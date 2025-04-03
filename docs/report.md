# Os fatores que influenciam os salários dos profissionais de dados no Brasil.

INTEGRANTES:

Antonio Augusto Vieira Lopes Filho, aavlfilho@sga.pucminas.br

Daniel Pires de Andrade Boller, daniel.boller@sga.pucminas.br

Diego Rodrigo Marinho Silva, diego.marinho@sga.pucminas.br

Ryan Junio de Oliveira, ryan.junio@sga.pucminas.br

Vinicius Bigonha Cancela Moraes de Melo Filho, vbcmmfilho@sga.pucminas.br  

---

Professores:

Prof. Hugo Bastos de Paula

Prof. Hayala Nepomuceno Curto

---

_Curso de Ciência de Dados, Unidade Praça da Liberdade_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

**Resumo**. Este projeto propõe o desenvolvimento de um sistema inteligente para analisar como fatores como nível de formação, experiência profissional, porte da empresa, região de residência e domínio de tecnologias específicas influenciam os salários dos profissionais de dados no Brasil. Utilizando técnicas de aprendizado de máquina e análise estatística, o sistema processará dados de diversas fontes para identificar padrões e correlações entre essas variáveis e a remuneração. O objetivo é fornecer insights precisos que auxiliem profissionais e empresas a entenderem melhor os fatores que impactam os salários no setor de dados, contribuindo para decisões estratégicas de carreira e gestão de talentos. 

---


## Introdução

O mercado de dados no Brasil está em constante expansão, e diversos fatores influenciam a remuneração dos profissionais da área. Aspectos como nível de formação, experiência profissional, porte da empresa, localização geográfica e domínio de determinadas tecnologias podem impactar significativamente os salários. Compreender essas variáveis é essencial tanto para profissionais que buscam crescimento na carreira quanto para empresas que desejam atrair e reter talentos. Neste contexto, este projeto propõe o desenvolvimento de um sistema inteligente capaz de analisar e identificar padrões salariais no setor de dados, auxiliando na tomada de decisões estratégicas.

###    Contextualização

Nos últimos anos, a área de ciência de dados tem se consolidado como um dos segmentos mais promissores do mercado de trabalho, impulsionada pelo crescimento da transformação digital e pelo uso intensivo de dados nas tomadas de decisão empresariais. Com essa expansão, há um aumento na demanda por profissionais qualificados, o que torna relevante a análise dos fatores que influenciam a remuneração desses especialistas.
Nesse contexto, este projeto se insere na interseção entre inteligência artificial, análise de dados e mercado de trabalho, buscando compreender como diferentes características dos profissionais de dados impactam seus salários no Brasil. Para isso, o estudo utiliza um sistema inteligente capaz de processar grandes volumes de informações e identificar padrões relacionados a variáveis como nível de formação, experiência profissional, porte da empresa, localização geográfica e domínio de tecnologias específicas. Essa abordagem possibilita uma análise mais precisa e baseada em evidências sobre os determinantes salariais no setor.

###    Problema

O problema central deste projeto é entender quais características dos profissionais de dados no Brasil afetam de forma mais significativa seus salários. Essa questão é relevante tanto para trabalhadores que buscam otimizar suas trajetórias profissionais quanto para empresas que desejam estabelecer políticas salariais mais competitivas. O contexto da aplicação envolve o mercado de tecnologia e ciência de dados, abrangendo profissionais de diferentes perfis, desde iniciantes até especialistas, que atuam em empresas de diversos portes e segmentos. O estudo se baseia em dados reais, extraídos de fontes como o State of Data - BR 2023, para analisar padrões e tendências salariais no setor. 

###    Objetivo geral

Desenvolver um sistema inteligente para analisar o impacto de fatores como nível de formação, experiência profissional, porte da empresa, localização geográfica e conhecimento em tecnologias nos salários dos profissionais de dados no Brasil, utilizando dados extraídos do State of Data - BR 2023 e outras fontes complementares. 

