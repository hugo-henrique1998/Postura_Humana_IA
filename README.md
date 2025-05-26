
# 🧠 Reconhecimento e Monitoramento de Posturas Humanas

Este repositório contém uma Prova de Conceito (PoC) para um sistema de visão computacional voltado ao reconhecimento e monitoramento de posturas humanas (deitado, sentado, em pé, em movimento) a partir de vídeos. A proposta contempla três atividades principais: curadoria e análise de dados (AT1), modelagem de modelos preditivos (AT2) e desenvolvimento de um sistema com API RESTful (AT3).

## 📁 Estrutura do Repositório

```
📦 projeto-posturas
├── AT1/              <- Scripts e ambiente virtual da AT1
├── AT2/              <- Scripts, modelos e ambiente virtual da AT2
├── AT3/              <- Em construção
├── dados/            <- Disponibilizado no link:
└── README.md         <- Este arquivo
```

## ✅ AT1 – Criação e Análise do Conjunto de Dados

🔹 **Descrição**: Seleção, limpeza e organização de um subconjunto representativo contendo três classes de posturas: em pé, sentado e em movimento.  
🔹 **Atividades realizadas**:
- Curadoria de dados com base no MPII Human Pose Dataset.
- Análise exploratória: distribuição de classes, qualidade das imagens, ruídos.
- Amostragem balanceada com 100 imagens por classe.
- Pré-processamento e salvamento dos dados em formato CSV e pastas organizadas.

📂 Diretório: `AT1/`  
📄 Relatório: `AT1/AT1 – Criação e análise do conjunto de dados.pdf`  
⚙️ Ambiente: ambiente virtual com bibliotecas de manipulação e visualização de dados.

## ✅ AT2 – Modelagem e Experimentação

🔹 **Descrição**: Desenvolvimento e comparação de modelos para reconhecimento de postura.  
🔹 **Modelos testados**:
- `PoseActionCNN`: uma CNN para regressão de keypoints e classificação de ações.
- `YOLOInspiredNet`: rede baseada na arquitetura YOLO com múltiplas saídas.

🔹 **Técnicas**:
- Validação cruzada
- Métricas de desempenho: accuracy, F1-score, classification report
- Hiperparâmetros ajustados para cada rede

📂 Diretório: `AT2/`  
📄 Relatório: `AT2/AT2 - Modelagem e experimentação.pdf`  
⚙️ Ambiente: ambiente virtual com PyTorch e bibliotecas de visualização e validação.

## 🚧 AT3 – Desenvolvimento do Sistema com API de Monitoramento (Em construção)

🔹 **Descrição**: API RESTful com autenticação, upload de vídeos, detecção de posturas e armazenamento dos resultados.

🔹 **Tecnologias planejadas**:
- Django Rest Framework + JWT
- Banco de dados PostgreSQL
- Upload e análise de vídeos
- Swagger para documentação
- Docker e docker-compose para execução

📂 Diretório: `AT3/` (em construção)

## ⚙️ Instruções Gerais

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/projeto-posturas.git
cd projeto-posturas
```

### 2. Entrar na pasta do projeto desejado (AT1 ou AT2)

```bash
cd AT1  # ou AT2
```

### 3. Criar e ativar ambiente virtual

```bash
Seguir Readme Correspondente de cada projeto
```

## 📌 Sobre o Projeto

Esta PoC foi desenvolvida como parte de uma avaliação técnica com o objetivo de demonstrar a capacidade de:
- Estruturar projetos de visão computacional de forma modular
- Trabalhar com curadoria, modelagem e validação de dados
- Integrar modelos em APIs reais com autenticação e persistência
