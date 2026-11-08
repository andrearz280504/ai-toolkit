---
name: alertas-de-carteira
description: Use para analisar vendas de clientes recorrentes (oficinas, revendas) e apontar quem esfriou, quem está em atenção e quem está crescendo.
---

# Alertas de carteira

## Entrada
Planilha de vendas de 12 meses: data, pedido, cliente (código), vendedor, valor líquido.

## Regras de leitura
- Datas no padrão brasileiro (dd/mm/aaaa) e valores como 1.250,40.
- Conte pedidos distintos, não linhas.
- Ignore linhas repetidas, canceladas e devoluções.

## Status
Compare cada cliente com o **próprio** intervalo médio de compra e com a média de 12 meses, nunca com os outros.
- **Fria**: passou bem do próprio intervalo sem comprar
- **Atenção**: comprou abaixo da própria média
- **Ativa**: dentro do ritmo
- **Em alta**: acima da própria média

## Saída
Para cada alerta, uma frase de motivo que o vendedor entenda, o telefone e a última compra.
Nenhum alerta sem motivo escrito.
