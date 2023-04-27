Release Plan 

Funcionalidade de Login para Agendamentos de Consultas Médicas On-line

Guilherme Alves Soares - RA: 22.01540-0

User Story:
Como usuário do site de agendamentos de consultas médicas on-line, quero poder realizar login em minha conta para agendar, reagendar ou cancelar consultas de forma segura e prática.

Tarefas Técnicas e Story Points:

Implementar o formulário de login (3 story points):

Criar a estrutura do formulário de login com campos para e-mail/username e senha.
Adicionar validações de entrada nos campos do formulário.
Implementar a lógica de autenticação do usuário.

Integrar com o sistema de autenticação (5 story points):

Configurar o sistema de gerenciamento de usuários e autenticação existente ou escolher uma solução de terceiros confiável.
Realizar a integração entre o formulário de login e o sistema de autenticação.
Implementar a lógica de verificação de credenciais e geração de tokens de autenticação.

Personalização do perfil do usuário (2 story points):

Criar uma página de perfil do usuário onde ele possa visualizar e atualizar suas informações pessoais, como nome, endereço, telefone, etc.
Implementar a funcionalidade de edição de perfil, permitindo que o usuário atualize suas informações.

Recuperação de Senha (Story Points: 3)

Adicionar a funcionalidade de recuperação de senha.
Implementar um fluxo de redefinição de senha seguro, com envio de e-mail de redefinição.
Criar a página de redefinição de senha com campos de entrada e verificação.

Medição de Prioridade Rice:

Reach (alcançar):
As tarefas técnicas descritas são relevantes para todos os usuários do sistema, tornando o Reach alto.

Impact (impacto):
As tarefas descritas permitem que os usuários acessem informações importantes, agendem consultas e gerenciem suas contas, portanto, o Impacto é alto.

Confidence (confiança):
A equipe tem experiência em autenticação e autorização de usuários, portanto, a Confiança é alta.

Effort (esforço):
O Effort varia de acordo com a tarefa, mas no geral, considerando a experiência da equipe, pode ser considerado moderado.

Usando a fórmula Rice, a prioridade para cada tarefa pode ser calculada como:

Prioridade = (Reach x Impact x Confidence) / Effort

Integrar com o sistema de autenticação
Prioridade = (5 x 5 x 4) / 5 = 20

Criar a página de perfil do usuário:
Prioridade = (5 x 4 x 4) / 3 = 26.67

Implementar a autorização de acesso:
Prioridade = (5 x 5 x 4) / 5 = 20

Recuperação de Senha
Prioridade = (5 x 4 x 4) / 5 = 20

Conclusão:
Com base na medição de prioridade Rice, a tarefa mais importante é criar a página de perfil do usuário, seguida pela configuração da autenticação do usuário e pela implementação da autorização de acesso. Portanto, a equipe deve se concentrar na criação da página de perfil do usuário como a primeira tarefa a ser concluída.







