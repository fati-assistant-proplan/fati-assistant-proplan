# 🤖 assistant-proplan

Esta conta GitHub é a conta institucional do projeto **Assistente PROPLAN UFPE** — uma plataforma web desenvolvida para apoiar as atividades da Pró-Reitoria de Planejamento, Orçamento e Finanças da UFPE.

---

## Sobre esta conta

A conta **assistant-proplan** centraliza todos os recursos de infraestrutura e implantação do projeto. Os seguintes serviços estão vinculados exclusivamente a ela:

- **GitHub**: repositório principal em [assistant-proplan/assistant-proplan](https://github.com/fati-assistant-proplan/assistant-proplan)
- **Vercel**: conta e projeto de deploy contínuo vinculados a esta conta GitHub
- **Supabase**: projeto de banco de dados e autenticação vinculado a esta conta

Manter esses serviços sob uma conta única garante que deploys, variáveis de ambiente e integrações funcionem de forma consistente, independentemente de quem está contribuindo com o código.

---

## Fluxo de contribuição

Qualquer colaborador com acesso ao repositório pode abrir e revisar Pull Requests a partir de sua conta pessoal. No entanto, **o merge de PRs na branch principal deve ser realizado exclusivamente pela conta `assistant-proplan`**, a fim de manter o rastreamento correto de deploys e permissões no Vercel.

### Passo a passo recomendado

1. Crie um branch a partir de `main` na sua conta pessoal ou fork.
2. Abra um Pull Request para `assistant-proplan/assistant-proplan`.
3. Solicite revisão de pelo menos um colaborador — a aprovação pode vir de qualquer conta com acesso.
4. Após aprovação, o merge deve ser feito pela conta **assistant-proplan**.

---

## Repositório principal

| Recurso | Link |
|---|---|
| Repositório | [assistant-proplan/assistant-proplan](https://github.com/assistant-proplan/assistant-proplan) |
| Deploy (produção) | [assistant-proplan.vercel.app](https://assistant-proplan.vercel.app) |

---

## Tecnologias utilizadas

- **Next.js** — framework React com suporte a SSR e API Routes
- **TypeScript** — tipagem estática
- **Tailwind CSS** + **Shadcn UI** — estilização e componentes
- **React Hook Form** + **Zod** — formulários e validação
- **Vercel AI SDK** — integração com modelos de linguagem
- **Supabase** — banco de dados e autenticação

---

> Dúvidas sobre acesso ou permissões? Entre em contato com os mantenedores do projeto.
