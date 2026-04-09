# 🤖 Prompts de IA para Transformação Digital

> Prompts estruturados para gerar relatórios completos e acionáveis sobre adoção de Inteligência Artificial e outras tecnologias emergentes — por cargo, por empresa, por consolidado executivo e por business case.

*por Laura · 2025*

---

## 📁 O que tem neste repositório

Este repositório contém quatro prompts complementares de engenharia de IA, desenvolvidos para apoiar processos de transformação digital em empresas de qualquer setor e em diferentes níveis de maturidade analítica.

| Prompt | Para quem | O que gera |
|---|---|---|
| [📋 Relatório por Cargo](#-prompt-1--relatório-de-usos-de-ia-por-cargo) | Profissionais, RH, consultores | Mapa de 80+ usos de IA para um cargo específico |
| [🏭 Relatório por Empresa](#-prompt-2--relatório-de-tecnologias-emergentes-por-empresa) | Líderes, consultores, C-level | Mapa de IA + outras tecnologias por área da empresa |
| [🧭 Consolidação Executiva por Cargos](#-prompt-3--consolidação-executiva-de-usos-de-ia-por-cargos) | Diretoria, PMO, consultores, transformação digital | Síntese executiva de todos os cargos analisados, com consolidado, Excel e apresentação |
| [💼 Business Case de IA](#-prompt-4--business-case-de-produtividade-e-ganhos-financeiros) | CEO, COO, CFO, diretoria e investidores | Estimativa de produtividade, custos, ganhos financeiros, payback e materiais executivos |

---

## 📋 Prompt 1 — Relatório de Usos de IA por Cargo

**Arquivo:** [`prompts/prompt-usos-ia-por-cargo.md`](prompts/prompt-usos-ia-por-cargo.md)

### O que é

A partir do nome ou descrição de um cargo, gera um relatório detalhado mapeando como a IA pode ser usada no dia a dia daquele profissional — com mais de 80 usos práticos organizados por categoria.

### Categorias de uso geradas

| Categoria | Mínimo de usos |
|---|---|
| 💬 Chat do dia a dia | 10 |
| 📁 Projetos com contexto persistente | 10 |
| 🧩 Skills / Assistentes especializados | 10 |
| 💻 Vibe code (geração de código assistida) | 10 |
| ⚙️ Automações e workflows | 10 |
| 🔗 Conexões com sistemas e aplicativos | 20 |

Cada uso é classificado por **dificuldade** e avaliado quanto ao **ganho de tempo** e **ganho de qualidade**.

O relatório ainda inclui:
- 🗺️ Mapa de priorização (Quick Wins vs. Projetos Estratégicos)
- 📅 Roteiro de adoção em 90 dias
- ⚡ Top 5 usos transformadores do cargo

### Como usar

**1.** Abra o arquivo [`prompts/prompt-usos-ia-por-cargo.md`](prompts/prompt-usos-ia-por-cargo.md) e copie o conteúdo completo.

**2.** Preencha a seção `## ENTRADA` com:

```
Dados do Cargo (obrigatório):
- Nome do cargo: [ex: Gerente de Vendas]
- Descrição completa (JD): [cole aqui o texto da vaga, se tiver]

Dados da Empresa (opcional, mas recomendado):
- Setor, porte, modelo de negócio
- Sistemas em uso (ERP, CRM, etc.)
- Estrutura organizacional
- Dores e desafios conhecidos
```

> 💡 Cole a descrição completa da vaga para resultados mais precisos. Quanto mais contexto, mais relevantes serão as integrações sugeridas.

**3.** Cole no seu assistente de IA preferido. Testado e otimizado para **Claude (Anthropic)**.

### Exemplo de output

<details>
<summary>📋 Clique para expandir — Analista Financeiro em empresa B2B de médio porte</summary>

#### Perfil do Cargo

**Cargo:** Analista Financeiro Pleno | **Área:** Financeiro / Controladoria | **Nível:** Tático  
**Ferramentas típicas inferidas:** Excel, Power BI, SAP, e-mail corporativo, Teams/Slack, sistemas bancários

**20 tarefas mapeadas:**
conciliação bancária, lançamentos contábeis, DRE, contas a pagar/receber, fluxo de caixa, fechamento mensal, apresentações para diretoria, análise de variações orçamentárias, emissão de notas fiscais, gestão de reembolsos, comunicação com auditores, KPIs financeiros, forecasts, análise de rentabilidade, controle de contratos, planejamento orçamentário, gestão de inadimplência, obrigações fiscais, análise de custos, relacionamento bancário.

#### Amostra — Chat do dia a dia

| # | Tarefa | Como usar a IA | Ganho de Tempo | Ganho de Qualidade | Dificuldade |
|---|---|---|---|---|---|
| 1 | Análise de variações orçamentárias | Colar os dados e pedir à IA que identifique padrões e anomalias | Muito Alto | Alto | 🟢 Muito Fácil |
| 2 | Redação de e-mails de cobrança | Descrever o contexto e pedir e-mail com tom adequado | Alto | Alto | 🟢 Muito Fácil |
| 3 | Interpretação de regulamentações fiscais | Colar texto da norma e pedir resumo com impactos práticos | Alto | Moderado | 🟢 Muito Fácil |

#### Amostra — Vibe Code

| # | Tarefa | O que gerar | Ferramenta | Ganho de Tempo | Dificuldade |
|---|---|---|---|---|---|
| 1 | Conciliação bancária automatizada | Script que cruza extrato bancário com lançamentos do ERP | Python ou VBA | Muito Alto | 🟡 Média |
| 2 | Dashboard de KPIs financeiros | Código do painel com indicadores principais | Looker Studio | Alto | 🔵 Fácil |

#### ⚡ Top 5 Usos Transformadores
1. Script de conciliação bancária — elimina o processo mais repetitivo do cargo
2. Forecast automatizado com IA — projeções mais rápidas com análise de cenários
3. Integração ERP + IA para alertas de inadimplência — ação proativa
4. Skill de redação financeira — padroniza comunicações com diretoria e auditores
5. Automação do fechamento mensal — checklist inteligente que reduz erros

</details>

---

## 🏭 Prompt 2 — Relatório de Tecnologias Emergentes por Empresa

**Arquivo:** [`prompts/prompt-tecnologias-por-empresa.md`](prompts/prompt-tecnologias-por-empresa.md)

### O que é

A partir dos dados de uma empresa, gera um relatório estratégico mapeando como a IA e outras tecnologias emergentes podem ser adotadas em cada área da organização — com usos práticos, classificação de dificuldade e um roteiro de transformação digital de 24 meses.

### Tecnologias cobertas

| Tecnologia | Exemplos de aplicação |
|---|---|
| 🤖 Inteligência Artificial | Chat, projetos, skills, vibe code, automações, integrações |
| 📡 IoT | Sensores, telemetria, monitoramento em tempo real |
| 🚁 Drones / VANT | Mapeamento, pulverização, monitoramento aéreo |
| ☁️ Cloud Computing | Infraestrutura, SaaS, integração de sistemas |
| 🔗 Blockchain | Rastreabilidade, contratos inteligentes, certificações |
| 🌍 XR / Metaverso | Treinamento imersivo, showrooms virtuais |
| 🤖 Robótica | Automação física, cobots, robôs autônomos |
| 🏗️ Edge Computing | Processamento local, operação offline |
| 🌾 Agricultura 5.0 | Precisão, sensoriamento, integração digital-físico |
| ⚡ Energias Renováveis | Solar, biogás, eficiência energética |
| 🛰️ Sensoriamento Remoto | Satélites, GIS, imagens multiespectrais |
| 📊 Big Data & Analytics | Data lakes, BI em tempo real, análise preditiva |

### O relatório gerado inclui

- Seção por área da empresa (produção, financeiro, comercial, RH, etc.)
- Para cada área: tabelas de usos de IA + usos de cada tecnologia relevante
- 🗺️ Mapa de calor tecnológico (Áreas × Tecnologias)
- 🎯 Mapa de priorização estratégica (Quick Wins vs. Iniciativas Estratégicas)
- 📅 Roteiro de transformação digital em 24 meses
- 📊 Estimativa de impacto por área (custo, receita, risco)
- ⚡ Top 10 iniciativas transformadoras

### Como usar

**1.** Abra o arquivo [`prompts/prompt-tecnologias-por-empresa.md`](prompts/prompt-tecnologias-por-empresa.md) e copie o conteúdo completo.

**2.** Preencha a seção `## ENTRADA`:

```
Dados obrigatórios:
- Nome, setor e atividades principais da empresa

Dados recomendados (quanto mais, melhor):
- Modelo de negócio e porte
- Maturidade tecnológica atual
- Sistemas e tecnologias já em uso
- Áreas/departamentos existentes
- Principais desafios e dores
- Objetivos estratégicos 2–3 anos
- Restrições relevantes (conectividade, orçamento, etc.)
```

**3.** Cole no Claude ou outro assistente de IA avançado.

> ⚠️ O output deste prompt é muito extenso. Recomenda-se usar um modelo com janela de contexto longa e, se necessário, solicitar por partes (ex: "gere apenas as seções da Área de Produção").

### Exemplo de output

**Arquivo completo:** [`exemplos/exemplo-agroverde-soja-laranja-pecuaria.md`](exemplos/exemplo-agroverde-soja-laranja-pecuaria.md)

**Empresa do exemplo:** AgroVerde Ltda. (fictícia) — soja (3.000 ha) + laranja (1.200 ha) + pecuária de corte (1.500 cabeças)

<details>
<summary>📋 Clique para expandir — Destaques do exemplo AgroVerde</summary>

**10 áreas cobertas:** Produção de soja, Citricultura, Pecuária, Financeiro, Comercial, Logística, RH, Sustentabilidade, TI e Diretoria.

**Mapa de Calor — destaques:** IA e IoT com alto potencial em todas as áreas produtivas; Drones com alto potencial em Soja, Citros e Sustentabilidade; Blockchain com alto potencial em Comercial e Citros; XR com alto potencial em RH.

**Top 3 Quick Wins identificados:**
1. Assistente de IA para a equipe técnica (sem custo, começa hoje)
2. Skill de diagnóstico de HLB — protege o ativo mais crítico da citricultura
3. Automação de alertas de cotação de soja — captura oportunidades de venda sem monitoramento manual

**Top 3 Iniciativas Estratégicas:**
1. Plataforma blockchain de rastreabilidade (soja + laranja + boi) para conformidade EUDR
2. Rede IoT de sensores de solo + irrigação de precisão em 3.000 ha
3. Usina solar fotovoltaica para os pivôs de irrigação

</details>

---

## 🧭 Prompt 3 — Consolidação Executiva de Usos de IA por Cargos

**Arquivo:** [`prompts/prompt-consolidacao-executiva-cargos.md`](prompts/prompt-consolidacao-executiva-cargos.md)

### O que é

A partir de um conjunto de relatórios individuais já produzidos por cargo, gera um consolidado executivo da empresa com visão transversal de prioridades, níveis de dificuldade, quick wins, materiais para diretoria e uma apresentação pronta para discussão executiva.

### O que o output deve gerar

| Entregável | Finalidade |
|---|---|
| Relatório executivo consolidado | Resumir os achados de todos os cargos em uma visão única |
| Planilha geral | Listar cargos, arquivos, quantidades por dificuldade e exemplos relevantes |
| Apresentação executiva | Mostrar metodologia, consolidado e um slide por cargo |
| Síntese metodológica | Explicar como os relatórios individuais foram transformados em visão corporativa |

O prompt foi desenhado para situações em que a empresa já mapeou funções individualmente e agora precisa converter esse material em **priorização organizacional**, **governança de implantação** e **comunicação executiva**.

### Quando usar

Use este prompt quando você já tiver produzido os relatórios por cargo e quiser transformar dezenas de análises individuais em um material executivo integrado, adequado para diretoria, comitê de inovação, PMO, RH ou transformação digital.

### Como usar

**1.** Abra o arquivo [`prompts/prompt-consolidacao-executiva-cargos.md`](prompts/prompt-consolidacao-executiva-cargos.md) e copie o conteúdo completo.

**2.** Reúna como entrada:

```
- Lista de cargos analisados
- Arquivos ou trechos dos relatórios individuais por cargo
- Classificação de dificuldade já usada nos relatórios
- Exemplos de aplicações mais relevantes por cargo
- Contexto da empresa (setor, porte, objetivos e restrições)
```

**3.** Solicite a geração dos materiais consolidados em relatório, planilha e apresentação.

> 💡 Este prompt funciona especialmente bem quando os relatórios individuais seguem um padrão consistente de categorias, dificuldade e ganhos esperados.

### O relatório consolidado inclui

- Visão executiva dos cargos cobertos e da metodologia usada
- Sumário por nível de dificuldade consolidado na empresa
- Destaques por área ou macrofunção
- Exemplos selecionados de aplicações por cargo
- Proposta de apresentação com um slide por cargo
- Arquivo geral para uso interno e compartilhamento com a liderança

---

## 💼 Prompt 4 — Business Case de Produtividade e Ganhos Financeiros

**Arquivo:** [`prompts/prompt-business-case-ia-produtividade.md`](prompts/prompt-business-case-ia-produtividade.md)

### O que é

A partir do consolidado dos cargos, das premissas salariais e dos níveis de dificuldade das aplicações, gera um business case executivo para estimar produtividade, economia potencial, custos de licenças, APIs, cloud, esforço de implantação, payback e materiais para tomada de decisão.

### O que o output deve gerar

| Entregável | Finalidade |
|---|---|
| Business case financeiro | Estimar custos, ganhos, economia e faixas de retorno |
| Cenários de adoção | Comparar ondas como Muito Fácil + Fácil e Média + Difícil |
| Tese de implementação | Priorizar ondas, dependências, quick wins e responsáveis |
| Matriz por área | Mostrar onde há mais retorno, viabilidade e complexidade |
| Apresentação executiva | Suportar decisão de diretoria com narrativa objetiva |

Este prompt foi desenhado para traduzir um mapeamento técnico de usos de IA em uma linguagem de **decisão executiva**, com foco em **ROI**, **payback**, **priorização** e **viabilidade organizacional**.

### Quando usar

Use este prompt quando a empresa já tiver identificado casos de uso por cargo ou por área e precisar responder perguntas como: quanto custa implantar, quanto tempo economiza, quanto vale financeiramente, quais APIs e infraestrutura serão necessárias, e em quanto tempo o programa pode ficar de pé.

### Como usar

**1.** Abra o arquivo [`prompts/prompt-business-case-ia-produtividade.md`](prompts/prompt-business-case-ia-produtividade.md) e copie o conteúdo completo.

**2.** Reúna como entrada:

```
- Consolidado dos cargos e aplicações por nível de dificuldade
- Número de colaboradores e distribuição por função
- Premissas salariais médias por grupo de cargos
- Restrições específicas (ex.: exclusão de ganhos econômicos para algumas funções)
- Ferramentas candidatas (LLMs, automação, OCR, cloud, integrações)
- Premissas de adoção, treinamento e suporte
```

**3.** Solicite o business case em duas camadas: relatório detalhado e versão executiva para diretoria.

> 💡 O valor deste prompt cresce muito quando as premissas financeiras são explícitas e quando os ganhos são separados entre benefício quantitativo e benefício qualitativo.

### O business case inclui

- Estimativa de horas economizadas por cenário
- Conversão de produtividade em impacto financeiro
- Estimativa de custos de licenças, APIs, OCR, automação e cloud
- Sensibilidade por faixa de adoção
- Estimativa de prazo de implantação por onda
- Materiais executivos para discussão com diretoria, CFO, COO e comitês internos

---

## 🏷️ Legenda de Dificuldade

Usada em todos os relatórios gerados por ambos os prompts:

| Nível | Descrição | Investimento | Prazo | Requer programação? |
|---|---|---|---|---|
| 🟢 Muito Fácil | Uso imediato, sem configuração. Qualquer pessoa começa hoje. | Gratuito a baixo | Dias | Não |
| 🔵 Fácil | Configuração simples, treinamento básico de usuários. | Baixo a médio | 2–8 semanas | Não |
| 🟡 Média Dificuldade | Integrações, automações no-code, parceiro especializado. | Médio | 2–6 meses | Mínima (no-code) |
| 🔴 Difícil | Desenvolvimento customizado, infraestrutura, equipe técnica dedicada. | Alto | 6–18 meses | Sim |

---

## 📂 Estrutura do Repositório

```text
ai-prompts-transformacao-digital/
├── README.md
├── LICENSE
├── prompts/
│   ├── prompt-usos-ia-por-cargo.md
│   ├── prompt-tecnologias-por-empresa.md
│   ├── prompt-consolidacao-executiva-cargos.md
│   └── prompt-business-case-ia-produtividade.md
└── exemplos/
    ├── exemplo-analista-financeiro.md
    └── exemplo-agroverde-soja-laranja-pecuaria.md
```

---

## 🤝 Contribuições

Contribuições são muito bem-vindas! Você pode ajudar de três formas:

### 📤 Compartilhar outputs gerados
Usou um dos prompts e gerou um relatório interessante? Abra uma **Issue** com a tag `exemplo` informando o cargo, a empresa ou o setor e os principais destaques. Os melhores exemplos serão adicionados à pasta [`exemplos/`](exemplos/).

### 🛠️ Sugerir melhorias nos prompts
Identificou uma lacuna, um caso de uso não coberto ou uma forma de tornar os relatórios mais precisos? Abra uma **Issue** com a tag `melhoria` descrevendo sua sugestão.

### 🌍 Traduzir para outros idiomas
Quer adaptar os prompts para inglês, espanhol ou outro idioma? Crie um arquivo na pasta `prompts/` com o sufixo do idioma:
- `prompt-usos-ia-por-cargo-en.md`
- `prompt-tecnologias-por-empresa-es.md`
- `prompt-consolidacao-executiva-cargos-en.md`
- `prompt-business-case-ia-produtividade-en.md`

### Como enviar um Pull Request

```bash
# 1. Faça um fork do repositório no GitHub
# 2. Clone o seu fork localmente
git clone https://github.com/seu-usuario/ai-prompts-transformacao-digital.git

# 3. Crie uma branch para sua contribuição
git checkout -b minha-contribuicao

# 4. Faça suas alterações e commit
git add .
git commit -m "Adiciona novos prompts executivos de IA"

# 5. Envie para o seu fork
git push origin minha-contribuicao

# 6. Abra um Pull Request no repositório original
```

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo [`LICENSE`](LICENSE) para mais detalhes.  
Livre para usar, adaptar e compartilhar — créditos são sempre apreciados. 🙏

---

*Criado por Laura · 2026*
