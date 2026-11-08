# Gestão contábil de pizzaria

Escopo: CMV, ficha técnica, custos fixos e variáveis, ponto de equilíbrio, DRE, fluxo de caixa e organização de documentos.

> Esta referência é de gestão, não de contabilidade oficial. Regime tributário, alíquotas, obrigações acessórias e escrituração devem ser validados com contador habilitado.

## Ficha técnica

A ficha técnica é a base de todo cálculo de custo. Para cada pizza, registre:

| Ingrediente | Unidade | Quantidade por pizza | Custo unitário | Custo por pizza |
|---|---|---|---|---|
| Massa | kg | 0,250 | R$ __ | R$ __ |
| Queijo muçarela | kg | 0,120 | R$ __ | R$ __ |
| Molho de tomate | kg | 0,060 | R$ __ | R$ __ |
| Embalagem (caixa) | un | 1 | R$ __ | R$ __ |
| *Total* | | | | *R$ __* |

Regras:
- Use peso, não medida caseira, para ingredientes que variam (queijo, carne, cobertura).
- Inclua ingredientes compostos (molho, massa), com a receita do preparo e o rendimento.
- Inclua a embalagem e o material de entrega, que muitas vezes são esquecidos.
- Atualize a ficha sempre que o custo de um insumo mudar de forma relevante.
- Quando o preço de um insumo muda, recalcule o custo de todas as fichas que o usam.

## CMV (custo da mercadoria vendida)

**Fórmula:** CMV = Estoque inicial + Compras − Estoque final

**Percentual:** CMV % = CMV ÷ Faturamento do período

Boas práticas:
- Faça o cálculo mensal, com contagem de estoque no início e no fim do mês.
- Separe as compras por categoria (proteína, laticínio, hortifrúti, embalagem, bebida), para ver onde o custo cresce.
- Compare o CMV teórico (vendas × ficha técnica) com o CMV real (fórmula acima). A diferença é perda, desperdício, erro de porção ou furto. Investigue.
- Use o CMV % como alerta de tendência. Uma subida de 2 ou 3 pontos percentuais sem explicação merece análise.

**Exemplo ilustrativo (valores fictícios):** estoque inicial R$ 8.000, compras R$ 30.000, estoque final R$ 7.000. CMV = 8.000 + 30.000 − 7.000 = R$ 31.000. Se o faturamento do mês foi de R$ 90.000 sem impostos, CMV % = 31.000 ÷ 90.000 ≈ 34,4%.

## Custos fixos e variáveis

| Tipo | Exemplos típicos em pizzaria |
|---|---|
| Fixos (não variam com o volume no curto prazo) | Aluguel, condomínio, IPTU, energia básica, internet, contador, sistema de gestão, salários fixos, seguros, licenças |
| Variáveis (variam com o volume) | Insumos e embalagens, comissão de aplicativo, taxa de cartão, taxa de entrega paga a motoboy por corrida, impostos sobre a venda, gás e energia do forno em função do uso |

Atenção:
- Entregador por diária ou salário é fixo; entregador por corrida é variável. Classifique conforme o contrato.
- Se o custo de energia ou gás cresce com o uso, trate como semivariável e rateie por volume ou por faixa.

## Ponto de equilíbrio

**Ponto de equilíbrio (faturamento)** = Custos fixos ÷ Margem de contribuição %

Margem de contribuição % = (Faturamento − Custos variáveis) ÷ Faturamento

**Exemplo ilustrativo (valores fictícios):** custos fixos de R$ 25.000 por mês; custos variáveis de 55% do faturamento, então margem de contribuição de 45%. Ponto de equilíbrio = 25.000 ÷ 0,45 ≈ R$ 55.556 por mês.

Use para responder: "quanto preciso vender para não ter prejuízo?" e "quanto custa, em faturamento, cada aumento de aluguel ou de salário?".

## DRE simplificado (demonstração do resultado)

| Linha | Exemplo de cálculo |
|---|---|
| (+) Faturamento bruto | Vendas de todos os canais |
| (−) Deduções (impostos sobre a venda, devoluções, descontos) | Conforme regime tributário |
| (=) Receita líquida | Bruto − deduções |
| (−) CMV | Fórmula acima |
| (=) Lucro bruto | Receita líquida − CMV |
| (−) Despesas operacionais | Mão de obra, aluguel, energia, marketing, taxas de cartão, comissão de aplicativo, entrega |
| (=) Resultado operacional (EBITDA simplificado) | Lucro bruto − despesas operacionais |
| (−) Depreciação, juros e outras despesas financeiras | Equipamentos, financiamentos |
| (=) Lucro líquido antes de impostos sobre o lucro | Resultado − itens acima |

Gere o DRE todo mês, com o mesmo plano de contas. Comparar mês a mês mostra a tendência.

## Fluxo de caixa

