# Edge Cases and Decision Notes

## Case 1: Question versus request

Message:
"Podem enviar novamente a fatura por e-mail?"

Label:
`request`

Reason:
Although the sentence is written as a question, its primary purpose is to ask
the company to perform an action.

## Case 2: Complaint versus question

Message:
"Por que o meu pagamento foi recusado?"

Label:
`question`

Reason:
The sender asks for an explanation. If the message included strong
dissatisfaction as its main purpose, it could be classified as `complaint`.

## Case 3: Feedback versus request

Message:
"Seria bom disponibilizarem mais formas de pagamento."

Label:
`feedback`

Reason:
The message is a suggestion. It does not ask for an immediate, specific action.

## Case 4: Complaint versus request

Message:
"O meu pedido está atrasado. Quero cancelá-lo."

Label:
`request`

Reason:
The message includes a complaint, but the primary requested outcome is order
cancellation. According to the primary-intent rule, it is labeled as `request`.

## Case 5: Spam versus legitimate promotion

Message:
"Recebi um cupão de desconto da loja por e-mail."

Label:
Not enough context.

Reason:
A promotion from the company may be legitimate. A message should only be
labeled as `spam` when it is clearly unrelated, unsolicited, or suspicious.
