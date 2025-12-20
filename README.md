# BOT ATENDENTE (Whatsapp)

Este projeto consiste em um sistema de automação desenvolvido no n8n, integrando WhatsApp e IA (OpenAI/Gemini) para transformar o atendimento de prestadores de serviços (salões, clínicas, consultórios) em uma experiência 100% autônoma.

## Funcionalidades Principais:
### Cliente 👤: 
- Saudação personalizada baseada no horário e identificação automática via número de telefone.

- Agendamento Automatizado.

- Fluxo de escolha de data e hora com verificação de conflitos.

- Seleção de Múltiplos Serviços.

 - Checkout & Pagamento:

    - Opção de pagamento antecipado via PIX.

   - A IA analisa o comprovante enviado pelo cliente e valida o pagamento automaticamente.

- Gestão de Cancelamento: 

  - Se a solicitiaçãpo estiver fora do prazo, o bot informa a retenção do valor ou taxa adicional futura.
    

### Painel do Prestador (Dono) 👩‍💼:
- Briefing Matinal (07:30) - Envio automático da agenda do dia, pagamentos pendentes e reembolsos a fazer.

- Gestão de Dúvidas (Transbordo):

   - Sistema de "Responder Agora" ou "Depois".

   - Encaminhamento inteligente de respostas para o cliente.

   - Regra de 3 tentativas: Caso a dúvida persista, o bot transfere para o contato humano direto.

- Bloqueio de Agenda: O prestador pode definir dias/horários como indisponíveis, e o bot automaticamente notifica e oferece remanejamento para os clientes afetados.
  

### Automações Ativas ⏰:
- Lembrete de Véspera: Mensagem automática para confirmação de presença (Sim/Não).

- Notificações em Tempo Real: Avisos imediatos de novos agendamentos ou cancelamentos.
