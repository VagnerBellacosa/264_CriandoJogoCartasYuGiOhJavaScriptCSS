# 264_CriandoJogoCartasYuGiOhJavaScriptCSS
 Criando um Jogo de Cartas do Yu-Gi-Oh! com JavaScript e CSS



- CONTEÚDOS
- INFORMAÇÕES

###### DESCRIÇÃO

Vamos recriar um jogo do Yu-Gi-Oh utilizando as mecânicas de jogo do Jo-Ken-Po, vamos explorar conceitos avançados de organização de states com Javascript puro, estruturação de arquivos e criação de funções reaproveitáveis

**JavaScript****HTML****CSS**

------

###### Front-End

###### Avançado

------

###### ESPECIALISTA

![author](https://hermes.dio.me/users/author/photos/e0aa7c57-89e3-41ff-a60b-09dc7a9bc6e9.jpg)

###### Felipe Aguiar

Tech Educator, DIO[**](https://www.linkedin.com/in/felipe-aguiar-047/) [**](https://github.com/felipeAguiarCode)



https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/2d295397-04a9-4479-8610-42ddd482009d

[**](https://web.dio.me/track/potencia-tech-ifood-desenvolvimento-de-jogos)

##### Criando um Jogo de Cartas do Yu-Gi-Oh! com JavaScript e CSS

**

[**](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/0fc07a85-eeb0-4243-96ab-9bb11008c239)[**](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/703e0628-e377-48bf-a0a7-c153b5897091)

<iframe id="ytc20" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="Configurando o Projeto Base" width="100%" height="100%" src="https://www.youtube.com/embed/J5QcVt5Bq2k?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-19="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



06:33

 

13:03









normal

auto

- CONTEÚDOS
- INFORMAÇÕES

[Introdução](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/0fc07a85-eeb0-4243-96ab-9bb11008c239)[Configurando o Projeto Base](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/2d295397-04a9-4479-8610-42ddd482009d)[Estruturação geral](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/703e0628-e377-48bf-a0a7-c153b5897091)[Vídeo de fundo](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/179ce291-e43f-4179-bf0b-afe7b8238ac8)[Finalizando o Container Left](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/ea6d1996-5810-4cac-8c32-6c144aee159f)[Construindo o container right](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/970854e3-4f36-42c5-82f1-a36455b0ea8c)[Demarcando os elementos do container right](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/8852f7c7-094a-46b3-9c95-c53f2aa2a254)[Terminando de estilizar componentes visuais](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/643992f0-2c26-461c-9c42-2be4e0a31bec)[Criando os states da engine](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/856550d6-2e3c-48b4-997e-19ee32f93163)[Criando a enumeração de cartas](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/5e452885-ed1f-4b85-8fbc-9780e48e605d)[Criando assinatura das funções principais](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/d50da974-02fa-490d-9678-31f50c8b95b6)[Implementando a lógica de setar cartas em campo](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/2af64a53-5bfa-41f0-9f3d-3a0ffd30423a)[Ajustando o caminho dos recursos](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/3a1241ca-2f06-4d98-9dec-0849e9ae3a56)[Implementando o mouseover](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/fe46af41-2cca-4cd7-bddc-de31eb4ff8d8)[Implementando o setCardFields](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/83301130-63bf-4803-ae52-902026018478)[Implementando o removeAllCardsImages](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/125a82dd-9b5e-43bf-87dd-9cd1e5fc9a03)[Implementando a lógica de duelos](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/87510da9-db5a-4726-8b1d-b9fe060c9104)[Implementando Efeitos sonoros](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/acf9f274-e818-4215-ac21-36871808d4fa)[Refatorando a tela de versus](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/f8451a0a-15d4-4f42-ae72-725f3cd82833)[Aprendendo a Técnica de Extract to Method](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/32e8000a-c0af-4dc3-abbc-5e42d9738293)[Adicionando um FavIcon](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/2ad71f7a-452f-48b8-a72a-f6d50dcc1a50)[Adicionando cursores personalizados](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/fb342336-1a66-4451-8cb3-d63b70f2c15f)[Colocando uma música de fundo (BGM)](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/03b46b89-ab16-45e3-b165-3781df6dd43a)[Até o próximo Duelo](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/e0745a18-23b0-4a54-9302-186a02c02e75)[Entendendo o Desafio](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/4ea66946-9497-47f7-a85c-849d860e8f65)



#####  Criando um Jogo de Cartas do Yu-Gi-Oh! com JavaScript e CSS

**

[**](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/e0745a18-23b0-4a54-9302-186a02c02e75)[**](https://web.dio.me/lab/criando-um-jogo-de-cartas-do-yu-gi-oh-com-javascript-e-css/learning/undefined)

# Entendendo o Desafio

 

🎯 **AGORA É A SUA VEZ**
Chegou a hora de colocar em prática tudo aquilo que você aprendeu durante esse projeto.

👨‍💻 **OBJETIVO:**
Sua missão vai ser reproduzir passo passo o projeto visto nessa aula, ao final
suba seu projeto no Github e compartilhe conosco clicando no botão "Entregar Projeto" e cole o link do seu repositório do Github.

🔗 **Links Úteis**
Sabemos que toda jornada tem seus desafios, por isso separamos alguns links que podem te ajudar durante esse processo:

-> Veja como entregar seu desafio de projeto no Github: https://web.dio.me/lab/conversando-por-voz-com-o-chatgpt-utilizando-whisper-openai-e-python/learning/705acdae-ceb0-4095-8b4d-f5ed76b3ec52
-> Código-fonte deste Desafio de Projeto: https://github.com/digitalinnovationone/js-yugioh-assets

 

Bons estudos 😉



