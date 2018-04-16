# Congelar Conta

<br />

|Título|Congelar Conta|
|-----|------------|
|**Objetivo**|Manter a conta sem mostrá-la para outros usuários, apenas as configurações de perfil podem ser acessadas pelo usuário.|
|**Contexto**|**Pré-condição:** O usuário deve possuir um perfil e estar logado.<br/>**Pós-condição:** A conta do usuário terá sido congelada e estará oculta para outros usuários.|
|**Atores**| Usuário Sistema|
|**Recursos**|Acesso à Internet|
|**Episódios**|1. O usuário abre o aplicativo.<br/>2. O usuário abre a aba perfil.<br/>3. O usuário clica em configurações.<br/>4. O usuário desliza a página até a opção deletar conta.<br/>5. O usuário seleciona deletar conta.<br/>6. O usuário escolhe a opção congelar a minha conta.<br/>7. O sistema abre a tela principal.<br/>8. O sistema exibe a mensagem ‘Seu cartão está oculto’.<br/>9. O sistema exibe opção de ativar descoberta.|
|**Restrições**|O fluxo não ser intuitivo|
|**Exceção**|1. A internet pode cair durante a execução da ação.<br/>2. O usuário pode fechar a aplicação antes de completar a ação.|
