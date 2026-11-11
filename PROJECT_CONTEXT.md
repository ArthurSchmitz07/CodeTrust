# CodeTrust — Contexto do projeto

## Objetivo

Investigar qual modelo produz soluções Python mais corretas, seguras e eficientes quando recebe os mesmos problemas. O projeto combina aprendizado, portfólio técnico e uma metodologia reproduzível de avaliação.

## Colaboração

O responsável controla o desenvolvimento. Cada implementação exige proposta, explicação e aprovação prévia, seguida de validação e documentação. Não avançar automaticamente. As orientações permanentes estão em AGENTS.md.

## Tecnologias escolhidas

- Frontend: Next.js, React, TypeScript e Tailwind CSS.
- Backend: Python e FastAPI.
- Avaliação: Pytest, Ruff e Bandit.
- Banco de dados: SQLite inicialmente.
- Versionamento: Git e GitHub.

Essas escolhas ainda não representam dependências instaladas. Versões e compatibilidade serão verificadas antes da instalação.

## Arquitetura proposta

O frontend consumirá a API FastAPI. O backend gerenciará experimentos e persistência em SQLite. O módulo de avaliação terá execução isolada, cujo mecanismo ainda precisa ser discutido e aprovado.

Pastas planejadas, ainda não criadas:

- frontend/: interface e navegação.
- backend/: API e persistência.
- challenges/: enunciados padronizados e casos de teste.
- experiments/: soluções coletadas e registros de experimentos.
- docs/: metodologia e decisões técnicas.

## Estado em 2026-11-11

Primeiro escopo aprovado: criar AGENTS.md, PROJECT_CONTEXT.md, README.md e .gitignore; inicializar o Git local; não instalar dependências, criar commits ou publicar.

Os quatro arquivos iniciais foram criados e o Git foi inicializado na branch main. A validação confirmou ausência de commits e de remotos. Não há código de aplicação, testes automatizados ou ambiente de execução configurados.

Inspeção do ambiente em 2026-11-10:

- Pasta: C:\Users\Arthur Schmitz\Desktop\CodeTrust, inicialmente vazia.
- Node.js: v24.19.0.
- npm: 11.17.0.
- Python: 3.14.10.
- Git: 2.55.0.windows.3; nome e e-mail configurados.
- GitHub CLI: não instalado.

## Metodologia a definir

- Começar com cinco desafios Python e coleta manual das soluções.
- Padronizar enunciados, condições de coleta e registro do modelo e de sua versão.
- Definir métricas e limites da avaliação antes de comparar resultados.
- Separar correção, achados de qualidade e achados de segurança. Análise estática não comprova ausência de vulnerabilidades.
- Definir medição de desempenho em condições comparáveis.
- Aprovar isolamento e limites de execução antes de executar qualquer solução coletada.

## Validação desta etapa

Validação concluída em 2026-11-11: conteúdo dos quatro arquivos conferido em UTF-8; git status confirmou os quatro arquivos ainda não rastreados e a branch main sem commits; git remote -v não apresentou remotos. git check-ignore confirmou que dependências, caches, arquivos .env, bancos SQLite e arquivos auxiliares são ignorados. Os exemplos .env.example e os documentos permanecem versionáveis. Não há testes de aplicação a executar nesta etapa.

## Pendências e próximos passos

1. Base documental aprovada pelo responsável para o primeiro commit local.
2. Primeiro commit autorizado: chore: initialize CodeTrust project. Este snapshot registra a base documental inicial; verificar o histórico do Git para seu identificador. A autorização não inclui push ou publicação.
3. Definir proprietário e visibilidade do repositório GitHub e criá-lo vazio desde o início do desenvolvimento.
4. Após autorização, conectar origin e fazer o primeiro push. O navegador pode ser usado sem instalar gh.
5. Propor a próxima pequena implementação e aguardar aprovação.

Nenhuma licença foi escolhida. Não criar licença sem discutir com o responsável.

## Marcos futuros

Frontend, backend, desafios e coleta, avaliação isolada, integração com resultados reais e publicação da primeira versão. Bons marcos para LinkedIn: primeira interface funcional, integração frontend/backend, avaliação automatizada e primeiros resultados reais.
