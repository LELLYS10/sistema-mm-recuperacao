# Sistema MM Recuperação — regras específicas deste projeto

Esta pasta `.claude/` guarda as regras **só deste projeto**.
Elas ficam separadas das regras pessoais globais do Tom, que vivem em `~/.claude/CLAUDE.md`
e valem em qualquer projeto (por exemplo: responder sempre em português do Brasil, de forma simples).
Aqui só entra o que é específico deste projeto.

## Qual projeto é este
- Hoje é **um único arquivo de texto**: `Prompt_Mestre_MM_Reparacao_Performance.txt`, um "prompt mestre" que descreve o sistema web da oficina **M.M Reparação e Performance** (diagnóstico eletrônico de linha diesel, injeção eletrônica, scanner, bombas e bicos, reprogramação).
- O prompt pede: gestão de oficina (orçamento, OS, caixa, financeiro, clientes, veículos, peças, estoque, produtividade do mecânico) em web responsiva, com Supabase/PostgreSQL.
- Repositório GitHub: `LELLYS10/sistema-mm-recuperacao` (**público**). Pasta no Mac: `~/Desktop/Sistema MM Recuperaçao`.
- **Não tem código ainda.** Se o sistema for construído, o código deve ir para um repositório/pasta própria, e este continua sendo só o prompt.
- **Não tem ligação com o CredPlus** nem com a VPS.

## Regras deste projeto
1. Repositório público: não colocar dados reais da oficina, de clientes, telefones, chaves ou senhas.
2. Se o prompt mudar, manter a versão anterior no histórico do Git (commit) em vez de sobrescrever sem registro.
3. Ao construir o sistema, seguir as regras do próprio prompt (simples, rápido e preparado para crescer) e criar um `.claude/` novo no projeto de código.
4. Não apagar nada sem pedir confirmação ao Tom.
