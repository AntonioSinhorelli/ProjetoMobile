# *Funcionalidade:* Reservar Quadras

Como* um morador do condomínio
*Para* saber quais das e horários as quadras estão vagas para reservas
*Eu quero* reservar uma quadra para uso exclusivo

*Cenário 1:* Reserva de quadra
*Dado que* estou conectado na conta de morador
*E* entrei na aba de reserva de quadras
*E* escolheu a quadra desejada junto com os dados e horário
*Quando* eu clicar em confirmar, exibe junto o Pagamento
*Então* eu pago e a reserva está confirmada

*Cenário 2:* Cancelamento de reserva de quadra
*Dado que* estou conectado na conta de morador
*E* tenho uma reserva de quadra já confirmada
*Quando* eu acesso uma lista de minhas reservas e selecione a opção de cancelar
*Então* o sistema solicita a confirmação do cancelamento
*E* após confirmar, a reserva é cancelada
*E* o horário da quadra volta a ficar disponível para outros moradores
