# NATIVE PROGRAMS FROM WINDOWS 10

Estes .batch files desinstalam os programas nativos que vem instalados com o Windows 10.
Basta executá-los como administrador que ele realizará automaticamente o processo de desinstalação.

-----------------------------------------

*O que cada arquivo desinstala?*

Os arquivos que realiza `desinstalação` de programas são:
    
    - default.bat
    - cortana.bat
    - cortana-store.bat
    - cortana-sticky-notes.bat
    - cortana-store-xbox.bat

## DEFAULT.BAT
O arquivo `default.bat` desinstala:
    - 3DBuilder
    - Print3D
    - Windows Camera
    - Skype
    - Microsoft Solitaire Collection
    - BingFinance
    - BingWeather
    - BingNews
    - BingSports
    - Microsoft One Note
    - Windows Phone
    - Your Phone
    - Wallet
    - OfficeHub
    - Windows FeedbackHub
    - Windows Maps
    - Get Started
    - Sound Recorder
    - Get Help
    - Windows Alarms
    - Disney+
    - Mixed Reality Portal
    - Evernote
    - Facebook
    - RandomGames
    - DropboxOEM

>>>RECOMENDADO: Ideal para aqueles que querem excluir os programas nativos do Windows 10, deixando o computador um pouco mais leve. Ideal para usuários casuais e que podem estar com um pouco de receio de utilizar o executável

Os demais arquivos são a adição de `default` + `titulo`.
Exemplo: cortana.bat é adição de `default` + `desinstalação da Cortana`.

-----------------------------------------------------------------------

## CORTANA.BAT
Desinstala todos os `default` + desinstalação da `CORTANA`.

>>>RECOMENDADO: Este executável é idêntico a versão default, a diferença é que nesta versão do executável, é removido também a Cortana, Assistente Virtual do Windows 10. 

-----------------------------------------------------------------------

## CORTANA-STORE.BAT

Desinstala todos os programas presentes em `cortana.bat` + desinstalação da `Microsoft Store`

>>>RECOMENDADO: Ideal para aqueles que querem deixar o computador mais leve, remover a Cortana e sabe muito bem que não vai utilizar nada que a Microsoft Store tem a oferecer. Este executável age como o anterior, tendo um diferencial que remove a Microsoft Store. Recomendado para usuários que sabem muito bem que tipos de programas irão utilizar na máquina.

-----------------------------------------------------------------------

## CORTANA-STICKY-NOTES.BAT

Desinstala os programas de `cortana.bat` + desinstalação de `Notas Autoadesivas`

>>> RECOMENDADO: A utilização para quem quer otimizar ao máximo a utilização do Windows 10, eliminando todo e qualquer tipo de programa nativo. Instalando apenas o que se acha necessário. Ideal para quem utiliza o computador para jogos e deseja manter a Microsoft Store

-----------------------------------------------------------------------

## CORTANA-STORE-XBOX.BAT
Desinstala os programas de `cortana-store.bat` + desinstalação de todos os programas associados a `XBOX`

>>> RECOMENDADO: A utilização do `cortana-store-xbox.bat` é só recomendada para computadores que não serão utilizados para fins de lazer (Jogos) pois a desinstalação de alguma das propriedades -XBOX- pode acarretar em problemas relacionados a FPS (Frames per Second) em vários jogos. Pois o programa XBOX não realiza apenas o link da plataforma (PC x XBOX) mas também otimiza os jogos que estão rodando no computador, até hoje utilizei este executável apenas nos computadores da empresa onde trabalho assim que realizo a formatação.

------------------------------------------------------------------------

## EXCLUIR STORE E REINSTALAR STORE

Pode acontecer de eventualmente você sentir a necessidade de desinstalar ou re-instalar a `Microsoft Store`, por isto, está separado dois arquivos executáveis que realizam apenas estas funções. 
É bem possível que o Re-Instalar Store dê algum problema na execução. Caso não consiga, apenas executando o arquivo, edite ele como bloco de notas, abra o powershell como administrador e cole tudo que está dentro das aspas depois de -command

-------------------------------------------------------------------------

### CONSIDERAÇÕES FINAIS

É bem possível que ao finalizar a instalação, você note que alguns programas que deviam ter sido desinstalados ainda estão presentes. Mas calma, não se assuste. 

O executável que mostra no Menu Iniciar é de `instalação` ou seja, o programa será instalado ao clicar nele, para tirá-lo, clique com o direito em cima e clique em `Desinstalar`. Note que ele nem fará nenhum carregamento, apenas irá sumir do `Menu Iniciar`.

Com isto, finalizado.