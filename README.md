# Limpeza de Dados em Pandas
Utilizei o Gemini para criar um exercício de limpeza de Dados em Pandas. Meu objetivo com esse exercício foi principalmente praticar a limpeza e organização dos dados.
<br>

## Importando Bibliotecas e DataFrame
<img align="right" width="500" height="483" alt="image" src="https://github.com/user-attachments/assets/2c09ba86-1abc-455a-915b-e1fe66c6534a">
O exercício se inicia com a importação das Bibliotecas Pandas e Numpy. Pandas serve para manipulação e análise de dados de forma eficiente e intuitiva. Ela é usada para trabalhar com dados tabulares, como tabelas numéricas e séries temporais, e é um pilar fundamental na área de análise de dados em Python, já o Numpy é uma biblioteca Python de código aberto para computação científica que serve principalmente para trabalhar com arrays multidimensionais e matrizes de forma eficiente.
<br><br>

## Visualizando informações do DataFrame
<img align="left" width="500" height="372" alt="image" src="https://github.com/user-attachments/assets/2fe4e5d8-0780-4107-9c30-e57d1caf8411">
Após a importação das Bibliotecas e da criação do DataFrame, utilizei o comando .info() apenas para visualizar em detalhe as informações sobre o DataFrame 
<br><br>

## Utilizando Replace e Astype
<img align="right" width="500" height="415" alt="image" src="https://github.com/user-attachments/assets/5936eb45-90ba-4467-8568-c21b9c4d5c7c">
Seguindo com o exercício, meu proximo objetivo foi remover os dados que estavam em falta na coluna 'Preco_Unitario', para isso utilizei o comando "df_vendas['Preco_Unitario'].replace('np.nan', 55, inplace=True)", com esse simples comando foi possível substituir todas as linhas com 'np.nan' pelo número solicitado, que no caso era o 55. No próximo passo do exercício, precisei mudar o tipo de dado de uma coluna, no caso a coluna 'Quantidade_Vendida', esse passo foi bem simples, bastou apenas escrever o código "df_vendas['Quantidade_Vendida'] = df_vendas['Quantidade_Vendida'].astype(int)" para alcançar o objetivo.
<br><br>

## Substituindo valores faltantes pela Média
<img align="left" width="500" height="269" alt="image" src="https://github.com/user-attachments/assets/b390862b-9a71-4fbf-8328-d9c2a528698d">
Continuando com o exercício, me foi solicitado trocar os valores faltantes restantes pela média de cada respectiva coluna, nesse momento admito ter tido um pouco de dificuldade, talvez pelo cansaço mental haha, porém, pesquisei um pouco e cheguei a conclusão da imagem ao lado.
<br><br>

## Resultado Final
<img align="right" width="500" height="442" alt="image" src="https://github.com/user-attachments/assets/6cb0c099-5ccd-493a-946d-d3754937bef3" />
O resultado final desse exercício foi um DataFrame completamente limpo e tratado, e com esse resultado, foi possível encontrar a resposta para duas perguntas, sendo elas, "Qual categoria obteve mais vendas" e "Qual livro obteve mais vendas", sendo a categoria "Data Science" e o livro "Python Básico".
<br><br>

## Ferramenta e linguagen utilizada
<div style="display: inline_block">
    <img align="center" alt="VSCode" height="40" width="40" src="https://code.visualstudio.com/assets/images/code-stable.png">
    <img align="center" alt="Python" height="40" width="40" src="https://icon.icepanel.io/Technology/svg/Python.svg">
</div>
