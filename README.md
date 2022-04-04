# 
Etapa 1. Criação de um banco e um tabela de acordo com excel em anexo localmente
O SGBD escolhido foi o MySQL com o server da Oracle. O arquivo 'banco-tabela.sql' contém o script sql que cria o banco 'vendas_2020', a tabela 'vendas_janeiro e carrega os dados do arquivo csv na tabela, convertendo valores '' para NULL.

Etapa 2. Leitura e tratamento dos dados do banco com python
Nessa etapa, a tabela 'vendas_janeiro' é atribuída a uma variável python no ambiente do Jupyter Notebook (arquivo 'leitura_e_tratamento.ipynb'). Os dados foram analizados, sofreram um processo de limpeza simples e seu comportamento foi explorado através de métodos da biblioteca pandas em função de alguns parâmetros listados. Daí foram extraídos insights e a tabela foi exportada em um arquivo excel (base_tratada.xlsx).

Etapa 3. Extrair da base 3 insights que considere relevante para o negócio


Etapa 4. Utilizar uma ferramenta de visualização a sua escolha para ilustrar seus insights
A ferramenta de visualização de dados escolhida foi o Power BI 
