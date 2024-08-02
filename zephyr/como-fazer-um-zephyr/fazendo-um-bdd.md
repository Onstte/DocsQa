# Fazendo um BDD

#### Exemplo de BDD

## **Termos Chave do BDD e Seus Usos**

1. **Como (Como um...)**
   * **Objetivo:** Descreve o papel ou a pessoa que está solicitando uma funcionalidade.
   * **Exemplo:** "Como um Pedestre"
2. **Eu quero (Eu quero que...)**
   * **Objetivo:** Define o desejo ou a necessidade que deve ser atendida.
   * **Exemplo:** "Eu quero que as luzes do semáforo fiquem vermelhas"
3. **Assim que (Assim que...)**
   * **Objetivo:** Especifica a condição que deve ocorrer para que o comportamento desejado seja ativado.
   * **Exemplo:** "Assim que eu me aproximar da faixa de pedestre"
4. **Dado (Dado que...)**
   * **Objetivo:** Define o contexto ou o estado inicial do sistema antes da ação ocorrer.
   * **Exemplo:** "Dado que a luz do semáforo esteja verde"
5. **Quando (Quando...)**
   * **Objetivo:** Descreve a ação que ocorre e que deve causar uma mudança ou desencadear um comportamento.
   * **Exemplo:** "Quando uma pessoa se aproximar da faixa de pedestre"
6. **Então (Então...)**
   * **Objetivo:** Define o resultado esperado ou o comportamento do sistema após a ação.
   * **Exemplo:** "Então a luz do semáforo deve ficar vermelha"
7. **E (E...)**
   * **Objetivo:** Adiciona mais condições ou passos dentro do mesmo cenário.
   * **Exemplo:** "E não houver mais pessoas se aproximando da faixa de pedestre"
8. **Mas (Mas...)**
   * **Objetivo:** Introduz uma exceção ou uma condição adicional que deve ser considerada.
   * **Exemplo:** "Mas somente até que pessoas se aproximem da faixa de pedestre"

## **Exemplos de Cenários em BDD**

**Funcionalidade:** Alteração automática das luzes de um semáforo

**Como u m Pedestre**

**Eu quero** que as luzes do semáforo fiquem vermelhas

**Assim que** eu me aproximar da faixa de pedestre

**Cenário 1: Alteração das Luzes de Verde para Vermelho**

* **Dado** que a luz do semáforo esteja verde
* **Quando** uma pessoa se aproximar da faixa de pedestre
* **Então** a luz do semáforo deve ficar vermelha

**Cenário 2: Alteração das Luzes de Vermelho para Verde**

* **Dado** que a luz do semáforo esteja vermelha
* **Quando** não houver pessoas na faixa de pedestre
* **E** não houver mais pessoas se aproximando da faixa de pedestre
* **Então** a luz do semáforo deve voltar a verde
* **Mas** somente até que novas pessoas se aproximem da faixa de pedestre

## **Resumo**

* **Dado:** Define o contexto inicial.
* **Quando:** Especifica a ação ou evento.
* **Então:** Descreve o resultado esperado.
* **E:** Adiciona mais condições ou passos.
* **Mas:** Introduz exceções ou condições adicionais.
