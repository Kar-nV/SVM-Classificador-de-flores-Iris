<h1> Análise e Classificação de Flores Iris com Support Vector Machine (SVM)</h1>

<h2>Este código utiliza a biblioteca scikit-learn para realizar a classificação de flores Iris usando o algoritmo de Máquina de Vetores de Suporte (SVM). A análise é feita utilizando o algoritmo Support Vector Machine (SVM), um modelo de aprendizado de máquina para classificação e regressão.</h2>
<ol>
 <li> Carregamento dos Dados:
    <p>Utiliza o conjunto de dados Iris fornecido pela scikit-learn.</p>
    <p>Cria um DataFrame chamado iris com as características (features) e os rótulos (targets).</p>
 </li>
  <li>Apresentação Inicial da Base de Dados:
    <p>Exibe os primeiros 5 indivíduos da base de dados usando iris.head().</p>
  </li>
  <li>Estatísticas Básicas da Base de Dados:
    <p>Fornece algumas estatísticas básicas da base de dados, como médias, mínimos e máximos de cada coluna, usando iris.describe(). </p>
  </li>
  <li> Informações Detalhadas da Base de Dados:
    <p>Apresenta informações detalhadas sobre a base, como o tipo de cada coluna, a memória ocupada e outras informações relevantes, usando iris.info().</p>
  </li>

  <li> Treinamento do Modelo SVM:
    <p>Importa o algoritmo de Máquina de Vetores de Suporte (SVC) da scikit-learn.</p>
    <p>Configura o modelo SVC com um kernel automático (gamma="auto").</p>
     <p>Utiliza validação cruzada (cross_val_score) para avaliar a acurácia do modelo.</p>
  </li>
  <li> Avaliação do Modelo:
    <p>Exibe a acurácia média do modelo com validação cruzada.</p>
  </li>
  <li> Treinamento Final do Modelo:
    <p>Treina o modelo SVC com todos os dados disponíveis.</p>
  </li>
<<<<<<< HEAD
<p><img src='outputplt.png' alt='Gráfico contendo pontos coloridos referentes ao algoritmo SVM treinado'></p>
=======
>>>>>>> 72a5559fa8dbce0051bc9fcb47e1782be29e8d83
  <li> Predição de uma Nova Instância:
   <p> Prediz a qual classe pertencerá uma flor com características específicas usando svc.predict().</p>
  </li>
  <li> Visualização da Decisão do Modelo:
    <p>Cria um gráfico de dispersão (scatter plot) e um contorno de decisão para visualizar como o modelo SVM separa as classes com base nas características 'sepal length' e 'petal width'.</p>
  </li>
<p><img src='outputfinal.png'></p>
</ol>
<p>Esse código fornece uma introdução básica à classificação de flores Iris usando SVM e oferece uma visualização da decisão do modelo no espaço de características.</p>