Lucro não é caixa. Uma pizzaria pode dar lucro no papel e faltar dinheiro, se as vendas no cartão e no aplicativo demoram para cair, se o estoque é pago à vista e se há parcelas de equipamentos.

- **Projete o caixa para 30, 60 e 90 dias**, com entradas (vendas por forma de pagamento e prazo de recebimento) e saídas (fornecedores, salários, impostos, aluguel, parcelas).
- **Registre diariamente** entradas e saídas, por categoria.
- **Concilie** o caixa com o extrato bancário e com os recebimentos das operadoras de cartão e dos aplicativos. Diferenças aparecem aí.
- **Mantenha reserva** de pelo menos o valor de um ou dois meses de custos fixos, se possível.
- **Separe conta pessoal da conta da empresa.** Misturar as duas é a causa mais comum de falta de controle.

## Tributos e documentos (orientação geral)

- Confirme com o contador o regime tributário da empresa (por exemplo, Simples Nacional, Lucro Presumido ou Lucro Real) e como as vendas por aplicativo e por cartão são tributadas.
- Guarde notas fiscais de compra e de venda, comprovantes de pagamento e relatórios das operadoras e dos aplicativos. Organize por mês.
- Verifique obrigações trabalhistas e previdenciárias do funcionário e do entregador, incluindo o vínculo de motoboy, com o contador ou advogado trabalhista. A classificação do vínculo tem consequências relevantes.
- Licenças de funcionamento, alvará e vigilância sanitária são responsabilidade da empresa. Confirme com o órgão municipal.

## Indicadores financeiros (painel mensal)

| Indicador | Como medir |
|---|---|
| CMV % | CMV ÷ faturamento |
| Margem bruta | Lucro bruto ÷ receita líquida |
| Custos fixos sobre faturamento | Custos fixos ÷ faturamento |
| Ponto de equilíbrio vs. faturamento real | Comparar os dois valores |
| Saldo de caixa no fim do mês | Saldo bancário conciliado |
| Prazo médio de recebimento | Média de dias entre a venda e o recebimento |
| Inadimplência de vendas a prazo ou de convênio | Valor não recebido ÷ valor a receber |

## Erros comuns

- Calcular CMV só pela compra, sem contagem de estoque.
- Não incluir embalagem e entrega no custo do produto.
- Precificar sem considerar a taxa do aplicativo e os impostos.
- Confundir lucro com caixa disponível.
- Não separar conta pessoal da conta da empresa.
- Deixar as notas e os comprovantes para o fim do ano.

## Exemplo completo: unidade econômica de uma pizza

> Valores fictícios para ilustrar o método. Substitua pelos seus custos reais.

**1. Custo de insumos e embalagem (pizza grande de muçarela)**

| Ingrediente / item | Quantidade | Custo unitário | Custo na pizza |
|---|---|---|---|
| Massa | 250 g | R$ 6,00/kg | R$ 1,50 |
| Muçarela | 150 g | R$ 40,00/kg | R$ 6,00 |
| Molho de tomate | 60 g | R$ 8,00/kg | R$ 0,48 |
| Orégano, azeite e outros | — | rateio | R$ 0,30 |
| Caixa e sacola | 1 un. | R$ 1,20 | R$ 1,20 |
| **Total** | | | **R$ 9,48** |

**2. Preço e custos variáveis por canal**

| Item | Balcão / telefone | Aplicativo (taxa de 23%) |
|---|---|---|
| Preço de venda | R$ 45,00 | R$ 45,00 |
| Custo de insumos e embalagem | − R$ 9,48 | − R$ 9,48 |
| Impostos sobre a venda (6%, ilustrativo) | − R$ 2,70 | − R$ 2,70 |
| Comissão do aplicativo (23%) | — | − R$ 10,35 |
| **Margem de contribuição** | **R$ 32,82 (72,9%)** | **R$ 22,47 (49,9%)** |

Leitura: a mesma pizza rende 23 pontos percentuais a menos quando vendida pelo aplicativo, com a comissão como principal diferença. Isso não significa abandonar o canal; significa que o aplicativo precisa ser contabilizado como canal próprio, com meta de volume e de lucro.

**3. Ponto de equilíbrio em quantidade de pizzas**

- Custos fixos mensais: R$ 30.000 (aluguel R$ 8.000, salários fixos R$ 15.000, outros R$ 7.000).
- Margem de contribuição média por pizza (mix de canais): R$ 25,00.
- Ponto de equilíbrio = R$ 30.000 ÷ R$ 25,00 = **1.200 pizzas por mês** (cerca de 40 por dia).

Se o mix migrar para mais aplicativo, a margem média cai e o ponto de equilíbrio sobe. É por isso que o cálculo precisa ser refeito a cada mudança de canal.

**4. Mão de obra direta**

Mão de obra não entra no custo do insumo. Ela entra como custo fixo ou semi-fixo, rateado pelo volume. Se a equipe é fixa, aumentar o volume diminui o custo por pizza; se é por hora, o custo acompanha a demanda.
