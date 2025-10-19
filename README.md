# Sprint 8 – Análise de Negócios: Otimização de Marketing na Y.Afisha

## Descrição do Projeto

Neste projeto, meu objetivo foi aplicar os conhecimentos adquiridos na seção de Análise de Negócios para resolver um estudo de caso real. Recebi uma oferta de estágio no departamento analítico da **Y.Afisha** e minha primeira tarefa foi ajudar a empresa a **otimizar as despesas com marketing**, analisando dados de acessos, pedidos e custos de campanhas.

O foco principal foi:

- Entender como os usuários utilizam o produto.  
- Identificar quando eles começam a comprar.  
- Calcular quanto dinheiro cada cliente traz para a empresa (LTV).  
- Avaliar quando os investimentos em marketing se tornam rentáveis.  

---

## Dados Utilizados

### Logs de Acesso (`visits_log_us.csv`)

- **Uid** — identificador único do usuário.  
- **Device** — dispositivo usado pelo usuário.  
- **Start Ts** — data e hora de início da sessão.  
- **End Ts** — data e hora de término da sessão.  
- **Source Id** — origem do anúncio que trouxe o usuário.  

> Todas as datas estão no formato `YYYY-MM-DD`.

### Pedidos (`orders_log_us.csv`)

- **Uid** — identificador do usuário que realizou o pedido.  
- **Buy Ts** — data e hora da compra.  
- **Revenue** — receita obtida pela Y.Afisha com o pedido.  

### Custos de Marketing (`costs_us.csv`)

- **source_id** — identificador da origem do anúncio.  
- **dt** — data da despesa.  
- **costs** — custo das campanhas publicitárias neste dia.

---

## Passos do Projeto

### Passo 1: Preparação dos Dados
- Carreguei os dados em variáveis separadas (`visits`, `orders`, `costs`).  
- Ajustei os tipos de dados para análise e pré-processamento.  
- Certifiquei-me de que todas as colunas possuíam os tipos corretos e tratei possíveis inconsistências.

### Passo 2: Análise e Métricas

#### Produto
- Calculei quantas pessoas utilizaram o produto diariamente, semanalmente e mensalmente.  
- Analisei o número de sessões por dia e a duração de cada sessão.  
- Observei a frequência de retorno dos usuários.

#### Vendas
- Analisei o período entre o registro e a primeira compra (conversão por coorte).  
- Calculei a quantidade de pedidos por cliente ao longo do tempo.  
- Estimei o valor médio de cada pedido e o **LTV** de cada cliente.

#### Marketing
- Calculei os gastos totais e por origem de anúncio.  
- Analisei o **Custo de Aquisição de Clientes (CAC)** por canal.  
- Avaliei o retorno sobre investimento (ROI) das campanhas.  
- Criei gráficos para visualizar as métricas por dispositivo, origem e ao longo do tempo.

### Passo 3: Conclusão e Recomendações
- Baseado nos dados analisados, recomendei **quais origens e plataformas** são mais eficientes para investimento.  
- Justifiquei minhas escolhas focando em métricas-chave como ROI, LTV, taxa de conversão e frequência de compra.  
- Apresentei decisões fundamentadas que podem otimizar a alocação do orçamento de marketing.

---

## Ferramentas e Formato

- Todo o projeto foi desenvolvido em **notebook Jupyter**.  
- O código de análise está em células de código (`code`) e as explicações em células de texto (`markdown`).  
- Organizei o notebook com títulos, seções e comentários claros para facilitar a leitura e a compreensão do trabalho.

---

## Critérios de Avaliação

Meu projeto foi avaliado com base em:

- Preparação e limpeza dos dados para análise.  
- Criação de gráficos explicativos para cada métrica analisada.  
- Interpretação clara dos gráficos e métricas.  
- Cálculo e interpretação correta de parâmetros como LTV, ROI e CAC.  
- Fundamentação das recomendações aos especialistas de marketing.  
- Organização do notebook e clareza do código.  
- Conclusões baseadas em dados e explicações detalhadas em cada passo.

---

## Conclusão

Com este projeto, consegui aplicar conceitos de **Análise de Negócios**, **Análise de KPIs** e **Tomada de Decisão baseada em dados**, consolidando minha capacidade de transformar dados brutos em recomendações estratégicas para otimização de marketing.

