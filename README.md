## LIGHTHOUSE INDICIUM - Desafio Cientista de Dados

**Passa a passo para execução dos arquivos:**

1. Baixar os arquivos: *"desafio_indicium_imdb.csv"* e *"LH_CD_ARTUR.ipynb"*;
2. Certificar as versões indicadas nos arquivos de requisitos;
3. Executar o código em uma IDE do Python para uma visualização passo a passo do projeto (vale ressaltar que o arquivo .csv deve ser carregado junto com o código).

**Para previsão de novos dados:**

1. Baixar o arquivo: *"random_forest_model.pkl"*;
2. Carregar o arquivo .pkl em sua IDE Python e utilizar em uma célula de código o comando: `joblib.load('random_forest_model.pkl')` em uma variável, como: `loaded_model = joblib.load('random_forest_model.pkl')`;
3. Certificar-se de que os novos dados estão na estrutura definida no projeto;
4. Realizar a previsão dos dados pelo comando em uma célula de código: `loaded_model.predict(X_test)` (trocar a variável `loaded_model` pela utilizada em seu código).
