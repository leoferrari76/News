---
tags:
  - pd-research
  - product-design
  - curadoria
data: 2026-05-29
---

# PD Research — 29 de maio de 2026

## Artigos encontrados

---

### 1. The Figma Design Agent is Here
**Fonte:** Figma Blog | **Link:** https://www.figma.com/blog/the-figma-agent-is-here/ | **Tema:** IA no Design / Tech + Produto

**A tese central:**
O Figma lançou um agente nativo (em beta desde 20 de maio) que vive dentro do arquivo, lê o design system do time e edita designs via linguagem natural — o maior shift no produto Figma desde a edição colaborativa em tempo real.

**Por que isso importa (ou não):**
O agente não gera output genérico: ele usa @mentions para componentes, tokens e variáveis existentes, o que significa que a qualidade do design system do cliente determina diretamente o que o agente consegue fazer. Para consultores, isso é oportunidade (acelerar execução em clientes com systems maduros) e argumento de venda (cliente sem design system perde o principal multiplicador da ferramenta). Durante o beta, sem custo de créditos — o momento certo para testar.

**Vale aprofundar?**
→ Sim — é um produto em beta que você pode testar agora. Impacto direto na velocidade de execução e nas conversas sobre design system com clientes.

---

### 2. Agents, Meet the Figma Canvas
**Fonte:** Figma Blog | **Link:** https://www.figma.com/blog/the-figma-canvas-is-now-open-to-agents/ | **Tema:** Tech + Produto / IA no Design

**A tese central:**
O Figma abriu o canvas para agentes externos via MCP — qualquer agente de IA (Claude, GPT, outros) pode agora ler e escrever em arquivos Figma, transformando o canvas em infraestrutura compartilhada entre designers e agentes.

**Por que isso importa (ou não):**
Este é o movimento estratégico por trás do artigo anterior: a Figma não está apenas lançando um agente próprio — está se tornando uma plataforma onde qualquer agente pode operar. A implicação mais imediata: fluxos automatizados (sincronização código ↔ design, revisão de consistency de design system por agente, geração de variações em escala) passam a ser possíveis com qualquer LLM. Para consultores, isso significa pensar em Figma não só como ferramenta de prototipagem, mas como ponto de integração de um ecossistema de agentes.

**Vale aprofundar?**
→ Sim — importante compreender o modelo MCP do Figma antes que se torne padrão de mercado e apareça como requisito em RFPs de clientes enterprise.

---

### 3. Agentic AI, Design Systems & Figma: A Practical Guide
**Fonte:** UX Collective | Christine Vallaure | **Link:** https://uxdesign.cc/agentic-ai-design-systems-figma-a-practical-guide-6ab0b681718d | **Tema:** Tech + Produto / IA no Design

**A tese central:**
Agentes de IA seguem design systems — não os inventam. Uma demo com Brad Frost (autor de Atomic Design) e Dominic Nguyen (co-fundador da Chromatic) mostra que tokens semânticos, naming consistente e estados completos de componentes determinam o que o agente consegue compor.

**Por que isso importa (ou não):**
Este artigo dá o "porquê técnico" dos dois artigos anteriores do Figma. O argumento central: agentes não são criativos no sentido de design — são compositores de sistemas existentes. O prompt "Adicione um componente de reviews de clientes" faz o agente encontrar componentes Star, Typography e Avatar, entender suas propriedades e compor algo novo — se os fundamentos existirem. Christine conecta isso ao Figma Slots (open beta desde março 2026), que habilita troca de elementos dentro de componentes sem detach. Infraestrutura crítica para o agente funcionar bem.

**Vale aprofundar?**
→ Sim — se você vai trabalhar com o Figma Agent em qualquer projeto, este artigo entrega os fundamentos que tornam o agente útil vs. frustrante.

---

