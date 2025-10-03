---
layout: post
title:  Taux de descompte et projets climatiques
categories: Économie de l'énergie de bas carbone
---

Faz pouco mais de um mês que comecei um mestrado na área de economia de energia, e diante de vários temas de estudo, as finanças corporativas se mostram verdadeiramente como uma ferramenta poderosa pra modelagem de problemas. De fato, só depois de rigorosos exemplos modelagem, somos realmente convidados a criticar de maneira mais lúcida a viabilidade de cada projeto sobre todos os aspectos, seja econômico, tecnológico e também suas dificuldades/facilidades regulatórias frente ao subsídio (ou a falta dele) fruto de ações governamentais.

Diante de diversos exercícios e projetos sobre fluxos de caixa, concepções claras sobre a diferença de valor e preço e de valor do dinheiro no tempo, me foi apresentada uma precificação um pouco "fora da caixa", sobre taxa de desconto e sua aplicabilidade para projetos relacionados ao clima.

Frequentemente, a avaliação de projetos está totalmente ligada a indicadores avaliados como ROCE, VPL, WACC, Taxa Interna de Retorno, payback, entre outros. A avaliação do fluxo de caixa, frente à estrutura de capital de um projeto tem o objetivo de responder uma simples pergunta fundamental: De posse das premissas econômicas, qual o valor de mercado do projeto hoje ao considerar seu fluxo de caixa futuro atualizado? Administradores, economistas e engenheiros discutem sempre como otimizar a estrutura de capital (com as oportunidades de mercado e de financiamento), afim de maximizar seu valor de mercado mas mantendo também a viabilidade técnica.

Mas no campo dos projetos de ciência climática, qual é a principal objeto de avaliação e como precificá-lo ? 

Um projeto de eficiência energética, por exemplo, pode ser classificado como um projeto climático, visto que nele tem-se direta ou indiretamente, abatimento de carbono, isto é, a emissão em tCO2eq que foi evitada a partir da instalação de uma tecnologia dita eficiente.

Assim, nosso fluxo de caixa na verdade, além de caixa (EUR), será composto também por tCO2 evitado, que há seu preço regulado na frança desde 2014 segundo [fonte](https://www.ecologie.gouv.fr/politiques-publiques/prix-du-carbone).

Há diversas formas para calcular o Abatimento de carbono, entre elas, utiliza-se por exemplo o custo de abatimento médio, em que é considerado uma taxa de desconto $i$ para atualizar as emissões pelo projeto que tem criação de valor definida pelo VPL (numerador da equação).

$C_{abat-moyen}=\frac{|VAN_{\text{classique}}|}{\sum\frac{ \Delta tCO_{2}}{(1+i)^t}}​​$

A interpretação é simples, se o Custo de abatimento de carbono de um projeto de eficiência energética é superior ao custo de emissão do carbono na atmosfera, o projeto é dito rentável do ponto de vista de carbono

Como por exemplo, podemos citar a instalação de bomba de calor (como parte do projeto de eletrificação de residências privadas na França) em substituição a aquecedores à gás. Assim, se o custo de abatimento é de 18EUR/tCO2 e o custo de emissão de carbono é de 80EUR/tCO2, temos uma grande rentabilidade do ponto de vista carbono.

Além disso, podemos, ainda, enquadrar florestas (projeto de sequestro de carbono) como projetos climáticos (mesmo estes sendo bens públicos, em que a precificação depende muitas vezes de metodologias bem específicas, mas este é um tema para outro artigo!). Assim, nosso objetivo é precificar a emissão negativa de carbono (sequestro) .

A filosofia é a seguinte: 

Um projeto de eficiência energética tem as seguintes premissas:

- Há uma prevalência de valor do capital (EUR) presente sobre o capital futuro (EUR).
- Há uma prevalência de valor do abatimento do carbono (tCO2 evitado) presente sobre o abatimento do carbono (tCO2 evitado) futuro (Visto que tem-se grande necessidade de redução de emissões de carbono hoje para melhor nos direcionarmos sobre os cenários estabelecidos pelo IPCC)
- De maneira geral, uma taxa de desconto positiva para cálculo do custo de abatimento de carbono equivale a dizer "Cada tonelada de CO2 evitada no futuro vale menos que uma tonelada de CO2 evitada hoje"
- Como vimos na equação $C_{abat-moyen}=\frac{|VAN_{\text{classique}}|}{\sum\frac{ \Delta tCO_{2}}{(1+i)^t}}​​$ , há a atualização da variação do CO2 evitado pela taxa $(1+i)$

Por outro lado, um projeto climático de sequestro de carbono, como uma floresta, podem ter as seguintes premissas:

- Visto que o carbono é capturado gradualmente o valor ambiental das florestas tende a aumentar.
- Além disso, a captura de carbono, por meio das florestas, pode estar sujeito a riscos de reversão (desmatamento, incêndio, etc...). 
- Sendo assim, políticas publicas apontam que uma floresta (desimpedida de sua plena capacidade de capturar carbono), diante dos riscos associados à sua diminuição por desmatamento, podem ter maior valor no futuro do que no presente, e por isso, as taxas de desconto muito baixas ou até negativas poderiam ser aplicadas, segundo alguns estudos/economistas ( i.e. Stern Review, Weitzman).
- Dessa forma, se aplicada taxa de desconto negativa, a floresta (projeto exemplo) tem refletida seu valor crescente no fluxo de caixa para as próximas gerações.
- Por isso, tendo em vista os riscos e incertezas associados às mudanças climáticas (que são evidentes, e contam com diferentes cenários de previsão/risco, de acordo com o IPCC), a taxa de desconto negativa valoriza mais o carbono capturado em um ano (ou demais períodos de tempo no nosso fluxo de caixa) do que agora.

O dilema entre taxa de desconto positiva e negativa lembra muito bem o _Paradoxe d’Allais_: nossas decisões não seguem apenas cálculos racionais de valor esperado, mas também percepções sobre tempo e risco. Do mesmo modo, a taxa escolhida redefine completamente o valor atribuído a cada projeto climático.

No que se refere ao modelo de conservação, cito aqui alguns exemplos de fundos internacionais com modelos de financiamento a longo prazo, com filosofia de valorização do futuro : Green Climate Fund, Climate Investment Funds (CIF), Cop Trust, Fundo Amazônia ou até mesmo o Fundo Florestas Tropicais para Sempre (TFFF), anunciado recentemente no ano de 2024.


## Conclusões

- Taxa positiva para abatimento: bom para projetos de mitigação imediata; preferível para engenharia, energia renovável, substituição de combustíveis fósseis.
    
- Taxa muito baixa ou negativa (apoiada por alguns economistas especialistas em clima e modelisação prospectiva) para sequestro natural: importante para assegurar que políticas de longo prazo (ex: conservação, restauração) não sejam desvalorizadas no presente.
    
- Políticas públicas e mercados de carbono precisam explicitar qual taxa está usando, e qual abordagem (tempo, risco, permanência) está incorporando — isso traz transparência e consistência.