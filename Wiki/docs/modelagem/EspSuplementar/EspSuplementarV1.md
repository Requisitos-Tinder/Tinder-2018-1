# Especificação Suplementar V1
<br />

## Finalidade:
<p align="justify">&emsp;
Esta especificação suplementar busca tratar os requisitos não-funcionais não capturados pelos casos de uso.
</p>

<br />
## Escopo:
<p align="justify">&emsp;
Esta especificação suplementar se aplica ao sistema do Tinder, em um estudo sobre modelagem de requisitos.
</p>
<p align="justify">&emsp;
O Tinder é um aplicativo de relacionamento no qual pessoas avaliam outras pessoas por meio de fotos e breves descrições. Possibilitando posteriormente a interação entre pessoas que se avaliaram positivamente.
</p>

<br />
## Usabilidade:

#### Linguagem de fácil entendimento:
<p align="justify">&emsp;
A linguagem utilizada em todas as telas e funcionalidades do sistema deve se encaixar no vocabulário do perfil de usuário mais comum que, de acordo com o questionário, são pessoas com idade de 18 à 25 anos.
</p>

#### Interface intuitiva e de fácil compreensão:
<p align="justify">&emsp;
As telas do sistema devem possuir poucas opções de navegação, tornando-as simples e fáceis. As opções de navegação assim como os demais botões devem estar dispostos de maneira a minimizar riscos. Ex: botão de assinar serviço pago deve ser distante do botão de deletar conta.
Ícones devem ser claros em relação à seus objetivos.
</p>

<br />
## Confiabilidade:

#### Segurança ao guardar os dados do usuário:
<p align="justify">&emsp;
Os dados do usuário referentes à autenticação e relacionamento com outras pessoas dentro do Tinder devem ser privados e consequentemente bem protegidos na base dados da empresa.
</p>
#### Segurança ao realizar a integração com as redes sociais (Facebook, Instagram, Spotify):
<p align="justify">&emsp;
Ao solicitar integração de seu perfil com algum outro sistema, apenas os dados do sistema a ser integrado deverão ser importados, de forma que nenhuma informação sobre o comportamento ou se quer a existência de um usuário no tinder.
</p>

<br />
## Desempenho:
#### Tempo mínimo de resposta entre cada perfil avaliado:
A atividade de avaliar perfil consiste em arrastar cards para o lado direito ou esquerdo em caso de like ou deslike respectivamente. Logo é necessário que outro card substitua o card que foi arrastado para o lado. Caso o tempo de carregamento desse novo card seja lento, a principal tela do aplicativo se tornaria inútil durante esse tempo, piorando significativamente a experiência do usuário.
		Medidas de tempo?


#### Tempo mínimo de respostas quando houver o match:
<p align="justify">&emsp;
A tela que notifica o usuário que o match aconteceu, deve aparecer rapidamente e de forma invasiva, pois ela representa o objetivo da principal função do sistema(avaliar perfis) ser alcançado. Com isso o usuário tem noção em tempo real das consequências de suas avaliações.
</p>

<br />
## Compatibilidade:
#### Suporte à plataforma Android:
<p align="justify">&emsp;
Deve existir uma versão estável e otimizada para dispositivos móveis que utilizam o sistema operacional Android.
</p>

#### Suporte à plataforma IOS:
<p align="justify">&emsp;
Deve existir uma versão estável e otimizada para dispositivos móveis que utilizam o sistema operacional IOS.
</p>

#### Suporte à plataforma Web:
<p align="justify">&emsp;
O sistema deve ser acessível em navegadores web por meio de uma versão específica para eles.
</p>
#### Compatibilidade com versões de browser (Google Chrome, Mozilla Firefox, etc):
<p align="justify">&emsp;
O sistema deve se comportar de forma idêntica em qualquer navegador web comum.
</p>

#### Compatibilidade com versões de sistemas operacionais móveis:
<p align="justify">&emsp;
O sistema deve estar disponível para diversas versões de um sistema operacional como Android ou IOS. Deve-se levar em conta as limitações das versões mais antigas, que ocasionaram em diferenças entre versões do Tinder. Limitações do sistema operacional que interfiram de forma significativa nas principais funções do Tinder terão como consequência a não existência de uma versão do tinder para esta versão do sistema operacional.
</p>

<br />
## Restrições de Design?:

<br />
## Interfaces de Comunicações:
Interface de comunicação com o facebook, instagram e spotify?

<br />
## Padrões aplicáveis:
<p align="justify">&emsp;
Paleta de cores?
</p>
<p align="justify">&emsp;
As cores predominantes nas telas são: Tons de Laranja, branco e cinza. Detalhes em Verde claro, azul claro, roxo, amarelo e dourado.
</p>
<p align="justify">&emsp;
Navegação entre páginas por meio de abas.
</p>

<br />
## Requisitos de Licenciamento

#### Licenças presentes no sistema:
Apache 2.0:
- Google Play Services
- Android InApp Billing v3
- Facebook Android SDK
- GSON
- OkHTTP
- okio
- libphonenumber
- EventBus
- Dagger
- AndroidSVG
- SVG-Android
- Volley
- Glide
- ViewPageIndicator
- RxAndroid
- Retrofit
- Android Image Cropper
- LicensesDialog

Stetho
Rebound
StreamSupport
