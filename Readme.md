# Árvores de Decisão - Classificação

Este projeto implementa um modelo de árvore de decisão para prever a saída de funcionários de uma empresa. O modelo foi desenvolvido em Python utilizando a biblioteca `scikit-learn` e faz uso de análise exploratória para identificar variáveis importantes para a predição.

## 📁 Estrutura do Projeto

* **Data Loading**: Carrega o dataset de turnover.
* **Análise Exploratória**: Inclui informações gerais e estatísticas do conjunto de dados.
* **Criação do Modelo**: Desenvolvimento do modelo de árvore de decisão.
* **Avaliação do Modelo**: Métricas para validar a qualidade do modelo.

## 📝 Pré-requisitos

Certifique-se de ter os seguintes pacotes instalados:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn aed
```

## 📂 Dataset

O modelo utiliza o arquivo `base_rh.csv` que deve estar no mesmo diretório do script ou em um caminho acessível. O dataset deve conter a coluna `Funcionario_Deixou_Empresa` para identificar se o funcionário deixou ou não a empresa.

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu_usuario/seu_repositorio.git
cd seu_repositorio
```

2. Certifique-se de que o arquivo `base_rh.csv` está presente no diretório do projeto.

3. Execute o script:

```bash
python arvore_decisao.py
```

## 📊 Análise Exploratória

* Verificação de valores nulos e duplicados.
* Descrição das variáveis numéricas e categóricas.
* Matriz de gráficos para análise de correlações.

## 🌳 Desenvolvimento do Modelo

* Criação de variáveis dummy para variáveis categóricas.
* Separação das variáveis independentes (features) e dependentes (target).
* Divisão do dataset em conjuntos de treino e teste.
* Treinamento da árvore de decisão com profundidade máxima de 3.

## 📈 Avaliação do Modelo

* Acurácia do modelo.
* Relatório de classificação.
* Matriz de confusão para análise de erros de classificação.

## 📌 Resultados Esperados

* Árvore de decisão visualizada graficamente.
* Métricas de desempenho para análise do modelo.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📃 Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

## 📞 Contato

Criado por Walace Martinshttps://github.com/Wall009 - Entre em contato para mais informações.
