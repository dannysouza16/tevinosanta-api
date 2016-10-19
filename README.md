# Te vi no Santa - API

Projeto Open source feito por alunos do 2º ano do curso de Sistemas de informação da Unisanta.

### O que é?
O aplicativo te vi no santa é app que alunos da faculdade podem tirar fotos de outros alunos que tem interesse de conhecer, postando a foto em nossa timeline sendo anonimos. Se a pessoa da foto for reconhecida é aberto um chat para os dois conversarem.

### Pontos importantes
- A pessoa que postou a foto recebe notificações de comentários e curtidas feitas na foto que ele postou
- Quando uma pessoa mandar um “Sou eu” na foto que foi postada. O usuario que postou recebe uma notificação para ele identificar a pessoa  (Pelas fotos de perfil) e dar o SIM ou NÃO. Se aquela é a pessoa da Foto. Se ele digitar SIM o Chat abre para os dois conversarem.
- O post pode ou não ser anonimo. Depende do usuario escolher, A opção default é anonimo.
- Os post vão contem um botão "Tenho interesse", que quando a pessoa da foto for reconhecia a mesma pode abrir um chat com as que clicarem nesse botão


### API
A API será feita em ASP.NET (C#), futuramente faremos um guia de como conectar onde ele ficará hospedado.
Tutorial de como criar uma API em ASP.NET: http://www.macoratti.net/16/08/aspnc_mvc61.htm

### BD
O banco de dados utilizado será o SQL Server igual das aulas do coletto.

### Como contribuir?
- Dê um fork no projeto
- Vá no repositorio que o git criou e copie a url, digite git clone e cole o link
- git clone https://github.com/seu-nome/tevinosanta-api
- Entre no diretório $ cd tevinosanta-api
- Faça suas alteraçoes
- Crie um branch (ramificação) do projeto:
 - comando que fecha a master: $ git checkout master
 - comando que cria a branch: $ git branch nome-da-branch
 - comando para sincronizar seu fork com o original: $ git remote add upstream https://github.com/dannysouza16/tevinosanta-api.git
- Para subir o projeto:
 - comando que adiciona as alteraçoes feitas: $ git add *
 - comitando a alteração $ git commit -m 'Mensagem sobre a modificação'
 - dando o push no projeto para que seja feito o pull request: git push origin nome-da-branch
- E por ultimo vá até o seu repositório no github (parte gráfica) e faça o pull request.

Guia de git básico: http://rogerdudler.github.io/git-guide/index.pt_BR.html