####    Objetivos específicos

Analisar a relação entre nível de formação, experiência profissional e porte da empresa com a remuneração dos profissionais de dados no Brasil, utilizando técnicas de aprendizado de máquina e análise estatística.

Investigar o impacto da localização geográfica e do domínio de determinadas tecnologias no salário dos profissionais, identificando possíveis desigualdades regionais e valorização de habilidades específicas no mercado.

Desenvolver modelos preditivos capazes de estimar faixas salariais com base nos atributos dos profissionais, fornecendo insights para tomada de decisão sobre carreira e políticas salariais.

Implementar visualizações interativas e relatórios analíticos para facilitar a interpretação dos padrões identificados, tornando os resultados acessíveis para diferentes perfis de usuários.


###    Justificativas

A crescente demanda por profissionais de ciência de dados no Brasil, aliada às variações salariais influenciadas por múltiplos fatores, torna essencial a compreensão dos elementos que impactam a remuneração desses especialistas. Segundo o artigo "Carreira em Dados: conheça as principais áreas e como ingressar" (Alura, 2023), aspectos como nível de formação, experiência, porte da empresa, localização geográfica e domínio de tecnologias exercem influência direta sobre as oportunidades e os ganhos no setor. No entanto, ainda há uma lacuna na identificação quantitativa e preditiva desses fatores, dificultando a tomada de decisão tanto para profissionais que buscam progressão na carreira quanto para empresas que desejam formular políticas salariais competitivas.
Diante desse cenário, este projeto se justifica pela necessidade de um sistema inteligente capaz de analisar e prever os impactos desses fatores nos salários dos profissionais de dados no Brasil. Ao utilizar dados extraídos do State of Data - BR 2023 e outras fontes complementares, o sistema busca gerar insights estratégicos baseados em evidências, permitindo um entendimento mais profundo da valorização profissional no setor. Além disso, a implementação de modelos preditivos e visualizações interativas possibilita a democratização da informação, fornecendo subsídios para que profissionais façam escolhas informadas sobre suas carreiras e empresas ajustem suas políticas de remuneração de forma mais eficiente e equitativa.



##    Público alvo

A aplicação será utilizada por diferentes perfis de usuários que buscam compreender os fatores que influenciam os salários no setor de ciência de dados no Brasil. Esses usuários podem ter níveis variados de conhecimento sobre tecnologia e estatística, mas todos compartilham o interesse em tomar decisões informadas com base em dados. A seguir, são descritos os principais perfis de usuários:

**Profissionais de Ciência de Dados e Tecnologia**
**Perfil:** Engenheiros de dados, cientistas de dados, analistas de dados e desenvolvedores que desejam entender melhor o impacto de fatores como experiência, formação acadêmica e habilidades tecnológicas em seus salários. 
**Conhecimento prévio:** Alto conhecimento técnico em programação, estatística e machine learning. Familiaridade com análise de dados e interpretação de gráficos interativos. 
**Relação com a tecnologia:** Usuários experientes, que podem usar os resultados do sistema para planejar sua progressão de carreira e negociar salários. 

**Profissionais em Transição de Carreira**
**Perfil:** Pessoas migrando para a área de dados, vindas de setores como engenharia, administração, marketing e finanças. 
**Conhecimento prévio:** Nível intermediário a básico em ciência de dados e estatística. Interesse em entender quais habilidades e qualificações são mais valorizadas no mercado. 
**Relação com a tecnologia:** Familiarizados com ferramentas básicas de análise de dados, mas podem necessitar de suporte na interpretação dos resultados. 

**Recrutadores e Gestores de RH**
**Perfil:** Profissionais de Recursos Humanos e gestores que contratam e definem políticas salariais para equipes de dados. 
**Conhecimento prévio:** Baixo conhecimento técnico sobre ciência de dados, mas familiaridade com tendências de mercado e estruturação de cargos e salários. 
**Relação com a tecnologia:** Usam a aplicação para comparar remunerações, identificar padrões e embasar decisões estratégicas de contratação. 

