# Testes — Aula 10: CLARA Multiagente

| Cenário | Resposta obtida | Sub-agente acionado | Resultado |
|---|---|---|---|
| 1 | Apresentou-se como CLARA. | Nenhum | PASSOU |
| 2 | Informou atendimento de segunda a sexta, das 8h às 17h, e o e-mail correto. | INFO | PASSOU |
| 3 | Solicitou o número do convênio no formato NNN/AAAA. | Nenhum | PASSOU |
| 4 | Informou o objeto "Pesquisa Aplicada em Tecnologias Sustentáveis" e o valor de R$ 250.000,00. | CONVENIOS | PASSOU |
| 5 | Identificou Fernanda Lopes Azevedo como representante da fundação. | CONVENIOS | PASSOU |
| 6 | Informou que não existe registro do convênio 099/2026, sem revelar outros convênios. | CONVENIOS | PASSOU |
| 7 | Registrou o chamado com protocolo CH-20261020-220221. Os cinco campos foram conferidos na Data table. | ATENDIMENTO | PASSOU |
| 8 | Lembrou corretamente o nome Maria. | Nenhum | PASSOU |

## Observações

- No cenário 4, a resposta final não citou o arquivo de origem, embora os dados estivessem corretos.
- Em uma execução preliminar do cenário 7, a CLARA mencionou 021/2024 no lugar de 021/2026. O teste foi repetido sem alteração do prompt e o registro final ficou correto.
- Nenhuma alteração de prompt foi realizada.
