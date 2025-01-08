# bike-service
Ciclistas:
 Cadastro com tipo de bicicleta e histórico de manutenção.
 Busca por oficinas próximas com base em geolocalização.
 Solicitação de orçamento.
 Pagamento integrado.
 Avaliação da oficina.

Oficinas:
 Cadastro de serviços oferecidos e preços.
 Agenda para marcações.
 Recebimento de solicitações e interação com clientes.

Admin
Painel para acompanhar transações e usuários.
Definir e aplicar percentuais sobre serviços pagos.




Ciclistas: Tabela com informações sobre os ciclistas (nome, email, telefone, etc.).
Oficinas: Contém dados sobre as oficinas de bicicletas (nome, endereço, horário de funcionamento, avaliação média, etc.).
Serviços: Contém os serviços oferecidos pelas oficinas (revisões, ajustes, preços, etc.).
Agendamentos: Relaciona os ciclistas, oficinas e serviços, incluindo a data, hora e status do agendamento.
Pagamentos: Registra os pagamentos feitos pelos ciclistas, incluindo o valor pago, método e status do pagamento.
Comissões: Armazena a comissão cobrada pela plataforma sobre cada pagamento feito.
Relacionamentos:
Ciclistas têm agendamentos em Oficinas, e cada agendamento é associado a um Serviço.
Cada Agendamento está associado a um Pagamento.
A Comissão é calculada com base no Pagamento.
Índices:
Os índices são criados nas colunas frequentemente consultadas para melhorar o desempenho, como os campos de email, status de agendamentos e pagamentos, e a data de agendamentos.
