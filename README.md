# Estudo da Relação entre Horários de Disciplinas e o Desempenho Acadêmico dos Estudantes da UFRN

# 1 Introdução
A **Universidade Federal do Rio Grande do Norte (UFRN)** oferta turmas em diferentes horários: desde o início da manhã (7h) a tarde da noite (22h15). É comum que alunos evitem os horários mais extremos por, entre outros fatores, possíveis problemas de sono e cansaço, dificuldade de locomoção e gerenciamento de tempo. Não há, no entanto, estudos disponíveis que mostrem diferenças de desempenho acadêmico causados por esses horários.

## 1.1 Objetivo
Este projeto tem como intuito o estudo da relação entre horários de disciplinas e o desempenho de estudantes de forma geral em toda a UFRN.

### 1.1.1 Objetivos Gerais

* Analisar o rendimento dos alunos em diferentes horários nos quais as disciplinas são ofertadas; e
* Verificar se o horário possui influência no rendimento e capacidade de abstração dos estudantes.

### 1.1.2 Objetivos Específicos

* Verificar os horários em que há menos ou mais aprovações;
* Descobrir os horários em que há porcentagem alta de faltas;
* Apurar os horários que têm mais alunos;
* Verificar os horários em que há mais ou menos trancamentos; e
* Verificar os horários em que as médias finais são maiores ou menores.

# 2 Base de Dados

Os dados usados para análise e posterior interpretação foram tirados do  [Portal de Dados Abertos da UFRN](http://dados.ufrn.br/). As bases de dados utilizadas são referentes a todos os níveis — médio e superior — em toda a Universidade e armazenam informações dos períodos de 2014.1 a 2017.1. Sendo as bases:

* [DataSet de Matrículas](http://dados.ufrn.br/dataset/matriculas-componentes)
* [DataSet de Turmas](http://dados.ufrn.br/dataset/turmas)

A fim de se simplificar o processo de análise estatística dos dados, mesclamos as duas bases de dados em um único DataSet chamado **turmas-plus.csv**, que pode ser acessado na pasta **data**.

## 2.1 Leitura e Tratamento
A fim de se efetuar a leitura e manejo das bases de dados, utilizamos os módulos **pandas** e **numpy**. A interpretação dos dados é facilitada por ferramentas visuais, portanto, importamos, também, a biblioteca **matplotlib** para formulação de gráficos. Antes de começar os processos de análise, foi necessário **tratar** as bases de dados, uma vez que essas têm muitas informações.

# 3 Metodologia
O objetivo desse projeto é analisar a relação de desempenho acadêmico dos alunos da **UFRN** de acordo com os **horários** nos quais as disciplinas são ofertadas. Como nossa variável principal, isto é, nosso campo alvo de análise, são os horários e, por tal, não mantêm entre si relação de ordem quantitativa, abordamos visualmente as informações por meio de **gráficos de barras**. pois este é o modelo mais indicado para **variavéis nominais (qualitativas)**. Pode-se abstrair o caráter quantitativo por ordem **cronológica** — decorrer do dia letivo —, porém a ideia fica muito subjuntiva e vaga, mas serve para fins de organização.

# 4 Conclusão
A escolha do horário no qual o discente pagará a disciplina é um fator importante, uma vez que se percebeu um padrão no desempenho dos alunos nos três semestres analisados. Aconselha-se, com base nos resultados da pesquisa, aos interessados em cursar **Linguagem de Programação I** que optem, preferencialmente, pelos **horários da noite** e que evitem, assim, o turno vespertino.

A escolha do horário no qual o discente pagará as disciplinas é um fator importante, uma vez que, analisando os resultados dos três semestres estudados, percebe-se que o rendimento dos alunos no turno noturno é inferior aos demais horários. Pode haver inúmeros fatores que não foram registrados no DataSet que expliquem esse comportamento: alunos que trabalham e estudam, cuidam de casa... No entanto, pode-se afimar uma relação entre a taxa de faltas e o mau desempenho acadêmico: movimento perceptível no DataSet. É visível a diminuição na **média de notas dos alunos** do turno noturno. Talvez, as faltas sejam causadas por esses mesmos fatores externos. Não podemos, porém, confimar.

# 5 Autoria
Projeto desenvolvido por **Lucas Miguel Martiniano** ([lus-cas](https://github.com/lus-cas)).