---
layout: post
title:  "Como contribuir!"
date:   2017-03-20 00:43:00 -0200
categories: dicas
author: 'Alan Lira'
author_url: 'http://github.com/lira92'
author_url_label: 'Alan Lira'
author_url_avatar: 'https://avatars3.githubusercontent.com/u/10679262'
comments: true
---

Este é o blog do Google Developer Group Toledo PR, feito usando jekyll e github, ele é escrito em markdown e o jekyll transforma em um html estático, toda alteração deve ser feita via git, no [repositório](https://github.com/GDG-ToledoPR/gdg-toledopr.github.io) do github. O blog fica muito perfomático, pois é todo estático, e evolução do template também, já que os posts escritos em markdown e transformados em html a cada build.

## Quero escrever um artigo

Para escrever um artigo você deve visitar nosso [repositório](https://github.com/GDG-ToledoPR/gdg-toledopr.github.io) e dentro da pasta `_posts` criar um arquivo
no seguinte formato: `YYYY-MM-DD-nome-do-post.markdown`. No seu arquivo escreva seu artigo utilizando markdown, a sintaxe é muito simples e existem até editores online que facilitam essa tarefa.

No topo do arquivo você configura conforme a seguir:

{% highlight plan %}

---
layout: post
title:  "Nome do post"
date:   2017-03-20 00:43:00 -0200
categories: categoria1, categoria2
author: 'Seu Nome'
author_url: 'Seu site pessoal ou github'
author_url_label: 'Texto do link'
author_url_avatar: 'url da imagem do avatar'
comments: true
---

{% endhighlight %}

Caso você queira postar um trecho de código utilize o **code highlight**, conforme o exemplo:

{% highlight typescript %}

export class MinhaClasse {
    
    constructor() {

    }
}

{% endhighlight %}

Depois de escrito seu artigo, envie um pull request e faremos a revisão e indicaremos correções ou melhorias se for necessário.