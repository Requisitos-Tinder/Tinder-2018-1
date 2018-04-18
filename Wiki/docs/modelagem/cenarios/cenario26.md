# Configuração do Perfil Web

<br />

|Título|Configuração do [Perfil Web](/modelagem/lexicos#perfil-web)|
|------|--------------------------|
|**Objetivo**|Criar um [nome de usuário](/modelagem/lexicos#nome-de-usuario) público.|
|**Contexto**|**Pré-condições:** <br/>1. O [usuário](/modelagem/lexicos#usuario) deve possuir um [perfil](/modelagem/lexicos#perfil) e estar logado.<br/>2. O [nome de usuário](/modelagem/lexicos#nome-de-usuario) deve ser único.<br/>**Pós-condições:** <br/>1. O [usuário](/modelagem/lexicos#usuario) possuirá um [perfil web](/modelagem/lexicos#perfil-web) e poderá [compartilhar sua url](/modelagem/lexicos#compartilhar-minha-url).<br/>2. A opção ver meu [perfil web](/modelagem/lexicos#perfil-web) terá aparecido na seção [perfil web](/modelagem/lexicos#perfil-web).<br/>3. A opção [compartilhar minha url](/modelagem/lexicos#compartilhar-minha-url) terá aparecido na seção [perfil web](/modelagem/lexicos#perfil-web).|
|**Atores**|[Usuário](/modelagem/lexicos#usuario).<br/>[Sistema](/modelagem/lexicos#tinder).|
|**Recursos**|Acesso à Internet.|
|**Episódios**|1. O [usuário](/modelagem/lexicos#usuario) [acessa as configurações](/modelagem/cenarios/cenario39.md).<br/>2. O [usuário](/modelagem/lexicos#usuario) desliza a tela até a seção de [perfil web](/modelagem/lexicos#perfil-web).<br/>3. O [usuário](/modelagem/lexicos#usuario) clica na opção de [nome de usuário](/modelagem/lexicos#nome-de-usuario).<br/>4. O [usuário](/modelagem/lexicos#usuario) preenche o campo com o seu [nome de usuário](/modelagem/lexicos#nome-de-usuario).<br/>5. O [usuário](/modelagem/lexicos#usuario) clica em confirmar.<br/>6. O [sistema](/modelagem/lexicos#tinder) verifica se o [nome](/modelagem/lexicos#nome-de-usuario) está disponível.<br/>7. A [aplicação](/modelagem/lexicos#tinder) volta para a tela de configurações.|
|**Restrições** ||
|**Exceção**|1. A internet cair durante a execução da ação.<br/>2. O [usuário](/modelagem/lexicos#usuario) sair do aplicativo sem salvar as modificações.|
