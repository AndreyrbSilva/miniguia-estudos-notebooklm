# Caderno Tematico: Educacao Financeira Pessoal

Projeto desenvolvido como parte do Bootcamp DIO + Accenture — desafio de uso do NotebookLM como ferramenta de aprendizagem ativa com IA.

---

## Contexto e Objetivos

**Tema escolhido:** Educacao Financeira Pessoal, com foco em orcamento domestico, controle de gastos e reserva de emergencia.

O tema foi escolhido por ser diretamente relevante para jovens que estao entrando no mercado de trabalho e precisam desenvolver habitos financeiros saudaveis desde o inicio da vida profissional.

**Objetivos de estudo:**

1. Entender como organizar um orcamento pessoal usando metodos praticos.
2. Compreender o que e e como calcular uma reserva de emergencia adequada.
3. Aprender a diferenciar gastos fixos, variaveis e investimentos.
4. Identificar os principais erros financeiros de jovens adultos e como evita-los.
5. Explorar o NotebookLM como ferramenta de estudo ativo, testando diferentes estrategias de prompt.

---

## Curadoria de Fontes

As fontes abaixo foram selecionadas por serem abertas, confiaveis e diretamente relacionadas ao tema. Todas foram adicionadas ao caderno no NotebookLM.

| # | Fonte | Link |
|---|-------|------|
| 1 | Banco Central do Brasil — Caderno de Educacao Financeira: Gestao de Financas Pessoais | [bcb.gov.br](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf) |
| 2 | CVM — O Mercado de Valores Mobiliarios Brasileiro | [investidor.gov.br](https://www.investidor.gov.br/menu/investidor_estrangeiro/o_mercado_de_valores_mobiliarios_brasileiro/sistema-financeiro-nacional.html) |
| 3 | Serasa Ensina — Educacao Financeira | [serasa.com.br/ensina](https://www.serasa.com.br/ensina/dicas/educacao-financeira/) |
| 4 | Tesouro Nacional — Blog de Educacao Financeira | [tesourodireto.com.br](https://www.tesourodireto.com.br/blog/educacao-financeira.htm) |

---

## Engenharia de Prompts e "Cicatrizes"

### Prompt 1 — Conceito de Orcamento Pessoal

**Versao inicial (vaga):**
> "O que e orcamento pessoal?"

**Problema:** A resposta foi generica e nao citou as fontes do caderno.

**Versao refinada:**
> "Com base nas fontes do caderno, explique o conceito de orcamento pessoal e quais metodos praticos de controle financeiro sao recomendados para quem esta comecando?"

**Resposta obtida:**

O orcamento pessoal e definido nas fontes como uma ferramenta de planejamento financeiro essencial para a realizacao de sonhos e projetos. Ele consiste no registro e na organizacao de toda a movimentacao financeira, englobando receitas, despesas e investimentos. Um principio fundamental e que as despesas nunca devem superar as receitas, buscando-se sempre um orcamento superavitario para possibilitar a formacao de poupanca.

Para quem esta comecando, as fontes recomendam um metodo estruturado em quatro etapas:

1. **Planejamento:** Estimar receitas e despesas de um periodo futuro com base na rotina passada, diferenciando itens fixos de variaveis.
2. **Registro:** Anotar diariamente todas as entradas e saidas, usando papel, aplicativos ou planilhas.
3. **Agrupamento:** Reunir gastos em categorias (alimentacao, transporte, lazer) para entender onde o dinheiro esta sendo aplicado.
4. **Avaliacao:** Refletir sobre o balanco do mes e ajustar comportamentos.

Alem do metodo, as fontes destacam: pagar-se primeiro, diferenciar necessidade de desejo, envolver a familia no planejamento e entender o custo do credito.

**Aprendizado:** Prompts vagos geram respostas genericas. Especificar "com base nas fontes" e delimitar o publico-alvo melhora muito a qualidade da resposta.

---

### Prompt 2 — Reserva de Emergencia

**Versao inicial (vaga):**
> "O que e reserva de emergencia?"

**Problema:** Resposta correta, mas rasa. Nao trouxe o calculo nem orientacoes sobre onde guardar o dinheiro.

**Versao refinada:**
> "Como calcular o valor ideal de uma reserva de emergencia para um trabalhador com renda de R$ 2.000/mes? Quais sao as opcoes mais indicadas de onde guardar esse dinheiro com liquidez e seguranca? Use as fontes disponiveis no caderno."

**Resposta obtida:**

As fontes nao determinam um numero fixo de meses, mas fornecem o metodo: mapear as despesas essenciais mensais, considerar os riscos (saude, perda de renda) e incluir gastos sazonais como IPTU e IPVA no calculo.

Para guardar a reserva, as fontes recomendam opcoes com alta liquidez e baixo risco:

- **Caderneta de Poupanca:** alta liquidez e seguranca, indicada para iniciantes.
- **Tesouro Direto:** considerado um dos investimentos de menor risco do mercado.
- **CDB:** protegido pelo FGC ate R$ 250.000, opcao solida para perfil conservador.
- **Fundos de Curto Prazo:** compativeis com perfil conservador pela previsibilidade.

Importante: verificar se a instituicao e autorizada pelo Banco Central e se o investimento tem registro na CVM. A reserva nao deve ser usada para consumo, apenas para situacoes inesperadas.

**Aprendizado:** Incluir um caso concreto forcou a IA a aplicar os conceitos na pratica, tornando a resposta muito mais util.

---

### Prompt 3 — Tipos de Gastos e Investimentos

**Prompt usado:**
> "Qual a diferenca entre gasto fixo, gasto variavel e investimento? De exemplos praticos do cotidiano de um jovem adulto."

**Resposta obtida:**

- **Gastos Fixos:** Despesas que nao variam de um mes para o outro. Exemplos: aluguel, financiamento, mensalidade escolar.
- **Gastos Variaveis:** Valores que mudam conforme o consumo ou a ocasiao. Exemplos: conta de luz, alimentacao, transporte, lazer.
- **Investimentos:** Aplicacao dos recursos poupados com expectativa de retorno futuro. Diferente da poupanca (ato de nao gastar), o investimento e o destino dado ao dinheiro para que ele renda. Exemplos: Tesouro Direto, CDB, acoes.

O modelo destacou a aplicacao pratica: planejar fixos e variaveis, registrar gastos variaveis diariamente e, com o orcamento superavitario, destinar parte da renda para investimentos antes de iniciar os gastos do mes.

---

### Prompt 4 — Erros Financeiros de Jovens Adultos

**Prompt usado:**
> "Quais sao os erros financeiros mais comuns cometidos por jovens adultos e como evita-los? Base a resposta nas fontes disponiveis."

**Resposta obtida:**

1. **Ausencia de registro e planejamento:** Nao anotar despesas faz o dinheiro "sumir" sem explicacao. Solucao: adotar o metodo das 4 etapas.
2. **Confundir desejo com necessidade:** Tratar desejos como necessidades leva a compras por impulso. Solucao: consumo consciente.
3. **Uso inadequado do credito:** Avaliar apenas se a parcela "cabe no bolso", ignorando o CET e os juros compostos. Solucao: usar credito so para emergencias e comparar o CET entre instituicoes.
4. **Busca pelo prazer imediato:** Preferir consumir agora e pagar juros depois. Solucao: entender a troca intertemporal e preferir a posicao de credor.
5. **Procrastinacao da poupanca:** Poupar so o que sobra no fim do mes. Solucao: pagar-se primeiro.
6. **Ignorar custos sazonais:** Nao prever IPTU, IPVA e matriculas causa desequilibrio. Solucao: incluir esses itens no planejamento.

---

### Prompt 5 — Resumo Estruturado Geral

**Prompt usado:**
> "Gere um resumo estruturado com os principais conceitos de educacao financeira pessoal abordados nas fontes do caderno, organizado por topicos, em linguagem simples e direta."

**Resposta obtida:**

1. **Relacao com o Dinheiro:** Diferenca entre sonho e projeto, necessidade vs. desejo, e troca intertemporal.
2. **Orcamento Pessoal:** Ferramenta de planejamento com regra de ouro (receitas maiores que despesas), metodo das 4 etapas e estrategia de pagar-se primeiro.
3. **Credito e Dividas:** CET como indicador do custo real. Para sair das dividas: mapear, nao contrair novas, renegociar e cortar superfluos.
4. **Consumo Planejado:** Consumo consciente e identificacao de tecnicas de marketing para evitar compras por impulso.
5. **Investimentos e Prevencao:** Tripe do investimento (liquidez, risco, rentabilidade), perfis de investidor e importancia de planejar a aposentadoria cedo.

**Aprendizado:** Pedir "linguagem simples e direta" evita respostas formais demais. Foi o prompt mais eficiente para consolidar o aprendizado.

---

## Miniguia de Estudo

### Resumos Estruturados

**Orcamento Pessoal**

Orcamento pessoal e o planejamento das receitas e despesas em um periodo. O objetivo e manter um orcamento superavitario para viabilizar a poupanca. O metodo recomendado tem 4 etapas: planejamento, registro diario, agrupamento por categorias e avaliacao mensal. A estrategia central e pagar-se primeiro: separar a poupanca assim que receber a renda, antes de qualquer gasto.

**Reserva de Emergencia**

E um valor guardado exclusivamente para imprevistos. Nao e investimento, e protecao. O valor ideal cobre entre 3 e 6 meses de despesas essenciais. Deve ficar em aplicacoes com liquidez diaria: Tesouro Selic, CDB com liquidez diaria ou poupanca. Nao deve ser usada para consumo planejado.

**Tipos de Gastos e Investimentos**

| Tipo | Definicao | Exemplos |
|------|-----------|---------|
| Fixo | Valor constante todo mes | Aluguel, financiamento, mensalidade |
| Variavel | Valor que muda conforme o consumo | Alimentacao, lazer, conta de luz |
| Investimento | Dinheiro aplicado para gerar retorno | Tesouro Direto, CDB, acoes |

**Credito e Dividas**

Credito e o acesso a dinheiro de terceiros com custo (juros). O CET mostra o custo real de um emprestimo e deve ser comparado entre instituicoes. Para sair das dividas: mapear todas com seus juros, nao contrair novas, renegociar prazos e cortar gastos superfluos.

**Erros Mais Comuns**

Nao registrar gastos, confundir desejo com necessidade, usar credito sem avaliar o CET, buscar prazer imediato ignorando os juros, procrastinar a poupanca e nao prever custos sazonais.

---

### Glossario de Conceitos

| Termo | Definicao |
|-------|-----------|
| Orcamento pessoal | Planejamento das receitas e despesas em um determinado periodo |
| Reserva de emergencia | Valor guardado para cobrir imprevistos sem comprometer o orcamento |
| Gasto fixo | Despesa com valor constante todo mes |
| Gasto variavel | Despesa cujo valor oscila conforme o uso ou escolha do consumidor |
| Orcamento superavitario | Situacao em que as receitas superam as despesas |
| Pague-se primeiro | Estrategia de separar a poupanca assim que recebe a renda, antes dos gastos |
| Troca intertemporal | Escolha entre consumir agora pagando juros ou poupar para consumir mais no futuro |
| CET | Custo Efetivo Total — custo real de um emprestimo incluindo juros, tarifas e impostos |
| Liquidez | Facilidade de transformar um investimento em dinheiro disponivel rapidamente |
| Juros compostos | Juros que incidem sobre o capital inicial mais os juros ja acumulados |
| FGC | Fundo Garantidor de Credito — garante depositos ate R$ 250.000 por instituicao |
| Perfil do investidor | Classificacao em conservador, moderado ou arrojado conforme tolerancia ao risco |
| Consumo consciente | Habito de avaliar necessidade, impacto e custo antes de realizar uma compra |
| Score de credito | Pontuacao que mede a probabilidade de uma pessoa pagar suas dividas em dia |

---

### Prompts Reutilizaveis

```
1. "Com base nas fontes do caderno, explique [conceito] em linguagem simples e de 3 exemplos praticos para quem esta comecando."

2. "Qual a diferenca entre [conceito A] e [conceito B]? Use exemplos do cotidiano de um jovem adulto."

3. "Como calcular [meta financeira] para uma renda de R$ [valor]? Quais sao as opcoes mais indicadas considerando liquidez e seguranca?"

4. "Crie um plano de 3 meses para [objetivo financeiro] partindo do zero, com renda de R$ [valor] e gastos essenciais de R$ [valor]."

5. "Gere um resumo estruturado com os principais conceitos de [tema] abordados nas fontes, organizado por topicos, em linguagem simples e direta."

6. "Quais sao os erros mais comuns cometidos por [perfil] em relacao a [tema] e como evita-los? Base a resposta nas fontes disponiveis."

7. "Explique o conceito de [termo financeiro] com um exemplo numerico simples, mostrando o impacto negativo (divida) e positivo (investimento)."

8. "Com base no material estudado, crie 5 perguntas de revisao sobre [tema] com gabarito comentado."
```

---

## Repositorio

Projeto desenvolvido por [Andrey Rodrigo](https://github.com/AndreyrbSilva) como parte do Bootcamp DIO + Accenture.
