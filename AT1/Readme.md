# Passo a Passo para Rodar a Aplicação do Projeto 

Siga os passos abaixo para rodar a aplicação no seu computador. Certifique-se de ter o **Miniconda** ou **Anaconda** instalado antes de começar. O objetivo é configurar um ambiente virtual, instalar as dependências e rodar a interface do projeto usando o **Jupyter Notebook**

---

## 1. **Instalar o Miniconda ou Anaconda** (Caso ainda não tenha instalado)
Primeiro, se ainda não tiver o **Miniconda** ou **Anaconda** instalado, siga as instruções para a instalação:

- **Miniconda**: [Baixar Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- **Anaconda**: [Baixar Anaconda](https://www.anaconda.com/products/individual)


## 2. **Abrir o Terminal no Diretório do Projeto**
- Abra o terminal (ou prompt de comando) e navegue até o diretório onde você baixou os arquivos do projeto.

## 3. **Criar o Ambiente Virtual com Conda a partir do arquivo environment**

Certifique-se de que está no diretório inicial da pasta **Notebook*. 
Crie um novo ambiente virtual com o **Conda**, digitando o seguinte comando no terminal. Isso garante que as dependências do projeto sejam isoladas:

```bash

conda env create -f environment.yml

```

## 4. **Ativando a ambiento virtual**

Ainda no prompt de comando, precisamos ativar o ambiente virtual. Assim, teremos tudo preparado e instanciado de forma a rodar os códigos corretamente.
Digite o seguinte código:

```bash

conda activate arcelor

```

## 5. **Iniciando o Jupyter Notebook**

Nesse momento, caso queira iniciar o Jupyter Notebook e verificar as análises, digite o seguinte código no prompt:

```bash

jupyter notebook

```
Obs: Assim que finalizar as operações no Jupyter, volte ao prompt e aperte "Ctrl+ c" para interromper o código. 

## 6. **Finalizando**

Após finalização do uso da aplicação, para encerrar o ambiente virtual utilize o seguindo código para sair do ambiente virtual:


```bash

conda deactivate

```
