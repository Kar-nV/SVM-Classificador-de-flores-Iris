#Análise e Classificação de Flores Iris com Support Vector Machine (SVM)

<h1> Este código em Python utiliza a biblioteca Scikit-Learn para realizar a análise e classificação de flores Iris. A análise é feita utilizando o algoritmo Support Vector Machine (SVM), um modelo de aprendizado de máquina para classificação e regressão.</h1>
<p>Este código utiliza a biblioteca scikit-learn para realizar a classificação de flores Iris usando o algoritmo de Máquina de Vetores de Suporte (SVM). Aqui está uma explicação concisa e objetiva do que o código realiza:</p>

    <ol>Carregamento dos Dados:
        <li>Utiliza o conjunto de dados Iris fornecido pela scikit-learn.</li>
        <li>Cria um DataFrame chamado iris com as características (features) e os rótulos (targets).</li>
     </ol>   

    <ol>Apresentação Inicial da Base de Dados:
        <p>Exibe os primeiros 5 indivíduos da base de dados usando iris.head().
    </ol>

    <ol>Estatísticas Básicas da Base de Dados:
        <p>Fornece algumas estatísticas básicas da base de dados, como médias, mínimos e máximos de cada coluna, usando iris.describe().
    </ol>

    Informações Detalhadas da Base de Dados:
        Apresenta informações detalhadas sobre a base, como o tipo de cada coluna, a memória ocupada e outras informações relevantes, usando iris.info().

    Treinamento do Modelo SVM:
        Importa o algoritmo de Máquina de Vetores de Suporte (SVC) da scikit-learn.
        Configura o modelo SVC com um kernel automático (gamma="auto").
        Utiliza validação cruzada (cross_val_score) para avaliar a acurácia do modelo.

    Avaliação do Modelo:
        Exibe a acurácia média do modelo com validação cruzada.

    Treinamento Final do Modelo:
        Treina o modelo SVC com todos os dados disponíveis.

    Predição de uma Nova Instância:
        Prediz a qual classe pertencerá uma flor com características específicas usando svc.predict().

    Visualização da Decisão do Modelo:
        Cria um gráfico de dispersão (scatter plot) e um contorno de decisão para visualizar como o modelo SVM separa as classes com base nas características 'sepal length' e 'petal width'.

Esse código fornece uma introdução básica à classificação de flores Iris usando SVM e oferece uma visualização da decisão do modelo no espaço de características.