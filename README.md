# Simulador e Calculadora de Investimentos em Excel

## Descrição do Projeto

Este projeto apresenta uma planilha desenvolvida no Microsoft Excel que atua como um simulador e calculadora de investimentos. O objetivo principal é proporcionar uma ferramenta prática para que usuários possam projetar o retorno de diferentes tipos de investimento, considerando variáveis como investimento inicial, aportes mensais, taxas de juros, prazos e impostos. A planilha foi criada para facilitar a visualização e comparação de cenários de investimento.

---

## Destaques do Aprendizado e Ferramentas Utilizadas

O curso de criação de planilhas para cálculos de investimento revelou-se fundamental para meu desenvolvimento, visto que proporcionou o domínio de ferramentas distintas do Excel e ampliou minha percepção sobre as capacidades da plataforma. A ferramenta de **Valor Futuro (VF)**, em particular, otimizou e facilitou significativamente a realização dos cálculos. Além dela, foram exploradas funções para cálculo de Rendimento Líquido, Imposto de Renda, e análise de diferentes tipos de investimento.

---

## Estrutura da Planilha (`Dio Invest.xlsx`)

A pasta de trabalho `Dio Invest.xlsx` é composta por, no mínimo, duas abas principais:

### 1. Aba "APP" (ou aba Principal)

Esta aba é o coração da calculadora, onde os parâmetros de investimento são inseridos e os resultados são exibidos. As colunas principais incluem:

* **Entradas do Usuário:**
    * `Investimento Inicial (R$)`: Capital inicial aportado.
    * `Investimento Mensal (R$)`: Aportes regulares.
    * `Taxa de Juros`: Juros aplicados ao investimento.
    * `Prazo (Meses)`: Duração total do investimento.
* **Resultados Calculados:**
    * `Rendimento Bruto (R$)`: Lucro total antes de descontos.
    * `Montante Final (R$)`: Capital total ao final do prazo (resultado do `VF`).
    * `Tipo de Rendimento`: Classificação do rendimento (e.g., prefixado, pós-fixado).
    * `Alíquota IR (%)`: Percentual do Imposto de Renda aplicado.
    * `Valor IR (R$)`: Valor absoluto do Imposto de Renda.
    * `Rendimento Líquido (R$)`: Lucro após a dedução do IR.
    * `Tipo de Investimento`: Categoria do investimento (e.g., CDB, LCI, Tesouro Direto).
    * `Retorno em x Meses`: Projeção de retorno em um período específico.

### 2. Aba "Planilha2" (ou aba de Referência/Configurações)

Esta aba parece conter dados de referência ou descrições para diferentes tipos de investimento ou cenários. Suas colunas são:

* `Nº`: Identificador numérico.
* `Nome`: Nome ou título do item.
* `Risco`: Classificação do risco associado (e.g., baixo, médio, alto).
* `Retorno Estimado`: Uma estimativa de retorno esperada.
* `Liquidez`: Facilidade com que o investimento pode ser convertido em dinheiro.
* `Descrição`: Detalhes adicionais sobre o item.

*Nota: Esta aba pode ser utilizada para alimentar listas suspensas na aba "APP" ou para oferecer informações adicionais sobre os tipos de investimento.*

---

## Como Utilizar a Planilha

Para simular seus investimentos:

1.  **Baixe o arquivo `Dio Invest.xlsx`** deste repositório.
2.  **Abra o arquivo** no Microsoft Excel ou em um software de planilhas compatível.
3.  **Navegue até a aba "APP"**.
4.  **Insira seus dados** nas células designadas (Investimento Inicial, Mensal, Taxa de Juros, Prazo).
5.  **Observe os resultados calculados** automaticamente, incluindo o montante final e o rendimento líquido.
6.  Explore as opções de "Tipo de Investimento" e "Tipo de Rendimento" para ver como afetam os resultados.
7.  Consulte a aba "Planilha2" para obter informações adicionais sobre os diferentes tipos de investimento listados.

---

## Tecnologias Envolvidas

* **Microsoft Excel:** Ambiente principal para o desenvolvimento e uso da planilha.
* **Funções Financeiras do Excel:**
    * `VF` (Valor Futuro): Essencial para calcular o montante final do investimento.
    * Outras funções como `JUROS`, `PGTO`, `TAXA`, e funções lógicas (`SE`, `E`, `OU`) e de busca (`PROCV`, `PROCH`) provavelmente foram utilizadas para os cálculos de rendimento líquido, IR e para integrar dados da "Planilha2".

