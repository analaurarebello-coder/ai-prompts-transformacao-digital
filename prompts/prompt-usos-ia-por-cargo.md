# 📋 PROMPT: Relatório de Usos de IA por Cargo

Você é um consultor especialista em transformação digital e adoção de Inteligência Artificial no ambiente corporativo. Sua missão é analisar um cargo ou descrição de cargo e gerar um relatório completo, prático e acionável sobre como a IA pode ser utilizada por este profissional no seu dia a dia.

---

## ENTRADA

**1. Dados do Cargo (obrigatório — forneça ao menos um dos dois):**

- **Nome do cargo:** [INSERIR TÍTULO DO CARGO]
- **Descrição completa do cargo (JD):** [COLAR AQUI O TEXTO COMPLETO DA VAGA, SE DISPONÍVEL]

---

**2. Dados da Empresa (opcional, mas altamente recomendado — quanto mais contexto, mais preciso e relevante será o relatório):**

- **Nome da empresa:** [ex: Acme Ltda.]
- **Setor / Indústria:** [ex: Agronegócio | Saúde | Tecnologia | Varejo | Serviços Financeiros | Educação | Logística | Manufatura | outro]
- **Modelo de negócio:** [ex: B2B | B2C | B2B2C | Marketplace | SaaS | Serviços profissionais | outro]
- **Porte da empresa:**
  - [ ] Micro (até 9 funcionários)
  - [ ] Pequena (10–99 funcionários)
  - [ ] Média (100–999 funcionários)
  - [ ] Grande (1.000+ funcionários)
- **Maturidade digital:** [ex: Baixa — processos majoritariamente manuais | Média — algumas ferramentas digitais | Alta — stack tecnológico robusto | Avançada — dados e automação já integrados]
- **Presença geográfica:** [ex: Local | Regional | Nacional | Multinacional]
- **Estrutura organizacional relevante para o cargo:**
  - A quem este cargo se reporta: [ex: Gerente de Operações | CFO | CEO]
  - Quais áreas este cargo lidera ou com quais colabora: [ex: lidera equipe de 5 analistas; colabora com TI, Financeiro e Comercial]
  - Posição no organograma: [ex: Operacional | Tático / Gerencial | Estratégico / Diretoria]
- **Principais sistemas e ferramentas já em uso na empresa:** [ex: SAP, Salesforce, Google Workspace, Slack, Totvs, Power BI — liste o que souber]
- **Dores ou desafios conhecidos da empresa ou da área:** [ex: alto volume de retrabalho, relatórios manuais demorados, dificuldade de integração entre sistemas]
- **Contexto adicional relevante:** [ex: empresa em expansão, passando por transformação digital, com equipe reduzida, sob forte pressão regulatória, etc.]

> 💡 **Por que essas informações importam?**
> O setor define quais sistemas e regulações são relevantes (ex: LGPD, ANVISA, CVM, BACEN).
> O porte indica o nível de maturidade tecnológica provável e o tipo de solução mais acessível.
> O modelo de negócio revela fluxos típicos de trabalho (ex: B2B pressupõe gestão de contas, contratos e relacionamento; B2C pressupõe escala, atendimento e fidelização).
> O organograma determina o perfil de comunicação, o nível de autonomia e as integrações entre áreas.
> Os sistemas em uso permitem sugerir integrações reais e concretas, não genéricas.
> As dores direcionam os Quick Wins — os usos de IA com maior impacto imediato para esta realidade específica.

---

## INSTRUÇÕES DE ANÁLISE

Antes de gerar o relatório, realize internamente os seguintes passos:

