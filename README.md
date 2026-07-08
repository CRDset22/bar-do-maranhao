# Bar do Maranhão

Site institucional de um bar temático nordestino em São Paulo, especializado em
pratos com camarão. Página única feita com **HTML e CSS puro**, com seção
"Sobre o bar", cardápio em imagens, formas de pagamento aceitas, formulário de
contato e links de redes sociais.

## Tecnologias

- HTML5
- CSS3 (Flexbox)
- Google Fonts: Dancing Script e Great Vibes

## Como abrir

Não é preciso instalar nada. Abra o arquivo `index.html` no navegador
(clique duas vezes ou arraste para uma aba).

## Estrutura da pasta

```
bar-do-maranhao/
├── index.html        estrutura e conteúdo da página
├── main.css          estilos e layout
├── README.md         este arquivo
├── fluxograma.svg    diagrama dos arquivos do projeto
└── imagens/          todas as imagens usadas no site
```

Todas as imagens ficam na subpasta `imagens/`, e o HTML aponta para elas com
caminhos como `./imagens/nome-do-arquivo`.

## Observações sobre esta organização

Ao mover as imagens para a pasta `imagens/`, alguns ajustes foram feitos no
`index.html` para tudo continuar funcionando:

- Todos os caminhos de imagem passaram a começar com `./imagens/`.
- O link do Instagram apontava para `instagram.png.webp`, mas o arquivo real
  chama-se `instagram_png.webp` — o caminho foi corrigido, senão o logo não
  apareceria.
- Duas descrições `alt` estavam trocadas entre si (a imagem de bebidas dizia
  "camarão com chocolate" e vice-versa); foram acertadas.

No CSS, as imagens do cardápio (`.cardapio img`) agora têm todas a mesma
dimensão: **260 x 100**. Foi usado `object-fit: cover` para que elas preencham
esse tamanho sem esticar nem achatar a foto.

### Imagens de reserva (não usadas no site)

Estão na pasta, mas o `index.html` não as utiliza no momento:

- `galo-imagem-receitas-macarrao-com-camarao-share.jpg`
- `youtube-logo-hd-8.png` (o site usa a versão `.jpg`)

Pode apagá-las se quiser, ou usá-las depois.

---

Projeto de estudo de front-end.
