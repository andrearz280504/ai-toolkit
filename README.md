# ai-toolkit

Skills e agentes que eu criei e uso todos os dias com o Claude, para marketing, criação, finanças e produto.

Cada skill é uma rotina que ensina o Claude a fazer uma tarefa sempre do mesmo jeito. Cada agente é o Claude com papel, regras e conhecimento fixos para um tipo de trabalho.

## Skills

| Skill | Para quê | Projeto |
|---|---|---|
| [`lancamento-financeiro`](skills/lancamento-financeiro/SKILL.md) | Transforma um áudio ("gastei 32 no mercado") em lançamento na planilha e no app | Planilha financeira |
| [`carrossel-de-marca`](skills/carrossel-de-marca/SKILL.md) | Do briefing a um carrossel de 10 páginas no padrão da marca | Agente de design |
| [`revisao-de-marca`](skills/revisao-de-marca/SKILL.md) | Confere cor, fonte, margem, texto e tom de voz página por página | Agente de design |
| [`decupagem-de-video`](skills/decupagem-de-video/SKILL.md) | Ideia → roteiro em 3 atos → decupagem com prompts de imagem e vídeo | Paz Energy |
| [`alertas-de-carteira`](skills/alertas-de-carteira/SKILL.md) | Classifica clientes recorrentes em fria, atenção, ativa e em alta | Contagiro |
| [`criar-skill`](skills/criar-skill/SKILL.md) | Transforma uma tarefa que se repete em uma skill nova | Todos |

## Agentes

| Agente | Função |
|---|---|
| [Agente de design](agents/agente-de-design.md) | Designer sênior de cada marca, treinado com o kit de marca |
| [Agente financeiro](agents/agente-financeiro.md) | Lança gastos por áudio e mantém planilha e app iguais |
| [Diretor de vídeo](agents/diretor-de-video.md) | Roteiro, decupagem e prompts para comerciais com IA |

## Skills de terceiros que eu mais uso

Marketing: `campaign-plan`, `content-creation`, `brand-review`, `competitive-brief`, `performance-report`, `seo-audit`
Design: `design-critique`, `ux-copy`, `design-system`, `frontend-design`
Vendas: `proposal-builder`, `lead-finder`, `social-content-engine`
Dados: `build-dashboard`, `analyze`, `create-viz`
Documentos: `pptx`, `docx`, `xlsx`, `pdf`

## Como usar

Copie a pasta da skill para a pasta de skills do Claude (ou envie como skill na sua conta) e chame pelo nome. Os textos entre `{CHAVES}` são variáveis que você preenche.

Portfólio com os estudos de caso: https://claude.ai/artifact/RVnCRWnWzQ53mZzV4Uoz56
