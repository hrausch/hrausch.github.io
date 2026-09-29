# hrausch.github.io

Página pessoal de Herbert Rausch. HTML estático em um único arquivo, sem build.

## Arquivos

- `index.html` – a página, com o CSS embutido (procure por `TODO` para ver o que falta preencher)
- `CNAME` – domínio próprio: herbertrausch.com.br
- `assets/photo.jpg` – sua foto (formato retrato 4:5, 560x700 px)

## Publicar

1. Crie um repositório **público** chamado exatamente `hrausch.github.io`.
2. Envie estes arquivos para a branch `main`.
3. Repositório → Settings → Pages → Source: *Deploy from a branch* → `main` / root.
4. Settings → Pages → Custom domain: `herbertrausch.com.br`; marque *Enforce HTTPS* quando a opção aparecer.

## DNS (no registrador de herbertrausch.com.br)

Domínio raiz, quatro registros `A`:

    185.199.108.153
    185.199.109.153
    185.199.110.153
    185.199.111.153

`www`: um registro `CNAME` apontando para `hrausch.github.io`.

Para o futuro site de aulas (Docusaurus), crie um registro `CNAME` para `aulas`
apontando para `hrausch.github.io` e publique o repositório do Docusaurus com o
domínio `aulas.herbertrausch.com.br`. Depois é só adicionar uma seção "Aulas" na página.
