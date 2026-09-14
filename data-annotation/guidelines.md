# Text Classification Guidelines

## Objective

The objective of this exercise is to classify short Portuguese customer messages
according to their primary intent.

## Labels

### question

Use this label when the sender is asking for information.

Examples:
- "Qual é o horário de funcionamento?"
- "Onde posso acompanhar o meu pedido?"

### complaint

Use this label when the sender reports dissatisfaction, a problem, an error, or
a negative experience.

Examples:
- "O meu pedido ainda não chegou."
- "O produto veio danificado."

### request

Use this label when the sender asks the company to perform an action.

Examples:
- "Quero cancelar a minha encomenda."
- "Por favor, alterem o meu endereço de entrega."

### feedback

Use this label when the sender gives an opinion, suggestion, compliment, or
general comment without asking for action.

Examples:
- "Gostei muito do atendimento."
- "Seria bom disponibilizarem mais formas de pagamento."

### spam

Use this label when the message is unrelated to customer support, promotes an
unrelated service, contains suspicious links, or is clearly unsolicited.

Examples:
- "Ganhe dinheiro rápido. Clique neste link."
- "Promoção de criptomoedas. Envie mensagem agora."

## Decision Rules

1. Read the full message before assigning a label.
2. Assign only one label to each message.
3. Choose the primary intent when a message contains more than one intent.
4. Use `request` when the sender asks the company to take an action.
5. Use `question` when the sender only seeks information.
6. Use `complaint` when dissatisfaction or a problem is the main purpose.
7. Use `feedback` when the sender expresses an opinion or suggestion without
   requesting a specific action.
8. Use `spam` only when the message is clearly unrelated or unsolicited.
9. Do not use personal assumptions that are not stated in the text.
