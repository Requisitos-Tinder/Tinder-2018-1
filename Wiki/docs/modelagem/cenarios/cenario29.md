# Congelar Conta

<br />

|Título|[Congelar Conta](/modelagem/lexicos#congelar-conta)|
|-----|------------|
|**Objetivo**|Manter a conta sem mostrá-la para outros [usuários](/modelagem/lexicos#usuario), apenas as configurações de [perfil](/modelagem/lexicos#perfil) podem ser acessadas pelo [usuário](/modelagem/lexicos#usuario).|
|**Contexto**|**Pré-condição:** O [usuário](/modelagem/lexicos#usuario) deve possuir um [perfil](/modelagem/lexicos#perfil) e estar logado.<br/>**Pós-condição:** A conta do [usuário](/modelagem/lexicos#usuario) terá sido [congelada](/modelagem/lexicos#congelar-conta) e estará oculta para outros [usuários](/modelagem/lexicos#usuario).|
|**Atores**| [Usuário](/modelagem/lexicos#usuario) [Sistema](/modelagem/lexicos#tinder)|
|**Recursos**|Acesso à Internet|
|**Episódios**|1. O [usuário](/modelagem/lexicos#usuario) [acessa as configurações](/modelagem/cenarios/cenario39.md).<br/>2. O [usuário](/modelagem/lexicos#usuario) desliza a página até a opção deletar conta.<br/>3. O [usuário](/modelagem/lexicos#usuario) seleciona deletar conta.<br/>4. O [usuário](/modelagem/lexicos#usuario) escolhe a opção [congelar a minha conta](/modelagem/lexicos#congelar-conta).<br/>5. O [sistema](/modelagem/lexicos#tinder) abre a tela principal.<br/>6. O [sistema](/modelagem/lexicos#tinder) exibe a [mensagem](/modelagem/lexicos#mensagem) ‘Seu [cartão](/modelagem/lexicos#cartao) está oculto’.<br/>7. O [sistema](/modelagem/lexicos#tinder) exibe opção de ativar [descoberta](/modelagem/lexicos#descoberta).|
|**Restrições**|O fluxo não ser intuitivo|
|**Exceção**|1. A internet pode cair durante a execução da ação.<br/>2. O [usuário](/modelagem/lexicos#usuario) pode fechar a [aplicação](/modelagem/lexicos#tinder) antes de completar a ação.|