**Empresas e Tomadores de Decisão**
**Perfil:** Diretores e líderes de empresas de tecnologia e dados que desejam entender melhor a dinâmica salarial do setor para definir estratégias de retenção e contratação. 
**Conhecimento prévio:** Alto conhecimento sobre negócios e gestão, mas limitado em análise de dados e machine learning. 
**Relação com a tecnologia:** Buscam relatórios e insights claros para embasar decisões estratégicas. 

## Análise exploratórida dos dados

###    Dicionário de dados

**State of Data Brazil 2023**
A base de dados State of Data Brazil 2023 é rica em informações sobre profissionais no setor de dados no Brasil, abordando tanto características demográficas quanto aspectos profissionais e de experiência no mercado de trabalho.
 
 	Salario Médio
Descrição: É a média da faixa salarial mensal 

Tipo de Dado: Qualitativo - Nominal - Multivariado

	Nível
Descrição: Indica níveis de carreira que se diferenciam pela experiência, autonomia e responsabilidades

Tipo de Dado: Qualitativo - Ordinal

	Número de Funcionários da Empresa
Descrição: Indica uma faixa do número de funcionários de uma empresa

Tipo de Dado: Qualitativo - Ordinal

	Situação Atual de Trabalho
Descrição: Indica o tipo de vínculo empregatício do profissional. 

Tipo de Dado: Qualitativo - Nominal - Multivariado

	Área de Formação
Descrição: Indica a área de formação acadêmica do profissional.

Tipo de Dado: Qualitativo - Nominal - Multivariado

	Estado de Origem
Descrição: Indica o estado originário do profissional.

Tipo de Dado: Qualitativo - Nominal - Multivariado

	Mudou de Estado
Descrição: Se o profissional mudou de estado.

Tipo de Dado: Tipo de Dado: Qualitativo - Nominal - Binário

	PCD (Pessoa Com Deficiência)
Descrição: Se o profissional possui alguma deficiência.

Tipo de Dado: Qualitativo - Nominal - Binário

	Estado onde Mora 
Descrição: Estado onde o profissional reside atualmente.

Tipo de Dado: Qualitativo - Nominal - Multivariado

	UF onde Mora 
Descrição: Unidade Federativa (UF) onde o profissional reside atualmente.

Tipo de Dado: Qualitativo - Nominal - Multivariado

	Região onde Mora
Descrição: Região geográfica do Brasil onde o profissional reside (Norte, Nordeste, Sudeste, Sul, Centro-Oeste).

Tipo de Dado: Qualitativo - Nominal - Multivariado

	Idade 
Descrição: Idade do profissional em anos.

Tipo de Dado: Quantitativo - Discreto

	Faixa de Idade
Descrição: Faixa etária do profissional (por exemplo, 22-24, 30-34, etc.).

Tipo de Dado: Qualitativo - Ordinal

	Gênero
Descrição: Gênero do profissional (Masculino, Feminino, etc.).

Tipo de Dado: Qualitativo - Nominal - Binário

	Etnia/Cor/Raça 
Descrição: Etnia, cor ou raça do profissional.

Tipo de Dado: Qualitativo - Nominal - Multivalorado

	Nível de Ensino 
Descrição: Nível de educação do profissional (Ensino Fundamental, Ensino Médio, Ensino Superior, Pós-Graduação).

Tipo de Dado: Qualitativo - Ordinal

	Faixa Salarial Mensal 
Descrição: Intervalo de renda mensal do profissional (por exemplo, R$2.000-R$4.000, R$8.000-R$12.000).

Tipo de Dado: Qualitativo - Ordinal

	Experiência Profissional em Dados 
Descrição: Tempo de experiência do profissional na área de dados (menos de 1 ano, 1-2 anos, 3-5 anos, etc.).

Tipo de Dado: Qualitativo - Ordinal

	Cargo Atual 
Descrição: Cargo ocupado pelo profissional (Analista de Dados, Cientista de Dados, Engenheiro de Dados, etc.).

