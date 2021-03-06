# Configuração de Descoberta

<br />

|Título|Configuração de [Descoberta](/modelagem/lexicos#descoberta)|
|------|--------------------------|
|**Objetivo**|Configurar as preferências do [usuário](/modelagem/lexicos#usuario) em relação aos [perfis](/modelagem/lexicos#perfil) que serão exibidos para ele.|
|**Contexto**|**Pré-condições:**<br />1. O [usuário](/modelagem/lexicos#usuario) deve possuir um [perfil](/modelagem/lexicos#perfil) e estar _logado_.<br />2. O [usuário](/modelagem/lexicos#usuario) deve permitir o uso de sua [localização](/modelagem/lexicos#localizacao) atual <br />**Pós-condição:**<br />1. Somente serão mostrados ao [usuário](/modelagem/lexicos#usuario), [pessoas](/modelagem/lexicos#usuario) que se enquadrem nas escolhas dele.|
|**Atores**|1. [Usuário](/modelagem/lexicos#usuario).<br />2. [Sistema](/modelagem/lexicos#tinder).|
|**Recursos**|1. Acesso à Internet.<br />|
|**Episódios**|1. O [usuário](/modelagem/lexicos#usuario) [acessa as configurações](/modelagem/cenarios/cenario39.md).<br />2. O [usuário](/modelagem/lexicos#usuario) [desliza](/modelagem/lexicos#swipe) a página até a seção de configuração de [descoberta](/modelagem/lexicos#descoberta).<br />3. O [usuário](/modelagem/lexicos#usuario) define a [localização](/modelagem/lexicos#localizacao) dele.<br />4. O [sistema](/modelagem/lexicos#tinder) pede autorização para utilizar a [localização](/modelagem/lexicos#localizacao) atual do [usuário](/modelagem/lexicos#usuario).<br />5. O [usuário](/modelagem/lexicos#usuario) permite esse uso.<br />6. O [usuário](/modelagem/lexicos#usuario) define a [distância máxima](/modelagem/lexicos#distancia-maxima) das [pessoas](/modelagem/lexicos#usuario) que serão mostradas a ele.<br />7. O [usuário](/modelagem/lexicos#usuario) escolhe o [gênero](/modelagem/lexicos#genero) dessas [pessoas](/modelagem/lexicos#usuario).<br />8. O [usuário](/modelagem/lexicos#usuario) escolhe a [faixa etária](/modelagem/lexicos#faixa-etaria) delas.<br />9. O [usuário](/modelagem/lexicos#usuario) escolhe se quer ou não que seu [perfil](/modelagem/lexicos#perfil) apareça para outras [pessoas](/modelagem/lexicos#usuario).<br />10. O [usuário](/modelagem/lexicos#usuario) seleciona a opção _Ok_ para salvar suas alterações.<br /> 11. A tela volta para a aba de [perfil](/modelagem/lexicos#perfil).|
|**Restrições**|Fluxo intuitivo.|
|**Exceção**|1. O [usuário](/modelagem/lexicos#usuario) sai do [aplicativo](/modelagem/lexicos#tinder) antes que essas modificações sejam efetivadas.<br />2. A internet cai no meio da execução da ação.|
