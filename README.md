# Editando Repositório

Apenas edite os conteúdos na pasta source/

### Posts
Crie um arquivo dentro da pasta **source/posts** com o nome da pagina e extensão .md: **pagina-do-vitim.md**

No inicio do arquivo coloque o header:

```
---
title: Atributos e Habilidades
author: Vitor Lima
date: 2017-11-16 07:12:03
thumbnail: /images/indexes/atributos.jpg
categories:
  - Sistemas
---
```

thumbnail é a imagem que aparecerá no post. Você encontrará na pasta source/images um arquivo .psd para manter o padrão das imagens.


### Páginas
Para criar uma nova página crie uma pasta com o nome dela em **source/** e, dentro dela, uma outro arquivo chamado index.md

A página deve conter no seu inicio.

```
---
title: Downloads
date: 2017-05-26 02:05:18
---
```

title será o nome da página.

# Imagens
Imagens devem ser adicionadas na pata **source/images**.

Crie pastas caso queira organizar.

Para referenciar elas dentro do markdown use:
![](/images/nome_da_imagem.png)

# Subindo para o Repositório
Após instalar o github e clonar o repositório com **git clone https://github.com/vitorfdl/flsblog.git**

Digite **git checkout -b seu_usuario**
Isso criará uma nova branch para que você possa editar. O seu usuário deve ser um nome simples, sem acentos ou espaços.

Para pegar as ultimas atualizações dessa branch, digite sempre que quiser:
**git pull origin master**

Para enviar para estra branch commite suas mudanças com:
**git add -A**
**git commit -m "seus comentários aqui"
**git push origin seu_usuario**

Após enviar as mudanças, entre no site, acesse sua branch
https://github.com/vitorfdl/flsblog/tree/seu_usuario

E clique em **New pull request**, preencha e submeta.

