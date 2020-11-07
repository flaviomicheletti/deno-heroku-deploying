# Deployando Deno no Heroku

Tenha o Deno e o Heroku Cli instalados.

Você precisará se logar no Heroku pelo terminal:

    heroku login

Crie uma pasta qualquer, denttro dela inicialize um repositório git:

    git init

Recrie os arquivos `app.ts` e `Procfile` deste repositorio.

Adicione e "commite":

    git add .
    git commit -m "troque por sua mensagem"

Crie o app no Heroku:

    heroku create --buildpack https://github.com/chibat/heroku-buildpack-deno.git

Publique sua aplicação:

    git push heroku master

### Heroku

Minha aplicação ficou aqui https://lit-castle-11378.herokuapp.com/


### Tutorial no youtube

Assista este vídeo apra entender como fazer https://youtu.be/XWQv3II8BvM

Faltou explicar um detalhe no vídeo, veja como ficou meu painel, após ter feito o push:

![heroku-detalhe](https://user-images.githubusercontent.com/1257048/98451992-f9028600-2129-11eb-9270-44a09d7150ca.png)


### Links

- [Deploy your first Deno Web App to Heroku](https://youtu.be/yXH8VFLh2yA)
- https://github.com/chibat/heroku-buildpack-deno
- https://github.com/chibat/heroku-deno-getting-started