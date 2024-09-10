# Projecto-de-Data-sciences
Introdução à Análise de Dados de Diabetes
A análise de dados de diabetes é crucial para entender os fatores que influenciam a progressão da doença e para desenvolver modelos preditivos eficazes. Neste estudo, utilizamos o conjunto de dados de diabetes disponível na biblioteca scikit-learn, que contém várias medidas médicas de pacientes, incluindo índice de massa corporal (BMI), pressão arterial (BP) e diversas medidas de sangue.

Objetivo
O objetivo desta análise é explorar a relação entre diferentes variáveis médicas e a progressão da doença em pacientes com diabetes. Utilizamos técnicas de visualização de dados e modelos de regressão para identificar padrões e avaliar a importância de cada variável.

Metodologia
Carregamento e Preparação dos Dados:
Utilizamos o conjunto de dados de diabetes da scikit-learn.
As variáveis independentes incluem medidas como BMI, BP e várias medidas de sangue.
A variável dependente é a progressão da doença.
Visualização dos Dados:
Criamos histogramas para entender a distribuição de cada variável.
Utilizamos gráficos de dispersão 3D para explorar a relação entre três variáveis específicas: BMI, BP e uma medida de sangue (s3).
Modelagem Preditiva:
Aplicamos modelos de regressão, incluindo Regressão Linear, Ridge e Lasso, para prever a progressão da doença.
Avaliamos a performance dos modelos usando métricas como Mean Squared Error (MSE) e R2 Score.
Analisamos a importância das variáveis no modelo de Regressão Ridge.
Resultados
Distribuição das Variáveis: Os histogramas mostraram a distribuição das variáveis, ajudando a identificar padrões e outliers.
Relação entre Variáveis: O gráfico de dispersão 3D revelou possíveis correlações entre BMI, BP e s3.
Performance dos Modelos: O modelo de Regressão Ridge apresentou um MSE de 2892.01 e um R2 Score de 0.45, indicando uma precisão moderada.
Importância das Variáveis: A análise dos coeficientes revelou que BMI e s3 são as variáveis mais influentes na progressão da doença.
Conclusão
Esta análise fornece uma visão abrangente dos fatores que influenciam a progressão da doença em pacientes com diabetes. As técnicas de visualização e modelagem preditiva utilizadas ajudam a identificar variáveis-chave e a avaliar a performance dos modelos, oferecendo insights valiosos para futuras pesquisas e intervenções médicas.
