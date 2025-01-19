# Exploração e análise de dados da bolsa formação com SQL e Python

###  O que seria o bolsa formação: A Bolsa Formação custeia a oferta de vagas gratuitas de cursos técnicos e de formação inicial e continuada.

Este programa integra políticas públicas de educação, inclusão social e desenvolvimento econômico. Geralmente, ele é implementado por meio de parcerias com instituições de ensino e entidades que oferecem cursos técnicos e de capacitação em diversas áreas.



##  Os dados

• UF: Estado onde foi destinada a bolsa

• MUNICIPIO: onde foi destinada a bolsa

• DEPEDENCIA ADMINISTRATIVA: (SYSTEM S) plataforma utilizada o para o gerenciamento interno do programa, (PÚBLICA) é uma plataforma mais voltada para o acesso do público em geral

• TIPO: tipo de formação da bolsa disponibilizada (FIC) formação Inicial e continuada, (TÉCNICO)

• MODALIDAE DE ENSINO: educação prensencial, ensino presencial, ensino a distância

• CURSO: todos os cursos ofertados na bolsa

• ANO HOMOLOGAÇÃO: refere-se ao ano em que o curso foi oficialmente reconhecido e aprovado pelas autoridades responsáveis.

• VAGAS HOMOLOGADAS: vagas de bolsa que foi oficialmente aprovada

A tabela foi criada no SQL SERVER com uma versão dos dados disponibilizados nessse dataset: https://dados.gov.br/dados/conjuntos-dados/bolsa-formacao

## Exploração de dados
**Fase inicial do processo de análise de dados em que irei buscar padrões, características para gerar insights iniciais.
Qual a quantidade de informações que temos na nossa base de dados?**


![image](https://github.com/user-attachments/assets/4d3e08b8-1c89-4673-b2fa-3307c894c513)

**Como são os dados:**

![image](https://github.com/user-attachments/assets/33a44391-cb2b-416c-972f-0db05df638e1)

**Quais os tipos de cada dado:**

![image](https://github.com/user-attachments/assets/34be7f42-9479-48dd-971c-307ef696bc69)

## Análise de dados

 ## **Depois de exploramos os dados e buscamos entender quais infomações temos em nosso banco de dados, podemos analisar as infomações para compreeender o que está acontecendo no dataset. Vamos fazer algumas perguntas:**

 **Os dez cursos com mais vagas ofertadas:**

 ![image](https://github.com/user-attachments/assets/357f6e68-3d6c-48f7-a253-0798293c9824)
 
 É possível notar uma grande variedade de setores em que os cursos foram selecionados.
 
 **Quantidade de cursos ofertados**

![image](https://github.com/user-attachments/assets/82d95b72-03b1-45db-b889-7b8bf94567c2)

**Anos com maiores disponibilidades de bolsas em ordem decrescente.**

![image](https://github.com/user-attachments/assets/e975dd35-21be-4a6f-b501-2e6d711c7fa6)

## Análise com gráficos em Pyhon 

https://github.com/lucassdeandrade/Project-sql-py/blob/main/BolsaForma%C3%A7%C3%A3oproject.ipynb


# Conclusão
Essas foram algumas análises extraídas do dataset BolsaFormação.

## Alguns insights interessantes:

 - Verificando os cursos com maiores vagas notamos uma forte presença da área de Tecnologia da Informação.

- A análise preliminar dos dados sugere uma tendência de diminuição no número de vagas ao longo dos anos, com algumas variações. tendo seu pico em 2014 e seu maior declínio em 2022.

- Vemos que os cursos do tipo: "Formação Inicial e Continuada" tem maior impacto de escolha. Isso se deve por serem cursos mais acessíveis e podem ser aplicados rapidamente no mercado de trabalho. Além de menor custo e maior disponibilidade.

- Temos uma diferença esmagadora de aproximadamente 95.42% entre o ensino presencial e o ensino EaD. Em um âmbito geral, isso se deve ao fato de que o ensino presencial favorece a interação social e a colaboração entre alunos e professores. Algo mais difícil no ambiente online.
