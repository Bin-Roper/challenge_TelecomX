####Relatório de Análise Exploratória de Dados: Churn de Clientes na Telecom
X

**1. Introdução**

Este relatório apresenta as principais conclusões obtidas a partir da
Análise Exploratória de Dados (AED) realizada sobre o conjunto de dados
de clientes da Telecom X. O objetivo principal foi identificar os
fatores que mais influenciam a decisão dos clientes em cancelar seus
serviços (churn), fornecendo insights valiosos para a empresa direcionar
suas estratégias de retenção.

**2. Visão Geral do Churn**

A análise inicial revelou que a Telecom X enfrenta uma taxa de churn
considerável. Aproximadamente 26,58% dos clientes na base de dados
analisada cancelaram seus serviços. Este é um indicador chave que
destaca a urgência em implementar medidas de retenção.

**3. Principais Fatores Associados ao Churn**

A análise detalhada das características dos clientes e dos serviços
contratados permitiu identificar os seguintes fatores com maior impacto
no churn:

- Tipo de Contrato: Este é um dos fatores mais determinantes.

Clientes com contrato Mensal (Month-to-month) apresentam uma taxa de
churn significativamente mais alta em comparação com aqueles com
contratos de 1 ou 2 anos. Isso sugere que clientes com contratos mais
curtos possuem menor barreira para o cancelamento.

- Tempo de Contrato (Tenure): A longevidade do cliente na empresa é
  crucial.

Clientes com baixo tempo de contrato (novos clientes) são muito mais
propensos a cancelar. A taxa de churn tende a diminuir consideravelmente
à medida que o tenure aumenta, indicando que a fidelização ocorre ao
longo do tempo.

- Cobranças Mensais (MonthlyCharges): O valor pago mensalmente
  influencia a decisão de churn.

Observou-se uma tendência de maior churn entre clientes com cobranças
mensais mais elevadas. Isso pode indicar uma sensibilidade ao preço ou
que os pacotes mais caros podem não estar entregando o valor percebido
pelos clientes.

- Serviços Adicionais de Suporte e Segurança: A ausência de certos
  serviços adicionais está fortemente correlacionada ao churn.

Clientes que NÃO possuem OnlineSecurity (Segurança Online) e TechSupport
(Suporte Técnico) apresentam taxas de cancelamento notavelmente mais
altas. Estes serviços parecem ser importantes para a satisfação e
segurança do cliente, impactando positivamente a retenção.

- Método de Pagamento: A forma como o cliente paga também se mostrou
  relevante.

O método de pagamento Electronic check (Cheque Eletrônico) está
associado a uma taxa de churn significativamente maior em comparação com
outros métodos como cartão de crédito (automático) ou débito em conta.
Isso pode estar relacionado a um processo de pagamento menos
conveniente, mais propenso a falhas ou a um perfil de cliente menos
comprometido com a continuidade do serviço.

- Clientes Idosos (SeniorCitizen):

Clientes identificados como SeniorCitizen (Idosos) demonstraram uma taxa
de churn superior à dos clientes não idosos. Este grupo pode ter
necessidades específicas ou maior sensibilidade a fatores como preço e
complexidade dos serviços.

- Serviços de Internet e Streaming:

O tipo de InternetService (DSL, Fibra Óptica) também mostrou variações
na taxa de churn, com clientes de Fibra Óptica, apesar de geralmente
terem MonthlyCharges mais altas, apresentando taxas de churn que
precisam ser analisadas em conjunto com outros fatores.

A adesão a serviços como StreamingTV e StreamingMovies também
influencia, mas de forma menos direta que os fatores acima. Clientes sem
esses serviços podem ter um engajamento menor com o ecossistema da
empresa.

**4. Correlações Observadas**

A análise de correlação entre as variáveis numéricas reforçou alguns dos
achados:

- tenure vs. Churn_numeric: Correlação negativa, indicando que quanto
  maior o tempo de contrato, menor a chance de churn.

- MonthlyCharges vs. Churn_numeric: Correlação positiva, indicando que
  quanto maior a cobrança mensal, maior a chance de churn.

- TotalCharges vs. tenure: Forte correlação positiva, o que é esperado,
  já que clientes mais antigos acumulam mais cobranças totais.

**5. Conclusões e Recomendações Preliminares**

A análise exploratória dos dados da Telecom X revela que o churn de
clientes é um fenômeno multifatorial, com destaque para o tipo de
contrato, tempo de permanência (tenure), valor das cobranças mensais e a
ausência de serviços chave como segurança online e suporte técnico.

Com base nestes achados, algumas recomendações preliminares podem ser
consideradas:

- Estratégias de Fidelização para Novos Clientes: Desenvolver programas
  de boas-vindas e acompanhamento intensificado nos primeiros meses de
  contrato para reduzir o churn inicial.

- Incentivo a Contratos de Longo Prazo: Criar ofertas mais atrativas
  para contratos de 1 ou 2 anos, destacando os benefícios de
  estabilidade e possíveis descontos.

- Revisão de Precificação e Pacotes: Analisar a estrutura de preços,
  especialmente para os pacotes com MonthlyCharges mais elevadas,
  garantindo que o valor percebido justifique o custo.

- Promoção de Serviços de Valor Agregado: Destacar e incentivar a adesão
  aos serviços de OnlineSecurity e TechSupport, possivelmente
  incluindo-os em pacotes promocionais ou oferecendo demonstrações
  gratuitas.

- Melhoria da Experiência com Pagamento Eletrônico: Investigar os
  motivos da alta taxa de churn associada ao pagamento via Electronic
  check e buscar alternativas mais convenientes ou seguras.

- Atenção Segmentada: Desenvolver abordagens específicas para segmentos
  com maior propensão ao churn, como clientes idosos.

**6. Próximos Passos**

Os insights gerados por esta AED servem como uma base sólida para as
próximas etapas do projeto:

- Engenharia de Atributos: Criação de novas variáveis a partir das
  existentes para melhorar o desempenho dos modelos.

- Modelagem Preditiva: Desenvolvimento de modelos de machine learning
  para prever quais clientes têm maior probabilidade de cancelar o
  serviço.

- Validação e Implementação: Teste e implementação das estratégias de
  retenção baseadas nos resultados do modelo.

Este relatório visa fornecer uma compreensão clara dos principais
fatores de churn e auxiliar na tomada de decisões estratégicas para a
Telecom X.
