# Deletar Conta

<br />

|Título|Deletar Conta|
|------|-------------|
|**Objetivo**|Excluir o [perfil](/modelagem/lexicos#perfil) do [usuário](/modelagem/lexicos#usuario) e todos os dados associados a ele.|
|**Contexto**|**Pré-condição:** O [usuário](/modelagem/lexicos#usuario) deve possuir um [perfil](/modelagem/lexicos#perfil) e estar _logado_.<br />**Pós-condição:** O [perfil](/modelagem/lexicos#perfil) do [usuário](/modelagem/lexicos#usuario) não existirá mais.|
|**Atores**|1. [Usuário](/modelagem/lexicos#usuario).<br />2. [Sistema](/modelagem/lexicos#tinder).|
|**Recursos**|Acesso à Internet.|
|**Episódios**|1. O [usuário](/modelagem/lexicos#usuario) abre o [aplicativo](/modelagem/lexicos#tinder).<br />2. O [usuário](/modelagem/lexicos#usuario) seleciona aba [perfil](/modelagem/lexicos#perfil).<br />3. O [usuário](/modelagem/lexicos#usuario) seleciona a opção de configurações.<br />4. O [usuário](/modelagem/lexicos#usuario) desliza a tela até a opção deletar conta.<br />5. O [sistema](/modelagem/lexicos#tinder) exibe a tela de desativar.<br />6. O [usuário](/modelagem/lexicos#usuario) escolhe a opção de excluir minha conta.<br />7. O [sistema](/modelagem/lexicos#tinder) exibe a tela de deletar conta.<br />8. O [usuário](/modelagem/lexicos#usuario) escolhe o motivo da exclusão da conta.<br />9. O [sistema](/modelagem/lexicos#tinder) mostra a [mensagem](/modelagem/lexicos#mensagem) de confirmação para excluir a conta.<br />10. O [sistema](/modelagem/lexicos#tinder) deleta a conta.<br />11. O [sistema](/modelagem/lexicos#tinder) exibe uma [mensagem](/modelagem/lexicos#mensagem) confirmando a exclusão da conta.|
|**Restrições**|Fluxo intuitivo.|
|**Exceção**|1. A internet cai durante a execução da ação.<br />2. O [usuário](/modelagem/lexicos#usuario) sair do [aplicativo](/modelagem/lexicos#tinder) antes de terminar a execução da ação.|
