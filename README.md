# 💸 App de Finanças Pessoais por Conversa — Vibe Coding com IA

> 🚀 App de Finanças Pessoais por Conversa — desenvolvido com Vibe Coding e IA.  
> Controle seus gastos de forma simples e natural, sem planilhas ou formulários.  
> Registre despesas via chat, defina metas e receba dicas inteligentes de um Agente Financeiro virtual.  

Este projeto foi desenvolvido como parte do desafio da DIO, utilizando o conceito de Vibe Coding para criar um aplicativo de organização financeira pessoal com apoio de Inteligência Artificial. A proposta é transformar ideias em soluções reais por meio de conversas naturais com a IA, sem escrever uma única linha de código.

---

## ✨ Resumo do App

Um app de finanças pessoais que funciona por meio de conversas. O usuário registra gastos, define metas e recebe dicas de economia de um Agente Financeiro virtual. Tudo acontece em linguagem natural, sem formulários ou planilhas.

---

## 🧠 Prompt Final (PRD)

> Quero que você atue como parceiro de produto para criar um MVP de um App de Finanças Pessoais orientado a conversas.  
> **Contexto:** Usuários iniciantes se cansam de preencher formulários e planilhas. Quero uma experiência por chat que registre gastos, classifique automaticamente, crie metas simples e ofereça um Agente Financeiro com dicas personalizadas.  
>  
> **Entregáveis esperados:**  
> 1. Fluxo de telas (com foco em chat) mapeando a jornada: Onboarding, Chat de registro, Metas, Relatórios, Configurações.  
> 2. Plano de MVP: funcionalidades essenciais, recursos técnicos, restrições e riscos.  
> 3. Definição do Agente Financeiro: missão, tom de voz, princípios, exemplos de mensagens e casos de uso (registro de gasto, sugestão de economia, acompanhamento de metas).  
> 4. Plano de validação inicial: objetivos, métricas de sucesso, experimentos e hipóteses a testar em 2 semanas.  
>  
> **Regras:**  
> - Seja claro, direto, em português.  
> - Use formato estruturado com títulos e listas.  
> - Otimize para um plano gratuito com no máximo 5 interações diárias.  
> - Se necessário, forneça versões resumidas para caber nas limitações.  
>  
> **Objetivo:** Simular um produto real sem escrever código, com entregáveis prontos para documentação no README.

---

## 🖼️ Interações simuladas com a IA

### 🔹 Interação 1 — Fluxo de Telas
- **Onboarding:** Perguntas simples (“Qual sua meta mensal?”). Estado vazio: “Ainda não há gastos registrados.”  
- **Chat Principal:** Registro de gastos por texto, classificação automática, correção rápida.  
  - Usuário: “Almoço R$28 hoje”  
  - Agente: “Anotei R$28 em Alimentação. Quer ajustar a categoria?”  
- **Metas:** Criação de metas mensais com lembretes. Estado vazio: “Defina sua primeira meta: ‘Guardar R$200/mês’.”  
- **Relatórios:** Gastos por categoria, progresso da meta, insights semanais.  
- **Configurações:** Preferências de categorias, tom do agente, notificações.

---

### 🔹 Interação 2 — Definição do Agente Financeiro
- **Missão:** Simplificar finanças e motivar usuários iniciantes.  
- **Tom de voz:** Amigável, direto, educativo.  
- **Princípios:** Confirmar + classificar + sugerir; personalizar pelo histórico; ser breve.  
- **Exemplos de mensagens:**  
  - “Meta ‘Guardar R$200/mês’ ativa. Sugestão: transfira R$50 toda sexta.”  
  - “Assinaturas somaram R$87. Que tal revisar uma que você usa pouco?”  
  - “Você já registrou 5 gastos nesta semana. Consistência gera clareza.”

---

