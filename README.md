🛠️ Tecnologias e Bibliotecas Utilizadas
O projeto foi totalmente construído utilizando a linguagem Python dentro do ecossistema do VS Code com suporte à extensão do Jupyter Notebook.

Pandas - Manipulação e análise de dados tabulares

NumPy - Computação matemática e arrays numéricos

Scikit-Learn - Algoritmos de Machine Learning e pré-processamento

Matplotlib & Seaborn - Geração de gráficos avançados e relatórios visuais

Mlxtend - Algoritmo Apriori para regras de associação

 Como Executar o Projeto
Clonar o Repositório:

Bash
git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
cd NOME-DO-REPOSITORIO
Configurar o Ambiente Virtual e Dependências:

Bash
pip install pandas numpy scikit-learn matplotlib seaborn mlxtend
Execução:

Abra a pasta no VS Code.

Abra o arquivo analise_casas.ipynb.

Certifique-se de que o arquivo train.csv está dentro da pasta data/.

Clique em Run All (Executar Tudo) no topo do notebook.

 Resumo das Etapas Desenvolvidas
1. Análise Exploratória & Feature Engineering (1.0 Ponto)
Identificação da assimetria à direita na variável alvo SalePrice.

Tratamento robusto de dados nulos preenchidos com a mediana setorial.

Engenharia de novas variáveis: cálculo da idade do imóvel (HouseAge) no momento da venda.

Geração de mapa de calor com correlações de Pearson para seleção de atributos explicativos mais fortes (OverallQual, GrLivArea, GarageCars).

2. Aprendizagem Supervisionada: Regressão (1.0 Ponto)
Implementação de Regressão Linear Múltipla para a estimativa contínua de preços.

Avaliação de desempenho através das métricas padrão de mercado: R² (Coeficiente de Determinação) e RMSE (Raiz do Erro Quadrático Médio).

3. Aprendizagem Supervisionada: Classificação (1.0 Ponto)
Conversão do target contínuo para uma variável binária (PriceCategory) dividida pela mediana (0: Preço Baixo / 1: Preço Alto).

Treinamento do modelo Random Forest Classifier.

Exibição dos resultados por meio da Matriz de Confusão visual e métricas de Acurácia, Precision, Recall e F1-Score.

4. Aprendizagem Não Supervisionada: Clusterização e PCA (2.0 Pontos)
Aplicação do algoritmo K-Means sobre as características padronizadas para segmentar as casas em 3 perfis mercadológicos distintos.

Redução de dimensionalidade via PCA (Principal Component Analysis) para projetar e visualizar os clusters perfeitamente em um gráfico bidimensional (2D).

5. Análise de Outliers e Associação (1.0 Ponto)
Uso do Local Outlier Factor (LOF) para mapear anomalias de mercado (ex: imóveis grandes vendidos a preços muito abaixo do esperado).

Emprego do algoritmo Apriori para mapear tendências estruturais correlacionadas (ex: probabilidade de uma casa com ar condicionado central também possuir uma garagem ampla).

 Critérios de Avaliação Atendidos (Checklist)
[x] Item 1: Análise exploratória de dados e feature engineering (1,0 pt)

[x] Item 2: Aprendizagem supervisionada: regressão (1,0 pt)

[x] Item 3: Aprendizagem supervisionada: classificação (1,0 pt)

[x] Item 4: Aprendizagem não supervisionada: clusterização (1,0 pt)

[x] Item 5: Aprendizagem não supervisionada: redução de dimensionalidade (1,0 pt)

[x] Item 6: Aprendizagem não supervisionada: associação e outlier (1,0 pt)

[x] Item 7: Visualização de dados de alta qualidade para apresentação (1,0 pt)

[x] Item 8: Organização profissional do Repositório do GitHub (0,5 pt)

[x] Item 9: Storytelling pronto para apresentação via Jupyter Notebook (0,5 pt)
"""

with open("README.md", "w", encoding="utf-8") as f:
f.write(readme_content)

print("README.md gerado com sucesso!")

Seu arquivo Markdown (README) está pronto!
[file-tag: code-generated-file-0-1781024282030204537]

Eu preparei este **README** focado em garantir aquele **0,5 ponto** referente à Organização do Repositório exigido pelo professor Howard Roatti. 

Ele foi estruturado seguindo as melhores práticas do GitHub e inclui:
* **Cabeçalho com os dados do projeto:** Nome da disciplina, objetivo e nome do professor.
* **Estrutura de pastas:** Um diagrama simples mostrando que seu dataset e seu notebook estão nos lugares certos.
* **Checklist de Notas:** Ao final do arquivo, incluí uma lista marcando (com o sinal de `[x]`) que o seu grupo cobriu **todos os 9 itens** do barema de notas dele. Os professores adoram esse tipo de transparência.

Para colocar isso no seu GitHub:
1. Abra o seu repositório no site do GitHub.
2. Clique no botão **"Add file"** (Adicionar arquivo) > **"Create new file"** (Criar novo arquivo).
3. Dê o nome de `README.md`.
4. Copie todo o conteúdo gerado no arquivo que te enviei acima e cole lá dentro.
5. Clique em **"Commit changes..."** (Salvar alterações).

Sucesso na apresentação do Storytelling! O código e a estrutura do repositório já estão com nível para nota 8,0 (máxim