Tipo de Dado: Qualitativo - Nominal - Multivariado

	Tamanho da Empresa 
Descrição: Porte da empresa onde o profissional trabalha (Startup, Pequena, Média, Grande Empresa, Multinacional).

Tipo de Dado: Qualitativo - Ordinal

	Modelo de Trabalho 
Descrição: Tipo de regime de trabalho (Presencial, Híbrido, Remoto).

Tipo de Dado: Qualitativo - Nominal - Multivariado

	Setor da Empresa 
Descrição: Setor de atuação da empresa (Bancos, Tecnologia, Saúde, Varejo, etc.).

Tipo de Dado: Qualitativo - Nominal - Multivariado

	IDHM
Descrição: Índice composto que sintetiza o desenvolvimento humano global do município, combinando os componentes de longevidade, educação e renda. O valor varia de 0 a 1, sendo que valores mais próximos de 1 indicam maior desenvolvimento.

Tipo de Dado: Quantitativo - Contínuo

	PIB
Descrição: Produto Interno Bruto é um indicador econômico que mede o valor total de bens e serviços produzido

Tipo de Dado: Quantitativo - Contínuo

###    Descrição de dados

|index|Idade|Mudou\_de\_estado|Salario\_Medio|Analytics\_Engineer|Engenharia\_de\_Dados/Data\_Engineer|Analista\_de\_Dados/Data\_Analyst|Cientista\_de\_Dados/Data\_Scientist|Database\_Administrator/DBA|Analista\_de\_Business\_Intelligence/BI|Arquiteto\_de\_Dados/Data\_Architect|Data\_Product\_Manager/DPM|Business\_Analyst|SQL|R|Python|C/C++/C\#|NET|Java|Julia|SAS/Stata|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|count|5293\.0|5172\.0|4651\.0|859\.0|859\.0|859\.0|859\.0|859\.0|859\.0|859\.0|859\.0|859\.0|3772\.0|3772\.0|3772\.0|3772\.0|3772\.0|3772\.0|3772\.0|3772\.0|
|mean|32\.0|0\.79|10028\.68|0\.32|0\.65|0\.68|0\.62|0\.22|0\.55|0\.32|0\.24|0\.4|0\.84|0\.11|0\.75|0\.02|0\.01|0\.09|0\.0|0\.04|
|std|7\.62|0\.4|6969\.22|0\.47|0\.48|0\.47|0\.48|0\.42|0\.5|0\.47|0\.43|0\.49|0\.37|0\.31|0\.43|0\.13|0\.1|0\.29|0\.05|0\.2|
|min|18\.0|0\.0|1050\.5|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|
|25%|27\.0|1\.0|5000\.5|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|1\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|0\.0|
|50%|30\.0|1\.0|10000\.5|0\.0|1\.0|1\.0|1\.0|0\.0|1\.0|0\.0|0\.0|0\.0|1\.0|0\.0|1\.0|0\.0|0\.0|0\.0|0\.0|0\.0|
|75%|36\.0|1\.0|14000\.5|1\.0|1\.0|1\.0|1\.0|0\.0|1\.0|1\.0|0\.0|1\.0|1\.0|0\.0|1\.0|0\.0|0\.0|0\.0|0\.0|0\.0|
|max|73\.0|1\.0|35000\.5|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|1\.0|

## Preparação dos dados

A preparação dos dados consiste dos seguintes passos:

> - Seleção dos atributos
> - Tratamentos dos valores faltantes ou omissos: remoção, substituição, indução, etc.
> - Tratamento dos valores inconsistentes: conversão, remoção de dados duplicados, remoção ou tratamento de ouliers.
> - Conversão de dados: p. ex. numérico para categórico, categórico para binário, etc.


## Indução de modelos

### Modelo 1: Algoritmo

