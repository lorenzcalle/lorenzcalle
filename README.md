# Lorenzo Callegaro

Bacharel em Ciência da Computação (URI Santo Ângelo, 2026). Construo produtos e automações com IA generativa, do protótipo à produção.

[LinkedIn](https://www.linkedin.com/in/lorenzo-callegaro/) · [classcompute.com.br](https://classcompute.com.br)

## ClassCompute

**Site:** [classcompute.com.br](https://classcompute.com.br) · **App:** [app.classcompute.com.br](https://app.classcompute.com.br)

Agente de IA para professores da educação básica. O professor parte do tema que já ensina e recebe plano de aula, roteiro, folha do aluno e rubrica em PDF, ligados à BNCC Computação. O projeto nasceu do meu TCC e da bolsa PIBIC/CNPq na URI.

- **Ancoragem contra alucinação.** Habilidade, eixo e citações da BNCC vêm de um corpus recuperado por RAG (FAISS + embeddings multilíngues) e são montados de forma determinística. O LLM só redige a atividade.
- **Stack.** Google Cloud Run (Docker) e Cloudflare, FastAPI, React/TypeScript, PostgreSQL (Neon), contas com JWT e modelos intercambiáveis (Gemini, OpenAI, Anthropic, Groq).
- **Qualidade.** Mais de 1.000 testes automatizados no servidor e 453 na interface, e mais de 180 PRs integradas.
- **Avaliação antes de mudar.** Cada mudança de prompt ou de base é medida com um conjunto fixo de pedidos, baseline e teste A/B pareado com avaliador automático cego. Ideias que não se confirmam são revertidas.
- **Validação com professores.** Questionário TAM dentro do sistema: média 4,41/5 e 93% de concordância (n = 5, jun/2026).
- **Equipe de agentes de código.** O desenvolvimento roda no OpenBot com Claude Code, Codex e Gemini em papéis de planejador, implementador, revisor e integrador. Cada issue vira plano, PR, revisão com prova local e resumo, e nada entra sem a minha aprovação.

> O código da ClassCompute é privado. Posso mostrar o repositório e a arquitetura numa conversa.

## Outros projetos

- **[site-brinquedos](https://github.com/lorenzcalle/site-brinquedos)** · [bc.san.uri.br](https://bc.san.uri.br): site e painel do projeto Brinquedos Científicos (URI). React/TypeScript e Supabase com RLS, workers no servidor para a chave secreta nunca ir ao navegador, pré-renderização para SEO e deploy em Linux/nginx.
- **[omr.san.uri.br](https://omr.san.uri.br)**: site da Olimpíada Missioneira de Robótica, com hospedagem em Ubuntu Server.

## No dia a dia

No suporte técnico em hospedagem e cloud, uso IA na operação: processos de um agente de atendimento, análise de atendimentos com IA, Claude com MCPs e skills próprias, e automações para o time.

**Ferramentas:** Claude Code, Codex, Replit · Python, FastAPI, TypeScript, React, Supabase, SQL · Docker, Google Cloud Run, Linux, DNS, SSL/TLS