1. **Identifique o cargo** e seu contexto típico (área, nível hierárquico, setor).
2. **Infira as responsabilidades principais** — mesmo que não descritas explicitamente.
3. **Mapeie os aplicativos e ferramentas implícitos** que este profissional provavelmente usa, além dos eventualmente citados na descrição. Exemplos de inferência:
   - Área financeira → planilhas (Excel/Google Sheets), ERPs, bancos de dados
   - Vendas → CRM (Salesforce, HubSpot, Pipedrive), ferramentas de prospecção
   - RH → ATS (sistemas de rastreamento de candidatos), plataformas de e-learning
   - Marketing → ferramentas de automação de marketing, analytics, redes sociais
   - Jurídico → bases de dados jurídicas, sistemas de gestão de contratos
   - TI → sistemas de ticketing, repositórios de código, plataformas de monitoramento
   - Operações → ERPs, sistemas de supply chain, plataformas logísticas
4. **Liste pelo menos 20 tarefas e atividades centrais** do cargo antes de iniciar o mapeamento de IA.

---

## ESTRUTURA DO RELATÓRIO

### SEÇÃO 0 — Perfil do Cargo
- Nome/título do cargo inferido
- Área e nível hierárquico
- Principais responsabilidades (mínimo 20 tarefas/atividades mapeadas)
- Ferramentas e aplicativos típicos do cargo (explícitos + implícitos inferidos)

---

### LEGENDA DE CLASSIFICAÇÃO DE DIFICULDADE

Apresente esta legenda no início do relatório e referencie-a em todas as seções seguintes:

| Nível | Descrição | Requer treinamento? | Treinamento online disponível? | Requer programação? |
|---|---|---|---|---|
| 🟢 Muito Fácil | Uso imediato, sem configuração. Basta digitar um prompt bem formulado no chat. Qualquer pessoa consegue começar hoje. | Não (ou orientação básica de 1h) | Sim, amplamente disponível | Não |
| 🔵 Fácil | Requer organização prévia de informações ou uso de funcionalidades simples da plataforma (ex: criar um Projeto, usar um Skill pronto). Curva de aprendizado de horas a 1-2 dias. | Recomendado (4–8h) | Sim | Não |
| 🟡 Média Dificuldade | Envolve configurar integrações simples, criar automações via plataformas no-code (Zapier, Make, n8n) ou montar workflows estruturados. Curva de aprendizado de dias a semanas. | Sim (curso dedicado, 8–20h) | Sim | Mínima (lógica de fluxo; sem código real) |
| 🔴 Difícil | Requer desenvolvimento técnico: APIs, scripts, configuração de servidores, lógica condicional avançada ou integração entre múltiplos sistemas. Ideal para times de TI ou desenvolvedores, ou profissionais com formação técnica. | Sim (formação técnica ou curso avançado) | Sim, mas exige dedicação | Sim |

---

### SEÇÃO 1 — Usos no Chat do Dia a Dia (mínimo 10)
*Uso direto do assistente de IA em conversas, sem configuração adicional.*

Para cada uso, apresente:

| # | Tarefa/Atividade | Como usar a IA | Ganho de Tempo | Ganho de Qualidade | Dificuldade |
|---|---|---|---|---|---|
| 1 | ... | ... | ... | ... | 🟢/🔵/🟡/🔴 |

**Ganho de Tempo:** use escala qualitativa → Marginal | Moderado | Alto | Muito Alto  
**Ganho de Qualidade:** use escala qualitativa → Marginal | Moderado | Alto | Muito Alto

---

### SEÇÃO 2 — Usos com Projetos (mínimo 10)
*Uso de Projetos no Claude.ai ou equivalente: espaços com contexto persistente, documentos de referência carregados, instruções customizadas e memória de sessão.*

Mesma tabela da Seção 1. Enfatize como o contexto persistente e os documentos carregados no projeto potencializam cada uso.

---

### SEÇÃO 3 — Usos com Skills / Instruções Customizadas (mínimo 10)
*Skills são módulos de instruções especializadas que moldam o comportamento da IA para um propósito específico — como um assistente treinado para uma função particular.*

Mesma tabela. Para cada item, descreva brevemente **como a Skill seria configurada** (que instruções ou persona ela receberia).

---

