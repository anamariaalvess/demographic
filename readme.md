Neste projeto foi realizado uma análise de dados demográficos com as seguintes etapas:

1. Análise Inicial dos Dados:

Os dados foram carregados e explorados para entender sua estrutura, características e valores ausentes.
Foram exibidas informações sobre as primeiras linhas do conjunto de dados, os tipos de dados de cada coluna e estatísticas descritivas.

2. Visualização de Dados com Plotly:

Diferentes perguntas foram formuladas com base nos dados disponíveis, e gráficos foram gerados para respondê-las.
Gráficos de barra, gráficos de pizza (donut), e gráficos de barra agrupados foram utilizados para visualizar informações como a distribuição de raças, comparação de idade média entre homens e mulheres, porcentagem de pessoas com determinado nível de educação, entre outros.
As cores foram escolhidas de uma lista predefinida (color_list) para manter consistência entre os gráficos.

3. Salvando Gráficos em um Arquivo PDF:

Os gráficos gerados foram salvos em um arquivo PDF para facilitar a análise e compartilhamento.
Cada gráfico foi renderizado como uma imagem PNG usando o Plotly e, em seguida, as imagens foram agregadas em um arquivo PDF usando a biblioteca matplotlib.backends.backend_pdf.PdfPages.
Um loop foi utilizado para iterar sobre os gráficos e salvar cada um no arquivo PDF.

color_list =['#8fbee0', '#9ccbed', '#83d3dc', '#83d6c6', '#98d5af', '#a9cab4', '#c5b2be', '#d1a5c3', '#c59ab7', '#b98fac', '#ae84a1', '#a29fbd', '#9895b2', '#8d8ba8', '#9694b1', '#9f9dbb', '#a8a6c4']