### 4. Practical Interface Patterns For AI Transparency (Part 2)
**Fonte:** Smashing Magazine | Victor Yocco, PhD (UX Researcher, ServiceNow) | **Link:** https://www.smashingmagazine.com/2026/05/practical-interface-patterns-ai-transparency/ | **Tema:** IA no Design

**A tese central:**
Spinners falham em experiências de agentes de IA — o "Dynamic Checklist" pattern, que revela cada etapa planejada do agente em tempo real, transforma tempo de espera em tempo de confiança.

**Por que isso importa (ou não):**
Artigo de 13 de maio 2026, parte 2 de uma série. O problema é real: quando um agente está "pensando", usuários não sabem se ele está trabalhando ou travado — e um spinner genérico não resolve. O Dynamic Checklist lista cada etapa planejada antes de executar, marca a atual como "em progresso" e anteriores como "concluídas". É um pattern que entra direto numa sprint. O autor está escrevendo um livro sobre designing agentic AI, então a profundidade técnica é sólida. A Parte 1 (abril 2026, URL: smashingmagazine.com/2026/04/identifying-necessary-transparency-moments-agentic-ai-part1/) mapeia *quando* mostrar transparência; a Parte 2 mostra *como*.

**Vale aprofundar?**
→ Sim — leitura obrigatória para quem está desenhando qualquer produto com features de agentes. Pattern concreto, aplicável imediatamente.

---

### 5. Ten Data-Backed Truths Of User Experience ROI
**Fonte:** Smashing Magazine | Carrie Webster | **Link:** https://www.smashingmagazine.com/2026/05/data-backed-truths-user-experience-roi/ | **Tema:** Product Design

**A tese central:**
10 dados que ligam UX diretamente a receita, retenção e crescimento — de page load time a espaço em branco a custo de corrigir erro no momento errado.

**Por que isso importa (ou não):**
Artigo de 15 de maio 2026. Para consultores que precisam justificar investimento em design com números, este artigo entrega munição em formato citável. Os dados mais impactantes: 47% dos usuários esperam carregamento em ≤2s; 1s de delay = -20% conversões; corrigir um erro após o lançamento custa até 100x mais do que durante prototipagem; mais espaço em branco num dashboard fintech levou a -25% de time-on-task e aumento de conversão. Nada aqui é novo no fundo, mas ter os dados compilados e citáveis num único artigo é muito prático para apresentações.

**Vale aprofundar?**
→ Depende — leitura rápida suficiente. Os dados são para usar em conversas com clientes e stakeholders, não para estudo aprofundado.

---

### 6. How I Designed & Implemented Evals for Product Talk's Interview Coach
**Fonte:** Product Talk (Teresa Torres) | **Link:** https://www.producttalk.org/interview-coach-evals/ | **Tema:** IA no Design / Product Design

**A tese central:**
AI evals são uma prática obrigatória de discovery — Teresa Torres gastou mais tempo construindo o sistema de avaliação do que o produto em si, e sem evals não é possível garantir a qualidade do output de IA.

**Por que isso importa (ou não):**
Teresa Torres construiu o Interview Coach (produto de IA da Product Talk) e documentou o design e implementação de evals em detalhe. O dado mais importante: se ela fosse reescrever *Continuous Discovery Habits* hoje, adicionaria um capítulo sobre evals. A distinção entre "golden dataset", "code-based checks" e "LLM-as-judge" é um vocabulário que qualquer PD trabalhando com produtos de IA precisa ter. Para consultores: o cliente que não tem sistema de evals não tem garantia de qualidade no produto de IA — essa é uma lacuna de design, não só de engenharia. Coloca o PD como responsável por um novo tipo de entregável.

**Vale aprofundar?**
→ Sim — leitura de referência. Teresa é a voz mais confiável em product discovery e este é seu learning mais aplicável ao contexto de IA em 2026.

---

### 7. Product in the Age of AI: Designers on How Their Role Is Changing
**Fonte:** UX + AI (ileanamarcut.substack.com) | Ileana Marcut | **Link:** https://ileanamarcut.substack.com/p/designer-role-2026 | **Tema:** IA no Design / Product Design