Substitua o título pelo nome do algoritmo que será utilizado. P. ex. árvore de decisão, rede neural, SVM, etc.
Justifique a escolha do modelo.
Apresente o processo utilizado para amostragem de dados (particionamento, cross-validation).
Descreva os parâmetros utilizados. 
Apresente trechos do código utilizado comentados. Se utilizou alguma ferramenta gráfica, apresente imagens
com o fluxo de processamento.

### Modelo 2: Algoritmo

Repita os passos anteriores para o segundo modelo.


## Resultados

### Resultados obtidos com o modelo 1.

Apresente aqui os resultados obtidos com a indução do modelo 1. 
Apresente uma matriz de confusão quando pertinente. Apresente as medidas de performance
apropriadas para o seu problema. 
Por exemplo, no caso de classificação: precisão, revocação, F-measure, acurácia.

### Interpretação do modelo 1

Apresente os parâmetros do modelo obtido. Tentre mostrar as regras que são utilizadas no
processo de 'raciocínio' (*reasoning*) do sistema inteligente. Utilize medidas como 
o *feature importances* para tentar entender quais atributos o modelo se baseia no
processo de tomada de decisão.


### Resultados obtidos com o modelo 2.

Repita o passo anterior com os resultados do modelo 2.

### Interpretação do modelo 2

Repita o passo anterior com os parâmetros do modelo 2.


## Análise comparativa dos modelos

Discuta sobre as forças e fragilidades de cada modelo. Exemplifique casos em que um
modelo se sairia melhor que o outro. Nesta seção é possível utilizar a sua imaginação
e extrapolar um pouco o que os dados sugerem.


### Distribuição do modelo (opcional)

Tende criar um pacote de distribuição para o modelo construído, para ser aplicado 
em um sistema inteligente.


## 8. Conclusão

Apresente aqui a conclusão do seu trabalho. Discussão dos resultados obtidos no trabalho, 
onde se verifica as observações pessoais de cada aluno.

Uma conclusão deve ter 3 partes:

   * Breve resumo do que foi desenvolvido
	 * Apresenação geral dos resultados obtidos com discussão das vantagens e desvantagens do sistema inteligente
	 * Limitações e possibilidades de melhoria


# REFERÊNCIAS

Como um projeto de sistema inteligente não requer revisão bibliográfica, 
a inclusão das referências não é obrigatória. No entanto, caso você 
tenha utilizado referências na introdução ou deseje 
incluir referências relacionadas às tecnologias, padrões, ou metodologias 
que serão usadas no seu trabalho, relacione-as de acordo com a ABNT.

Verifique no link abaixo como devem ser as referências no padrão ABNT:

http://www.pucminas.br/imagedb/documento/DOC\_DSC\_NOME\_ARQUI20160217102425.pdf

Por exemplo:

**[1]** - _ELMASRI, Ramez; NAVATHE, Sham. **Sistemas de banco de dados**. 7. ed. São Paulo: Pearson, c2019. E-book. ISBN 9788543025001._

**[2]** - _COPPIN, Ben. **Inteligência artificial**. Rio de Janeiro, RJ: LTC, c2010. E-book. ISBN 978-85-216-2936-8._

**[3]** - _CORMEN, Thomas H. et al. **Algoritmos: teoria e prática**. Rio de Janeiro, RJ: Elsevier, Campus, c2012. xvi, 926 p. ISBN 9788535236996._

**[4]** - _SUTHERLAND, Jeffrey Victor. **Scrum: a arte de fazer o dobro do trabalho na metade do tempo**. 2. ed. rev. São Paulo, SP: Leya, 2016. 236, [4] p. ISBN 9788544104514._

**[5]** - _RUSSELL, Stuart J.; NORVIG, Peter. **Inteligência artificial**. Rio de Janeiro: Elsevier, c2013. xxi, 988 p. ISBN 9788535237016._



# APÊNDICES

**Colocar link:**

Do código (armazenado no repositório);

Dos artefatos (armazenado do repositório);

Da apresentação final (armazenado no repositório);

Do vídeo de apresentação (armazenado no repositório).