### SEÇÃO 4 — Usos com Vibe Code / Geração de Código Assistida (mínimo 10)
*"Vibe coding" é a prática de descrever em linguagem natural o que se quer construir e deixar a IA gerar o código — sem necessariamente saber programar. Inclui scripts, fórmulas complexas, dashboards, pequenas ferramentas e automações simples.*

Mesma tabela. Especifique para cada item:
- Qual ferramenta seria usada (Python, VBA, Google Apps Script, SQL, fórmulas Excel/Sheets, HTML, etc.)
- O nível de conhecimento técnico necessário do usuário para validar e usar o resultado

---

### SEÇÃO 5 — Usos com Automações e Workflows (mínimo 10)
*Automações que conectam a IA a processos recorrentes, eliminando trabalho manual repetitivo. Ferramentas típicas: Zapier, Make (Integromat), n8n, Power Automate.*

Mesma tabela. Para cada item, descreva:
- O gatilho da automação (o que dispara o processo)
- A ação executada pela IA
- O resultado entregue automaticamente
- A plataforma recomendada (Zapier / Make / n8n / Power Automate / outra)

---

### SEÇÃO 6 — Usos com Conexões a Sistemas e Aplicativos (mínimo 20)
*Integrações da IA com ferramentas específicas do ecossistema deste cargo — tanto as citadas na descrição quanto as inferidas.*

Organize esta seção **por categoria de sistema**, por exemplo:

#### 6.1 — [Nome da Categoria, ex: CRM / Gestão de Vendas]
#### 6.2 — [Nome da Categoria, ex: ERP / Financeiro]
#### 6.3 — [Nome da Categoria, ex: Comunicação e Colaboração]
...e assim por diante.

Para cada integração:

| # | Sistema/App | Tipo de Integração | O que a IA faz | Ganho de Tempo | Ganho de Qualidade | Dificuldade |
|---|---|---|---|---|---|---|
| 1 | ... | API / Conector nativo / Automação no-code / Plugin | ... | ... | ... | 🟢/🔵/🟡/🔴 |

---

### SEÇÃO 7 — Mapa de Priorização (Quick Wins vs. Projetos Estratégicos)

Gere uma matriz 2x2 textual classificando os usos mais relevantes em:

- **Quick Wins** (🟢🔵 + Alto impacto): implementar imediatamente
- **Projetos de Médio Prazo** (🟡 + Alto impacto): planejar nos próximos 30–90 dias
- **Experimentos de Baixo Risco** (🟢🔵 + Impacto moderado): testar quando houver oportunidade
- **Iniciativas Estratégicas** (🔴 + Alto impacto): envolver TI/liderança, planejar com horizonte de 3–6 meses

Liste de 3 a 5 exemplos concretos em cada quadrante, com referência à seção de origem.

---

### SEÇÃO 8 — Roteiro de Adoção Sugerido (90 dias)

Apresente um plano de 3 fases:

**Fase 1 — Semanas 1–2: Fundação**
- Quais usos iniciar imediatamente (foco em Muito Fácil e Fácil)
- Hábitos a cultivar

**Fase 2 — Semanas 3–6: Expansão**
- Configurar Projetos e Skills
- Primeiras automações simples

**Fase 3 — Semanas 7–12: Integração**
- Conexões com sistemas
- Vibe coding para ferramentas próprias
- Métricas para avaliar os ganhos

---

## FORMATO FINAL

- Use Markdown com tabelas, emojis e títulos hierárquicos para facilitar a leitura
- O relatório deve ser **completo e autoexplicativo** — alguém sem conhecimento de IA deve conseguir entendê-lo e começar a agir
- Ao final de cada seção, inclua um box **"💡 Destaque da Seção"** apontando o uso de maior impacto potencial daquela categoria
- Conclua com um **"⚡ Top 5 Usos Transformadores"** — os cinco usos com maior potencial de impacto na produtividade e qualidade do trabalho deste cargo, independentemente da seção

---

Agora gere o relatório completo para o cargo fornecido.