🆕 **Nova fonte descoberta** — *UX + AI* (ileanamarcut.substack.com) é um Substack produzido por Ileana Marcut, Designer e Product Strategist baseada em Berlim. Foco na interseção prática de UX, IA e estratégia de produto.

**A tese central:**
4 product designers compartilham como a IA está mudando concretamente seu trabalho em 2026 — o consenso é que o trabalho upstream (definir o problema, enquadrar a oportunidade) está se tornando o principal entregável.

**Por que isso importa (ou não):**
Artigo publicado em 3 de abril de 2026. Diferente dos artigos de tendência com dados de survey, este é qualitativo e específico — 4 designers reais, contextos reais. O padrão mais citado: a execução está sendo absorvida pela IA, e o que permanece como valor humano é o julgamento sobre o que vale construir e por quê. Para um PD Sênior em consultoria, isso é validação de campo de um repositório estratégico que está se tornando mais valioso, não menos.

**Vale aprofundar?**
→ Sim — leitura rápida com alta densidade de insight prático. Vale assinar o Substack.

---

### 8. Are We Doing UX for AI the Right Way?
**Fonte:** UX Collective | Katya Korovkina | **Link:** https://uxdesign.cc/are-we-doing-ux-for-ai-the-right-way-aea01e14138e | **Tema:** IA no Design

**A tese central:**
"Chatbot-first thinking" é um equívoco generalizado — quase metade da população em países ricos tem dificuldade com textos complexos e não vai obter bons resultados de chatbots, criando falhas de usabilidade disfarçadas de limitação do usuário.

**Por que isso importa (ou não):**
Publicado em 27 de janeiro de 2026, mas a tese ficou mais urgente à medida que o mercado empurrou interfaces de chat como padrão para "produto de IA". O dado de alfabetização funcional é perturbador: se ~46% dos adultos lêem no nível fundamental, um produto que requer prompt engineering intermediário já excluiu quase metade dos potenciais usuários. Para consultores desenhando produtos de IA para contextos não-tech (saúde, financeiro, varejo), esta perspectiva de accessibility/inclusion raramente entra nas conversas de produto — mas aparece como problema de adoção mais tarde.

**Vale aprofundar?**
→ Sim — especialmente para quem está desenhando produtos de IA para contextos com usuários não-tech. Argumento importante e consistentemente subvalorizado nas conversas de produto.

---

### 9. A Practical Guide To Design Principles
**Fonte:** Smashing Magazine | **Link:** https://www.smashingmagazine.com/2026/04/practical-guide-design-principles/ | **Tema:** Product Design

**A tese central:**
Criar design principles é apenas uma fração pequena do trabalho — o trabalho real é embuti-los nas decisões do dia a dia sem que virem decoração de parede ou fiquem em documentos que ninguém lê.

**Por que isso importa (ou não):**
Artigo de 1 de abril de 2026. No contexto de IA em que times tomam mais decisões mais rápido (incluindo agentes que tomam decisões automatizadas), design principles passam de "bom ter" para infraestrutura crítica. O artigo propõe que bons principles definem tanto o que o time faz quanto o que explicitamente *não* faz — e essa distinção negativa é especialmente útil para consultores que precisam criar guardrails sem exercer autoridade formal. Útil também como framework para definir os "princípios de design de agentes" que determinam como um produto de IA deve se comportar.

**Vale aprofundar?**
→ Depende — muito aplicável se você está trabalhando na definição de principles com algum cliente ou time. Menos urgente se isso não é uma necessidade atual.

---

## 🔍 Deep Dive: Figma Vira Plataforma de IA — O Canvas Como Infraestrutura

*Fontes cruzadas: Figma Blog (The Figma Agent Is Here, mai/26), Figma Blog (Agents Meet Canvas, mar/26), UX Collective — Christine Vallaure (Agentic AI + Design Systems, mar/26), TechCrunch (mai/26), Fast Company (mai/26)*

