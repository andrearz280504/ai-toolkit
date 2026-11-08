---
name: lancamento-financeiro
description: Use quando eu mandar um gasto, uma entrada ou uma conta por áudio ou mensagem curta ("gastei 32 no mercado") para lançar na planilha financeira e no app do Breno.
---

# Lançamento financeiro

## Contexto
A planilha do Breno existe em dois lugares: o app/site oficial e uma cópia no Google Sheets, com as colunas Data, Entrada, Saída, Diário e Saldo. Os dois precisam ficar sempre iguais.

## Passos
1. Identifique valor, data (hoje, se eu não disser), descrição e forma de pagamento.
2. Classifique:
   - gasto do dia a dia → coluna **Diário**
   - conta fixa ou parcela → coluna **Saída**
   - dinheiro recebido → coluna **Entrada**
3. Lance na aba do ano certo, no bloco do mês e na linha do dia.
4. Replique o mesmo lançamento na plataforma do Breno.
5. Confirme em uma linha.

## Regras
- "Gastei" sem detalhe significa pix ou débito na hora.
- Se eu disser crédito ou pix crédito, registre a forma de pagamento.
- Se o valor não estiver claro, pergunte antes de lançar.
- Nunca altere lançamentos antigos sem eu pedir.

## Formato da resposta
`Lançado: {VALOR} em {COLUNA}, {DATA}. Saldo do dia: {SALDO}.`
