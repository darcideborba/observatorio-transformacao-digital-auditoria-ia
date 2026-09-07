# Template — Tratamento dos achados de uma auditoria por IA

> Modelo genérico para registrar, de forma rastreável, como cada achado de uma auditoria metodológica por IA (ver `PROMPT_AUDITORIA_IA.md`) foi tratado pela equipe de pesquisa. Preencha uma linha por achado, na ordem em que aparecem no relatório de auditoria.

Referência: relatório de auditoria de [data]. Tratamento aplicado em [data] nas versões `_vN` dos documentos afetados.

| Nº | Achado (síntese) | Decisão | Tratamento aplicado |
|---:|---|---|---|
| 1 | [Descreva o achado, ex.: divergência de contagem entre texto e planilha] | Acatado / Acatado em parte / Não aplicado (justificado) | [Descreva a correção feita, o documento e a versão onde foi aplicada, e a fonte primária consultada quando aplicável] |
| 2 | ... | ... | ... |

## Convenções de decisão

- **Acatado**: o achado procede integralmente; a correção foi aplicada e verificada contra fonte primária quando possível.
- **Acatado em parte**: o achado procede parcialmente; parte da recomendação foi aplicada e parte permanece como ressalva registrada no texto, por depender de nova evidência ou de decisão colegiada.
- **Não aplicado (justificado)**: o achado é registrado, mas a ação recomendada não foi executada nesta rodada, com justificativa explícita (por exemplo, orientação da coordenação, escopo fora do mandato dos pesquisadores, ou pendência de decisão de terceiros).

## Observações finais (modelo)

Registre aqui: (a) o parecer geral da auditoria (por exemplo, "revisão necessária") e se foi integralmente endereçado pelos itens acima; (b) pendências que permanecem em aberto por dependerem de decisão colegiada ou de terceiros; (c) qualquer re-checagem ou pedido complementar já agendado, com a data prevista.
