# [Lighthouse] Desafio Cientista de Dados
<img src="https://s.wsj.net/public/resources/images/BN-QX295_1122ca_M_20161122005238.jpg" />

### **Motivação:**

Este desafio proposto pela INDICIUM representa uma excelente oportunidade para colocar em prática meus conhecimentos em resolução de problemas de negócios, análise de dados e desenvolvimento de modelos preditivos.

### **O desafio:**

“Você foi alocado(a) em um time da Indicium que está trabalhando atualmente junto a um cliente que o core business é compra e venda de veículos usados. Essa empresa está com dificuldades na área de revenda dos automóveis usados em seu catálogo. Para resolver esse problema, a empresa comprou uma base de dados de um marketplace de compra e venda para entender melhor o mercado nacional, de forma a conseguir precificar o seu catálogo de forma mais competitiva e assim recuperar o mau desempenho neste setor. Seu objetivo é analisar os dados para responder às perguntas de negócios feitas pelo cliente e criar um modelo preditivo que precifique os carros do cliente de forma que eles fiquem o mais próximos dos valores de mercado.”

### **Objetivo:**

Analisar os dados disponíveis para responder de forma assertiva às perguntas de negócio formuladas pelo cliente e, com base nessa análise, desenvolver um modelo preditivo capaz de estimar os preços dos veículos de maneira competitiva, aproximando-os ao máximo dos valores praticados no mercado.

-----------------------

### **Dados:**

Os dados foram fornecidos pela Indicium, e estão disponíveis para download [aqui](https://github.com/reisricardo1/desafioDC/blob/master/data/cars_training.csv) no repositório.

-----------------------
## Notebooks
Nesse repositório você encontrará dois notebooks, um deles destinado a **EDA(Análise Exploratória dos Dados)**, e outro destinado ao **modelagem(ML)**.

[**EDA.ipynb**](https://github.com/reisricardo1/desafioDC/blob/master/EDA.ipynb): 

Nesse notebook você encontrará análise exploratória dos dados, assim como a solução das questões de negócio propostas pelo desafio; a formulação e teste de três hipóteses de negócio adicionais.

#### Hipóteses:
**Hipótese 1:** Carros com blindagem tendem a ter um preço mais alto.

**Hipótese 2:** Carros mais antigos tendem a ter um hodômetro mais alto.

**Hipótese 3:** O tipo de vendedor (PF vs PJ) influencia no preço médio dos veículos.


#### Questões de Negócio:
**Pergunta 1:** Qual o melhor estado cadastrado na base de dados para se vender um carro de marca popular e por quê?

**Pergunta 2:** Qual o melhor estado para se comprar uma picape com transmissão automática e por quê?

**Pergunta 3:** Qual o melhor estado para se comprar carros que ainda estejam dentro da garantia de fábrica e por quê?

[**modelagem.ipynb**](https://github.com/reisricardo1/desafioDC/blob/master/modelagem.ipynb): 

Neste notebook, você encontrará todo o processo de pré-processamento, modelagem de dados e treinamento de nossos modelos preditivos.

------------

## Requisitos e Replicações:

Neste projeto, foi utilizada a versão 3.12.3 do Python

A versão do pip utilizada é a 24.0

A versão do git utilizada é a 2.43.0

Demais requisitos se encontram no arquivo requirements.txt

<details>
  <summary>Para utilizar este projeto, siga as instruções abaixo:</summary>

  <details>
    <summary>Passo 1: Clonar o repositório</summary>

    git clone https://github.com/reisricardo1/desafioDC.git

  </details>

  <details>
    <summary>Passo 2: Instalar os pacotes nas versões utilizadas</summary>

    pip install -r requirements.txt
    
  </details>

</details>