---

### O que as fontes dizem juntas

As fontes documentam dois movimentos simultâneos e complementares da Figma em 2026:

1. **Figma como ferramenta → Figma com agente interno** (maio 2026): Um agente que vive dentro do arquivo, lê o design system existente e executa edições via linguagem natural. O designer dirige; o agente executa.

2. **Figma como plataforma → Canvas aberto a agentes externos** (março 2026): Via MCP, qualquer agente de IA pode operar dentro de um arquivo Figma. O canvas se torna infraestrutura compartilhada.

O resultado combinado é que o canvas do Figma migra de "arquivo onde designers trabalham" para "sistema operacional do design de produto" — a camada onde o conhecimento de design encontra a execução automatizada.

---

### O que o campo está descobrindo além dos artigos

A Figma reportou receita 46% acima do ano anterior na semana do lançamento do agente. 60% dos arquivos Figma criados no último ano foram criados por não-designers — o canvas já deixou de ser território exclusivo de designers muito antes do agente. Com o agente, essa tendência acelera: o não-designer que antes precisava de um designer para executar agora tem um agente que interpreta intenção e produz output baseado no design system existente.

A dimensão mais importante que ainda não virou artigo: design systems de baixa qualidade vão se tornar visíveis de forma constrangedora. Um agente produz lixo se o sistema é inconsistente. Isso vai ser testado na prática por todos os times que adotarem o agent nos próximos meses.

---

### As tensões que ninguém resolve

**Tensão 1: Velocidade de adoção vs. Maturidade de design system**
O Figma Agent funciona melhor quando o design system é maduro (tokens semânticos, naming consistente, estados completos de componentes). A maioria dos times tem sistemas imaturos. A adoção vai gerar mais frustração do que magia para a maioria dos usuários nos primeiros meses. Nenhum dos artigos discute qual é o piso mínimo de maturidade necessário para o agente ser útil — e esse silêncio vai aparecer como problema de adoção.

**Tensão 2: Colaboração designer-agente vs. Accountability**
Quando um agente edita o arquivo e o resultado está errado, quem é responsável? O designer que definiu mal o sistema? O agente que interpretou mal o prompt? A Figma, pelos limites do agente? Para consultores em projetos com clientes, essa questão de accountability vai aparecer antes do mercado estar preparado para respondê-la.

---

### Minha posição

O movimento da Figma está sendo mal lido. A maioria das reações focou em "agora você cria telas mais rápido". O movimento real é outro: a Figma está se posicionando como o sistema operacional do design de produto — a camada onde o conhecimento de design (systems, tokens, componentes) encontra a execução por agentes. Isso é estruturalmente muito maior do que uma feature de geração.

Para consultores, a implicação estratégica mais urgente: audit de design system passa de "entrega opcional" para "pré-requisito de competitividade com agentes". Quem chegar num cliente com esse argumento antes do cliente descobrir na prática — ao ver o agente gerando outputs inconsistentes — tem uma vantagem de posicionamento clara.

---

### Perguntas para o Leonardo

1. **O design system dos seus clientes atuais está maduro o suficiente para o Figma Agent ser útil?** Tokens semânticos, naming consistente, estados completos de componentes — onde cada cliente está nisso? A resposta determina o time-to-value do agente para cada projeto.

2. **Como você vai posicionar um audit de design system para clientes que ainda não veem isso como prioridade?** Com o Figma Agent disponível, há um argumento de negócio direto: sistema maduro = execution acelerada por agente; sistema imaturo = execução manual + agente frustrante. Essa conversa ficou mais fácil de ter hoje.

3. **Você já testou o Figma Agent em beta?** Está disponível para Professional/Organization/Enterprise sem custo de créditos durante o beta. O melhor momento para aprender capacidades e limitações reais é agora — antes do GA quando o cliente vai perguntar o que você acha.
