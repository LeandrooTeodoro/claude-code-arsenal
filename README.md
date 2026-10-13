# Claude Code Arsenal

Coleção das skills, agentes e comandos que uso no Claude Code, reunidos num só lugar.

**Nada aqui foi criado por mim, exceto a pasta [`leandro/`](leandro/).** Todo o crédito vai para os autores originais listados abaixo. Cada pasta mantém o arquivo de licença original do projeto de onde veio. Para usar, prefira instalar direto da fonte oficial, que recebe atualizações.

## Conteúdo

| Pasta | Skills | Agentes | Comandos | Autor / Fonte original | Licença |
|---|---:|---:|---:|---|---|
| [`ecc/`](ecc/) | 311 | 71 | 97 | [affaan-m/ECC](https://github.com/affaan-m/ECC) (Affaan Mustafa) | MIT |
| [`gsd/`](gsd/) | — | 35 | 72 | [gsd-build/get-shit-done](https://github.com/gsd-build/get-shit-done) | MIT |
| [`claude-mem/`](claude-mem/) | 23 | — | — | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | Apache-2.0 |
| [`hyperframes/`](hyperframes/) | 22 | — | — | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) (HeyGen) | Apache-2.0 |
| [`superpowers/`](superpowers/) | 15 | — | — | [obra/superpowers](https://github.com/obra/superpowers) | MIT |
| [`n8n-skills/`](n8n-skills/) | 15 | — | — | [czlonkowski/n8n-skills](https://github.com/czlonkowski/n8n-skills) | MIT |
| [`anthropic-skills/`](anthropic-skills/) | 10 | — | — | [anthropics/skills](https://github.com/anthropics/skills) (Anthropic) | Apache-2.0 (LICENSE.txt em cada skill) |
| [`ui-ux-pro-max/`](ui-ux-pro-max/) | 7 | — | — | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | MIT |
| [`obsidian-skills/`](obsidian-skills/) | 6 | — | — | [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) | MIT |
| [`replica-pack/`](replica-pack/) | 11 | — | — | Autor não identificado. Se for seu, abra uma issue para eu creditar | — |
| [`task-observer/`](task-observer/) | 1 | — | — | [rebelytics/one-skill-to-rule-them-all](https://github.com/rebelytics/one-skill-to-rule-them-all) | CC BY 4.0 |
| [`claude-code-setup/`](claude-code-setup/) | 1 | — | — | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) (Anthropic) | Apache-2.0 |
| [`vercel-skills/`](vercel-skills/) | 1 | — | — | [vercel-labs/skills](https://github.com/vercel-labs/skills) (Vercel) | MIT |
| [`leandro/`](leandro/) | 4 | — | — | Minhas skills próprias | MIT |

## Fora do repositório (licença não permite redistribuir)

Estas eu também uso, mas a licença não permite cópia. Instale pela fonte:

- **Blotato** (8 skills): [Blotato-Inc/blotato-skills](https://github.com/Blotato-Inc/blotato-skills). O repositório não tem licença pública.
- **Skills da Anthropic no app Claude** (docx, pdf, pptx, xlsx, skill-creator, built-in-browser etc.): proprietárias, com todos os direitos reservados pela Anthropic. Já vêm no app Claude.
- **Skills nativas do Claude Code** (code-review, simplify, loop, schedule etc.): já vêm com o Claude Code.

## Como usar

Copie a pasta da skill para `~/.claude/skills/` e o agente para `~/.claude/agents/`. Para plugins completos, o ideal é instalar pelo marketplace oficial de cada projeto. Exemplo:

```bash
/plugin marketplace add affaan-m/ECC
```

## Aviso

Este repositório só redistribui o conteúdo, respeitando a licença de cada projeto. Se você é autor de algum item e quer remoção ou correção de crédito, abra uma issue.
