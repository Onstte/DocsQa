# Escrita do BDD

**BDD (Behavior Driven Development)** é uma técnica utilizada para integrar regras de negócios e linguagem de programação, caracterizando-se por um vocabulário bem específico e pequeno, que minimiza as dificuldades de comunicação e possibilita todos os membros do time utilizarem uma mesma linguagem para realizar o trabalho.

### O BDD vem sendo cada vez mais utilizado por permitir:

1. Que negócio e tecnologia se refiram a funcionalidades do software de uma só forma;
2. A visualização do valor de cada funcionalidade do software para o negócio;
3. Analisar, projetar e planejar tudo de cima a baixo sem retorno decrescente;
4. Compartilhamento de conhecimento entre analistas, desenvolvedores e testers;
5. Promover uma documentação dinâmica do software sem qualquer esforço a mais.

&#x20;Com a utilização dos BDD’s, é possível unir diversas práticas ágeis para um desenvolvimento qualitativo, sugerindo que analistas/testadores escrevam os cenários antes mesmo que a implementação aconteça, possibilitando assim, que os desenvolvedores tenham uma visão geral do projeto antes de codificá-lo.&#x20;

### O BDD durante o Teste do Software

Na metodologia do  BDD o analista de testes consegue planejar e criar os seus testes antes mesmo do desenvolvimento ser iniciado, assim, quebramos o paradigma de que o BDD seria aplicado como uma camada durante o desenvolvimento e passamos a vê-lo como um processo completo durante todo o projeto.

### Escrevendo seu teste funcional utilizando BDD

O planejamento e a escrita dos seus testes funcionais com a semântica do BDD é uma atividade importante, pois é a partir dessa etapa que você irá criar uma documentação viva que será utilizada por todos os membros do seu time.

### Qual é a semântica do BDD?

Para criar cenários de teste utilizando BDD usaremos as palavras chaves:

* Dado (Given);
* Quando (When);
* Então (Then).

Veja como estas palavras chaves devem ser utilizadas:

* Dado: Define as pré-condições verdadeiras para executar o seu teste
* Quando: Define a ação que será executada
* Então: Seguindo a ação descrita no QUANDO define o resultado esperado para o seu teste
* E: adiciona uma sentença positiva no Dado, no Quando ou no Então.&#x20;

