# 🚀 Projeto ETL - Sistema de Processamento de Dados

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![Status](https://img.shields.io/badge/Status-Completo-success.svg)

## 📋 Sobre o Projeto

Sistema completo de **ETL (Extract, Transform, Load)** desenvolvido em Python para processar dados de clientes da Empresa A&Z. O projeto demonstra as três etapas fundamentais da Ciência de Dados:

- **Extract**: Extração de dados de arquivos CSV
- **Transform**: Limpeza, padronização e enriquecimento dos dados
- **Load**: Carregamento dos dados processados com relatórios

## 🎯 Objetivos

- Demonstrar conhecimento prático em processos ETL
- Aplicar técnicas de manipulação de dados com Pandas
- Criar pipeline automatizado de processamento
- Gerar insights através de categorização e análise

## 🛠️ Tecnologias Utilizadas

- **Python 3.8+**
- **Pandas**: Manipulação e análise de dados
- **CSV**: Formato de entrada e saída de dados
- **Datetime**: Controle de timestamps

## 📂 Estrutura do Projeto

```
projeto-etl/
│
├── etl_az.py                    # Script principal do ETL
├── clientes_entrada.csv         # Arquivo de entrada (gerado automaticamente)
├── clientes_processados.csv     # Arquivo de saída (resultado do ETL)
├── README.md                    # Documentação do projeto
└── requirements.txt             # Dependências do projeto
```

## 🚀 Como Executar

### Pré-requisitos

```bash
pip install pandas
```

### Execução

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/projeto-etl.git
cd projeto-etl
```

2. Execute o script:
```bash
python etl_az.py
```

3. Na primeira execução, o sistema criará automaticamente um arquivo de exemplo `clientes_entrada.csv`

4. Execute novamente para processar os dados:
```bash
python etl_az.py
```

## 📊 Funcionalidades

### ✅ Etapa 1: Extract (Extração)
- Leitura de arquivo CSV
- Validação de dados
- Criação automática de arquivo de exemplo
- Contagem de registros extraídos

### ✅ Etapa 2: Transform (Transformação)
- **Limpeza**: Remoção de valores nulos
- **Padronização**: Formatação de nomes e valores
- **Categorização**: Classificação de clientes por saldo
  - Premium: Saldo ≥ R$ 10.000
  - Gold: Saldo ≥ R$ 5.000
  - Silver: Saldo ≥ R$ 1.000
  - Bronze: Saldo < R$ 1.000
- **Personalização**: Geração de mensagens customizadas
- **Timestamp**: Registro de data/hora do processamento

### ✅ Etapa 3: Load (Carregamento)
- Salvamento dos dados processados
- Geração de relatório estatístico
- Distribuição por categoria
- Análise de saldos (média, total, máximo, mínimo)

## 📈 Exemplo de Saída

```
==================================================
SISTEMA ETL - EMPRESA A&Z
Processamento de Dados de Clientes
==================================================

ETAPA 1: EXTRAÇÃO DE DADOS
✓ Arquivo carregado com sucesso!
✓ Total de registros extraídos: 6

ETAPA 2: TRANSFORMAÇÃO DE DADOS
✓ Removidos 0 registros com valores nulos
✓ Nomes padronizados
✓ Clientes categorizados
✓ Mensagens personalizadas geradas

ETAPA 3: CARREGAMENTO DE DADOS
✓ Dados carregados com sucesso
✓ Total de registros salvos: 6

RELATÓRIO DE PROCESSAMENTO
Distribuição por Categoria:
Premium    2
Gold       2
Silver     1
Bronze     1

Estatísticas de Saldo:
• Saldo Médio: R$ 7658.73
• Saldo Total: R$ 45952.40
```

## 💡 Aprendizados

Este projeto demonstra:

- Manipulação de dados com Pandas
- Boas práticas de ETL
- Tratamento de erros e exceções
- Geração de relatórios automatizados
- Documentação de código
- Criação de pipeline de dados reproduzível

## 🔄 Melhorias Futuras

- [ ] Integração com banco de dados (PostgreSQL/MongoDB)
- [ ] Interface gráfica com Streamlit
- [ ] Processamento em lote de múltiplos arquivos
- [ ] Integração com APIs externas
- [ ] Dashboard de visualização com Plotly
- [ ] Logs detalhados de processamento
- [ ] Testes unitários automatizados

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais e de portfólio.

## 👤 Autor

**Seu Nome**
- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- LinkedIn: [seu-perfil](https://linkedin.com/in/seu-perfil)

---

⭐ Se este projeto te ajudou, deixe uma estrela!

📧 Dúvidas? Entre em contato!