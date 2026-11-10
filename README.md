# Reconhecimento de Faces via Random Forest e Eigenfaces

Autor: Pedro Nelson Nóbrega Monteiro Leite Fonseca

Projeto desenvolvido para a disciplina **DCA0133 - Aprendizagem de Máquina e Mineração de Dados** da Universidade Federal do Rio Grande do Norte (UFRN), sob orientação do Prof. Adrião Duarte Dória Neto.

## Descrição do Projeto

Este projeto aborda o problema de biometria facial utilizando técnica de redução de dimensionalidade por **PCA (Eigenfaces)** combinada ao algoritmo de classificação **Random Forest**. O objetivo é extrair características relevantes do conjunto de dados *Labeled Faces in the Wild* (LFW) e classificar as identidades com base na redundância espacial dos pixels vizinhos.

## Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Processamento Numérico:** NumPy
- **Visualização de Dados:** Matplotlib, Seaborn
- **Machine Learning & Redução de Dimensionalidade:** Scikit-Learn (`fetch_lfw_people`, `PCA`, `RandomForestClassifier`)

## Dataset

- **Fonte:** *Labeled Faces in the Wild* (LFW)
- **Filtro Aplicado:** Mínimo de 60 imagens por pessoa ( resize: 0.4 )
- **Amostras:** 1.348 imagens de 8 identidades distintas.
- **Dimensão original das imagens:** 50x37 pixels (1.850 características por imagem).

## Como Executar

1. Clone este repositório:
```bash
git clone [https://github.com/seu-usuario/face-recognition-eigenfaces.git](https://github.com/seu-usuario/face-recognition-eigenfaces.git)
cd face-recognition-eigenfaces
2. Instale as dependências
```bash
pip install -r requirements.txt
```