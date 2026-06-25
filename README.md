# 📊 Case: Customer Feedback: Análise das Avaliações Negativas de um Sistema ERP

Atividade acadêmica desenvolvida como parte da pós-graduação em **Data Analytics e AI for Business** pela FNAT (Fundação de Negócios, Analytics e Tecnologia), 2026.

---

## Contexto

A **GenSoft** é uma empresa brasileira de tecnologia especializada em sistemas ERP no modelo SaaS, com mais de 20 mil clientes ativos. Com o crescimento acelerado da base, a empresa passou a registrar um aumento significativo de feedbacks negativos em canais públicos.

O desafio proposto foi investigar os dados internos da empresa para responder duas perguntas estratégicas:

- Qual público mais tende a avaliar negativamente o sistema?
- Quais são as principais características desse público e o que a empresa deveria observar?

---

## Fontes de Dados

Os dados utilizados são fictícios e foram fornecidos exclusivamente para fins acadêmicos. As bases contemplam:

| Arquivo | Conteúdo |
|---|---|
| Consumidores.xlsx | Perfil dos usuários, avaliações e comentários |
| Tickets de Suporte.xlsx | Histórico de chamados com data de criação, finalização e duração |
| Dispositivo.xlsx | Tipo de dispositivo utilizado por cada cliente |
| Planos.xlsx | Tipos de plano contratado |
| Geografia.xlsx | País e continente de cada cliente |
| Empresa.xlsx | Porte das empresas clientes |
| Cargos.xlsx | Cargo dos usuários dentro de suas empresas |

---

## Ferramentas Utilizadas

- **Power BI**: modelagem dos dados e análise via gráfico de Principais Influenciadores (Augmented Analytics)
- **Análise de Sentimentos via LLM**: interpretação qualitativa dos comentários dos usuários

---

## Principais Insights

### 1. Qual público mais tende a avaliar negativamente?

O perfil com maior concentração de avaliações negativas é o usuário com **cargo de Consumidor**, representando quase **32% das avaliações baixas** de toda a base. Dentro desse grupo, a maior parte das reclamações está concentrada nos clientes do **Plano Premier**, ou seja, os clientes que mais pagam pelo serviço são os que mais demonstram insatisfação, um risco crítico para retenção e imagem da empresa.

### 2. Quais são as principais características desse público?

**Tempo de atendimento do suporte**
O fator com maior impacto direto nas avaliações negativas. Tickets com maior duração de resolução apresentam margem expressivamente maior de avaliações baixas. Apenas melhorando o tempo de resposta e resolução dos chamados, a empresa já reduziria de forma significativa essa taxa de insatisfação.

**Volume de tickets abertos**
Quanto mais tickets um cliente abre, maior a chance de avaliar negativamente. O padrão reforça a hipótese do suporte: o cliente abre um chamado, não tem o problema resolvido a tempo, abre outro, acumula frustrações e avalia mal.

**Porte da empresa**
Empresas com menos de 5.000 funcionários concentram uma quantidade maior de reclamações. Possivelmente por terem menos recursos internos de TI, esses clientes dependem mais do suporte da GenSoft e sentem mais o impacto quando ele falha.

**Análise de sentimentos nos comentários**
A maioria das reclamações está relacionada a usabilidade, processos internos, segurança e comparações com outros ERPs do mercado. Há um padrão perceptível de clientes do Plano Premier que sentem que o plano não entrega valor proporcional ao preço pago, como se as funcionalidades não justificassem o custo em relação aos planos mais simples.

---

## Recomendações

- Investigar e reduzir o SLA de atendimento do suporte, especialmente para clientes Premier
- Revisar o pacote de funcionalidades do Plano Premier e avaliar se existe diferenciação real e percebida em relação aos demais planos
- Criar estratégias de onboarding e suporte dedicado para empresas de menor porte
- Monitorar continuamente o volume de tickets por cliente como indicador antecipado de churn

---

## Arquivos do Repositório

```
case-customer-feedback-erp/
├── README.md                          # Este arquivo
├── Customer_Feedback.pdf              # Documento original do case (FNAT)
├── Customer_Feedback_Respostas.pdf    # Respostas e análise desenvolvidas
└── Customer_Feedback.pbix             # Dashboard Power BI com a análise completa
```

---

## Sobre

Análise desenvolvida de forma independente com base no enunciado proposto pela FNAT. Os dados são fictícios e utilizados exclusivamente para fins acadêmicos e de portfólio.
