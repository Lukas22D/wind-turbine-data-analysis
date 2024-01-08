Análise de Dados: Turbina Eólica
Resumo
Este script realiza uma análise de dados relacionados a uma turbina eólica, utilizando a linguagem de programação Python e as bibliotecas pandas, seaborn e matplotlib. Ele lê um arquivo CSV contendo informações sobre a potência ativa, velocidade do vento, curva teórica e direção do vento. O código realiza o tratamento dos dados, visualização em gráficos e determina se a potência ativa está dentro de limites aceitáveis.

Bibliotecas Utilizadas
pandas: Para manipulação e análise de dados.
seaborn: Para criação de gráficos estatísticos atraentes.
matplotlib.pyplot: Para plotagem de gráficos.
matplotlib.pyplot.figure: Para controle adicional sobre o tamanho do gráfico.
Leitura e Tratamento de Dados
O script lê um arquivo CSV chamado "T1.csv" usando a biblioteca pandas, renomeia as colunas, remove uma coluna não utilizada e converte a coluna de data/hora para o formato apropriado.

Visualização em Gráficos
O código utiliza a biblioteca seaborn para criar dois gráficos de dispersão. O primeiro mostra a relação entre a velocidade do vento e a potência ativa real, enquanto o segundo compara a velocidade do vento com a curva teórica de potência.

Limites Aceitáveis
O script define limites aceitáveis para a potência ativa com base na curva teórica. Ele calcula valores máximos e mínimos permitidos, verifica se a potência real está dentro desses limites e determina a porcentagem de pontos dentro dos limites.

Adição de Informações ao DataFrame
Os resultados da verificação dos limites são adicionados ao DataFrame como a coluna 'DentroLimite'.

Gráfico com Limites
Finalmente, o código gera um gráfico de dispersão colorido, onde os pontos estão coloridos de acordo com a classificação 'DentroLimite' (Dentro, Fora ou Zero).

Nota: Certifique-se de que o arquivo "T1.csv" esteja presente no diretório de trabalho e contenha os dados esperados para uma execução bem-sucedida do script.




