# Desafio - Módulo 3: Processamento de Dados Simplificado com Power BI
## Neste desafio do Módulo 3, você terá a oportunidade de explorar o processamento de dados usando o Power BI e realizar várias etapas de transformação e preparação de dados. O desafio aborda a integração de dados de um banco de dados MySQL na Azure, a verificação da qualidade dos dados e a criação de um modelo de dados sólido no Power BI.

## Passos do Desafio
1. Criação de uma Instância na Azure para MySQL
Configure uma instância na plataforma Azure para hospedar um banco de dados MySQL. Certifique-se de que o ambiente esteja corretamente configurado.
2. Criar o Banco de Dados com Base Disponível no GitHub
Utilize um banco de dados disponível no GitHub ou forneça um banco de dados com dados de exemplo.
3. Integração do Power BI com MySQL no Azure
Conecte o Power BI à instância do MySQL no Azure para importar os dados para o ambiente do Power BI.
4. Verificar Problemas na Base de Dados
Analise os dados importados para identificar problemas ou inconsistências na base de dados.
Diretrizes para Transformação dos Dados
1. Verifique os Cabeçalhos e Tipos de Dados
Certifique-se de que os cabeçalhos das colunas e os tipos de dados estejam corretos.
2. Modifique os Valores Monetários para o Tipo Double Preciso
Converta valores monetários para o tipo de dado "double preciso" se necessário.
3. Verifique a Existência de Nulos e Analise a Remoção
Identifique nulos e decida se eles devem ser removidos ou tratados de outra forma.
4. Identifique Colaboradores Sem Gerente
Verifique se colaboradores com nulos em "Super_ssn" são gerentes e se há colaboradores sem gerente.
5. Verifique se Há Departamentos Sem Gerente
Confira se existem departamentos sem gerente e, se for o caso, preencha essas lacunas.
6. Verifique o Número de Horas dos Projetos
Avalie os números de horas registrados nos projetos para identificar possíveis problemas.
7. Separe Colunas Complexas
Se necessário, separe colunas complexas em colunas individuais.
8. Crie uma Tabela de Employee com os Nomes dos Departamentos
Combine dados das tabelas "employee" e "departament" para criar uma tabela que associe os nomes dos departamentos aos colaboradores.
9. Elimine Colunas Desnecessárias
Remova as colunas desnecessárias que não serão usadas no relatório.
10. Realize a Junção dos Colaboradores e Respectivos Nomes dos Gerentes
Execute uma junção entre colaboradores e seus respectivos gerentes, podendo ser feita com consulta SQL ou mescla de tabelas no Power BI.
11. Mescle as Colunas de Nome e Sobrenome
Combine as colunas de nome e sobrenome em uma única coluna que defina os nomes dos colaboradores.
12. Mescle os Nomes de Departamentos e Localizações
Realize a mescla dos nomes de departamentos e localizações para criar combinações únicas que serão úteis na criação de um modelo estrela em um módulo futuro.
13. Explique Por Que Usar a Mescla em Vez do Atribuir
Explique por que, no contexto deste desafio, a mescla de tabelas foi preferível à atribuição de valores.
14. Agrupe os Dados para Saber Quantos Colaboradores Existem por Gerente
Crie uma medida ou fórmula para calcular quantos colaboradores existem para cada gerente.
15. Elimine Colunas Desnecessárias
Finalize o processo eliminando qualquer coluna que não será usada no relatório final.