### 🔹 Interação 3 — Plano de MVP
- **Funcionalidades essenciais:** Chat de registro, classificação automática, metas simples, relatórios básicos, agente financeiro.  
- **Dados mínimos:** Valor, categoria, data, descrição.  
- **Não-objetivos:** Integração bancária, gráficos avançados, recomendações de investimento.  
- **Riscos:**  
  - Ambiguidade no texto → Mitigar com confirmações.  
  - Baixa adesão → Usar lembretes amigáveis.  
  - Categorias imprecisas → Aprender com correções.

---

### 🔹 Interação 4 — Plano de Validação (2 semanas)
- **Objetivos:** Testar se chat reduz fricção e se metas aumentam retenção.  
- **Métricas:**  
  - Ativação ≥60% (≥3 gastos na primeira semana)  
  - Retenção ≥35% (voltar na semana 2)  
  - Correções ≤30% após 10 registros  
  - Engajamento com metas ≥40%  
- **Experimentos A/B:** Onboarding com ou sem meta sugerida; tom direto vs acolhedor.  
- **Checklist:** Tracking de eventos, feedback de 5 usuários, relatório com métricas.

---

### 🔹 Interação 5 — Versão Compacta para README
- **Problema:** Apps tradicionais são tediosos e exigem muita entrada manual.  
- **Solução:** Chat que registra gastos, classifica, cria metas e dá dicas.  
- **Funcionalidades:** Chat, classificação automática, metas, relatórios, agente.  
- **MVP:** Escopo 1.0 com dados mínimos e relatórios simples.  
- **Agente:** Tom amigável e direto, confirma + sugere + motiva.  
- **Validação:** Ativação ≥60%, retenção ≥35%, correções ≤30%.  
- **Entrega:** PRD + prints/vídeos + resumo + reflexão no README.

---

## 💬 Reflexão Pessoal sobre o Processo

Quando comecei este desafio, confesso que fiquei um pouco perdido nas etapas e nas ferramentas. A ideia de “programar sem código” parecia abstrata demais. Mas conforme fui estruturando os prompts e entendendo como guiar a IA, percebi que o segredo não estava em dominar a técnica, mas em **clareza e intenção**.  

O que mais funcionou bem foi transformar minhas ideias em instruções simples e diretas. A cada interação, a IA respondia melhor quando eu mostrava exatamente a vibe do que queria construir. Isso me ensinou que conversar com IA é como conversar com uma equipe criativa: quanto mais claro o briefing, mais próximo do resultado ideal.  

O que não funcionou tão bem foi tentar usar o Lovable sem planejar as perguntas. Com poucos créditos, percebi que precisava ser estratégico. Foi aí que decidi usar o Copilot para concluir o projeto — e isso me mostrou que a IA pode se adaptar às nossas limitações, desde que saibamos como guiá-la.  

O maior aprendizado foi enxergar a IA como **parceira criativa**. Não é sobre pedir que ela faça tudo, mas sobre pensar junto, lapidar ideias e transformar conceitos em algo funcional. O Vibe Coding me mostrou que tecnologia pode ser leve, divertida e colaborativa.  

No fim, percebi que o desafio não era apenas criar um app de finanças, mas aprender a **conversar com a IA de forma inteligente e criativa**. Essa experiência me deixou mais confiante para usar IA em outros projetos e me ensinou que cada interação é um experimento — e cada experimento traz uma descoberta.

---

## 🚀 Link do Repositório

> [https://github.com/Oliveirclau/dio-lab-vibe-coding-app-financas]

---

## 🧩 Topics do Projeto

- `financas-pessoais`  
- `organizacao-financeira`  
- `inteligencia-artificial`  
- `vibe-coding`  
- `copilot`  
- `lovable`  
- `mvp`  
- `chatbot`  
- `agente-financeiro`  
- `dio-desafio`  
- `no-code`  
- `projeto-educacional`  

---

## 🧠 Conclusão

Este projeto mostra como é possível criar soluções reais com IA sem escrever código, apenas guiando com intenção e clareza. O Vibe Coding é uma nova forma de pensar tecnologia como extensão do raciocínio criativo. Cada interação é um experimento — e cada experimento, uma descoberta.
