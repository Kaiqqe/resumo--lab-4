Resumo do Lab: Identidade, Acesso e Segurança na Nuvem (Azure)

Durante esse laboratório, aprofundei conceitos essenciais relacionados à identidade, controle de acesso e segurança na nuvem, com foco no Azure. Abaixo, minhas principais lições:

Principais conceitos aprendidos

Azure Active Directory (Azure AD)
Entendi que o Azure AD é o serviço central de identidade na nuvem da Microsoft, usado para gerenciar usuários, grupos, permissões e autenticação em serviços Azure e aplicações.

Autenticação e Autorização
Diferenciação entre autenticar (confirmar quem é) e autorizar (definir o que pode fazer).
Uso de políticas de controle de acesso baseado em função (Role-Based Access Control, RBAC) para conceder permissões mínimas necessárias.

Identidade gerenciada (Managed Identities)
Aprendi que recursos no Azure (como VMs ou funções) podem ter identidades gerenciadas nativas para se autenticarem em outros serviços sem guardar segredos ou chaves manualmente.

Multifator de autenticação (MFA) e Proteção de Senhas
Importância de usar MFA para reforçar a segurança e políticas de senha forte.
Implementação de políticas que exigem renovação de senha, bloqueio de conta e proteção contra ataques de força bruta.

Políticas de segurança e compliance
Criação de restrições e diretrizes para garantir que os recursos na nuvem sigam práticas seguras (por exemplo, exigência de criptografia, exigência de uso de TLS/SSL).

Controle de acesso condicional (Conditional Access)
Definição de condições (localização, dispositivo, risco de login) para permitir ou bloquear acesso a recursos e aplicações.

Logs, auditoria e monitoramento de segurança
Importância de rastrear eventos de autenticação, falhas de login, alterações de permissão — como parte de estratégia de segurança e governança.

Aplicações práticas no laboratório

Configuração de um diretório no Azure AD

Criação de usuários e grupos com permissões específicas

Aplicação de políticas de RBAC em recursos

Habilitação de MFA para contas

Uso de identidades gerenciadas para autenticar recursos

Definição de políticas condicionais para reforçar segurança

Monitoramento de logs de acesso e auditoria

Importância desse conhecimento

Trabalhar com identidade e acesso de forma correta é crítico para garantir que apenas os usuários ou serviços legítimos possam interagir com recursos na nuvem. Falhas nessa camada costumam ser porta de entrada para muitos ataques.
Esse laboratório contribuiu para que eu entenda melhor como arquitetar sistemas seguros, com permissões restritas, rastreabilidade e mecanismos automáticos de controle — habilidades essenciais para qualquer ambiente corporativo em nuvem.
