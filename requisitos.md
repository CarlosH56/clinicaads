#Requisitos funcionais para o sistema de Clínica Médica

RU1 - Quero cadastrar os médicos
RF1 - O sistema deve permitir o cadastro de médicos com os seguintes dados: nome completo, data de nascimento, sexo CRM, especialidade, disponibilidade, CPF

RU2 - Quero cadastrar os pacientes
RF2 - O sistema deve permitir o cadastro de pacientes com  os seguintes dados: nome completo, data de nascimento, sexo, CPF, convenio 

RU3 - Quero agendar uma consulta
RF3 - O sistema deve permitir o agendamento de consulta para os pacientes com os seguintes dados: dia disponível, horário disponível e médico disponível

RU4 – Quero visualizar os médicos cadastrados
RF4 – O sistema deve permitir a listagem e a busca de médicos cadastrados, com filtros por nome, CRM e especialidade.

RU5 – Quero editar os dados de médicos ou pacientes
RF5 – O sistema deve permitir a edição dos dados de médicos e pacientes já cadastrados.

RU6 – Quero excluir um médico ou paciente do sistema
RF6 – O sistema deve permitir a exclusão de registros de médicos e pacientes.

RU7 – Quero visualizar as consultas agendadas
RF7 – O sistema deve permitir visualizar uma agenda de consultas, podendo filtrar por dia, médico e paciente.

RU8 – Quero desmarcar uma consulta
RF8 – O sistema deve permitir o cancelamento de uma consulta previamente agendada.

RU9 – Quero registrar o atendimento do paciente
RF9 – O sistema deve permitir registrar o atendimento realizado, com campos como: diagnóstico, procedimentos realizados, receita médica e observações.

RU10 – Quero cadastrar convênios médicos
RF10 – O sistema deve permitir o cadastro, edição e exclusão de convênios médicos, associando-os aos pacientes.

#Requisitos não funcionais para o sistema de Clínica Médica

RNF1 – Segurança
O sistema deve garantir a segurança dos dados dos pacientes e médicos, utilizando criptografia para senhas e acesso restrito por níveis de usuário (ex: recepcionista, médico, administrador).

RNF2 – Usabilidade
O sistema deve ter uma interface amigável e intuitiva, permitindo que usuários com pouca experiência em informática possam utilizá-lo com facilidade.

RNF3 – Performance
O sistema deve responder a qualquer ação do usuário em no máximo 3 segundos para operações básicas como cadastro, consulta e agendamento.

RNF4 – Disponibilidade
O sistema deve estar disponível para uso no horário comercial da clínica, das 7h às 19h, com no mínimo 99% de uptime.

RNF5 – Backup e Recuperação
O sistema deve realizar backup automático dos dados diariamente, com possibilidade de recuperação em caso de falhas ou perda de dados.

RNF6 – Compatibilidade
O sistema deve ser compatível com os principais navegadores web (Chrome, Firefox, Edge) e dispositivos móveis (smartphones e tablets).

RNF7 – Escalabilidade
O sistema deve suportar o aumento gradual de usuários, consultas e cadastros sem perda significativa de desempenho.

RNF8 – Manutenibilidade
O sistema deve ser desenvolvido com código modular e documentado para facilitar futuras manutenções e atualizações.

RNF9 – Legalidade e Privacidade
O sistema deve estar em conformidade com as normas de proteção de dados pessoais (como a LGPD no Brasil), garantindo a privacidade das informações dos pacientes.

#Requisitos de Software 
RS1 - O sistema deve funcionar no Windowns
RS2 - O sistema deve funcionar na Internet 
RS3 - O sistema deve funcionar no celular e redimensionar automaticamente
RS4 – Criptografia de Dados Sensíveis: Dados como senhas e CPF devem ser armazenados com criptografia para garantir a segurança.
RS5 – Backup Automático: O sistema deve executar backups automáticos diários dos dados armazenados no banco.
