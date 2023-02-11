# Square Cloud - Arquivo de configuração
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/876871715593011231/1060941671828820069/Erro.png">
</p>

Erros comum como este na imagem acima, impede você de hospedar suas aplicações na Square Cloud devido a ausencia do arquivo de configuração (**que é um arquivo obrigatório**), e muitos acabam não tendo o conhecimento de como cria-lo (mesmo após a leitura da documentação).

**Neste tutorial, você vai aprender como obter o arquivo de configuração de forma fácil e sem medir esforços para fazer um!**

- `Não basta apenas criar sua aplicação no portal de desenvolvedores do Discord e achar que magicamente seu bot ficará online`, você precisa possuir os arquivos de seu bot (também conhecido como source) e a Square Cloud deixará seu bot 24 horas 7 dias na semana online, **desde que não haja erros em seu código, abuso de request ou uso execessivo de memória RAM que seu plano suporta.**
> **Com o plano gratuito da Square Cloud você pode hospedar um bot de 256 MB de RAM ou dois bots com 128 MB cada!**
1. Baixe o arquivo de configuração para você hospedar suas aplicações na Square Cloud:
<br />![Alt](https://cdn.discordapp.com/emojis/899029262319890482.png?size=20) Para bots em **JavaScript** [clique aqui](https://cdn.discordapp.com/attachments/876871715593011231/1060953347970052157/squarecloud.app) para fazer o download.
<br />![Alt](https://cdn.discordapp.com/emojis/899848336000053248.png?size=20) Para bots em **TypeScript** [clique aqui](https://cdn.discordapp.com/attachments/876871715593011231/1060952913846997092/squarecloud.app) para fazer o download.
<br />![Alt](https://cdn.discordapp.com/emojis/899029744484495471.png?size=20) Para bots em **Python** [clique aqui](https://cdn.discordapp.com/attachments/876871715593011231/1060953987341357186/squarecloud.app) para fazer o download.
> No próprio arquivo de configuração você pode por opção alterar as seguintes informações:
> <br />MAIN=para alterar o nome do arquivo principal (se necesário)
> <br />MEMORY=para alterar a memoria que sua aplicação precisa (se necessário) - Mínimo é 100.
> <br />VERSION=para alterar a versão (se necessário). Saiba sobre as versões disponíveis [clicando aqui](https://docs.squarecloud.app/suporte/como-hospedar#versoes-disponiveis-e-recomendadas).

**<br />Se você precisar de mais memória RAM que o plano gratuito abrange, adquire um plano [clicando aqui](https://squarecloud.app/plans).**

- Para você que deseja hospedar um website na Square Cloud:
<br />![Alt](https://cdn.discordapp.com/emojis/899029262319890482.png?size=20) Para website em **JavaScript** [clique aqui](https://cdn.discordapp.com/attachments/876871715593011231/1060962482782474340/squarecloud.app) para fazer o download.
<br />![Alt](https://cdn.discordapp.com/emojis/899848336000053248.png?size=20) Para website em **TypeScript** [clique aqui](https://cdn.discordapp.com/attachments/876871715593011231/1060964722851205160/squarecloud.app) para fazer o download.
> Neste caso, no próprio arquivo de configuração você deve alterar as seguintes informações:
> <br />MAIN=para alterar o nome do arquivo principal (se necesário)
> <br />START=para a rota conforme no seu website (se necessário)
> <br />MEMORY=para alterar a memoria que sua aplicação precisa (se necessário) - Mínimo é 512.
> <br />SUBDOMAIN=colocando o subdominio que deseja utilizar e mantendo o squareweb.app | Para dominio personalizado, é necessário configura-lo no Cloud Flare e solicitar o mesmo no atendimento ao Square Mail.
> <br />VERSION=para alterar a versão (se necessário). Saiba sobre as versões disponíveis [clicando aqui](https://docs.squarecloud.app/suporte/como-hospedar#versoes-disponiveis-e-recomendadas).

**<br />Para que você possa hospedar um website na Square Cloud, é preciso possuir um plano pago, adquire um plano [clicando aqui](https://squarecloud.app/plans).**

3. Feito o download do arquivo de configuração, **você deve compactar todos os arquivos de sua aplicação juntamente com o arquivo de configuração** que você acabou de realizar o download (conforme a imagem abaixo).
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/876871715593011231/1060958834669137960/compactar.png">
<br />O formato do arquivo compactado deve ser em .zip
</p>

> - Caso não possua um programa de compactação de arquivos, procure por WinRar na internet ou outro de sua confiança.
> - Caso você esteja utilizando o celular para realizar os procedimentos, veja tutoriais na internet de como compactar arquivos pelo celular.
4. Depois do arquivo compactado, basta hospeda-lo utilizando o comando `/up` no servidor do Discord no canal **#💻┃commands** (conforme a imagem abaixo).
<p align="center">
  <img src="https://cdn.discordapp.com/attachments/876871715593011231/1060970073898106910/hospedar.png">
</p>
<p align="center">Em caso de dúvidas, utilize os canais de suporte do servidor oficial da Square Cloud!
</p>

**README feito por: Tigmo#0001**
