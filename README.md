# Pro Sport RS — Landing Page de Esteiras

Landing page premium com foco em **captura de leads via WhatsApp** para a linha de
esteiras (residencial, semiprofissional e profissional) da Pro Sport RS.

Público-alvo: Porto Alegre, Grande POA, Serra e Litoral. Comunicação técnica e
consultiva, posicionando a Pro Sport como especialista em esteiras.

## Estrutura

- `index.html` — página completa (HTML + CSS + JS embutidos, sem dependências de build).
- `img/` — imagens dos produtos, logo e favicon.

Basta hospedar `index.html` e a pasta `img/` na raiz do domínio. Não há back-end,
build nem formulário — **todos os CTAs levam para o WhatsApp**.

## Contato / CTAs

- WhatsApp / telefone: **(51) 3103-3650** → links `https://wa.me/555131033650`
- E-mail: **contato_site@prosportrs.com.br**
- Instagram: `@prosportfitnessstore` · Facebook: `/prosportrs`

Cada botão de WhatsApp já vai com uma mensagem pré-preenchida de contexto
(linha do produto, ficha técnica, região etc.), o que ajuda a qualificar o lead.

## Área de depoimentos — vídeo do personal Délcio

A seção **Depoimentos** (`#depoimentos`) tem um card de vídeo marcado como
"em edição · em breve". Quando o vídeo do Délcio estiver pronto, substitua o
bloco `<div class="video-card">` pelo embed. Há um comentário no HTML, logo
abaixo do card, com o exemplo pronto:

```html
<div class="video-card">
  <iframe src="https://www.youtube.com/embed/VIDEO_ID"
    style="position:absolute;inset:0;width:100%;height:100%;border:0"
    title="Depoimento do personal Délcio" allowfullscreen></iframe>
</div>
```

Para acrescentar depoimentos de texto no futuro, é só duplicar os cards `.mini`
da coluna lateral (`.testi-side`) com as frases reais dos clientes.

## Imagens

Os arquivos foram renomeados para nomes web-safe (minúsculos, com hífen, sem
espaços) para evitar problemas de deploy em servidores Linux. Ao adicionar
novas fotos, siga o mesmo padrão, ex.: `embreex-568-prof.jpg`.

## Identidade visual

- Vermelho da marca `#e11414` · azul-marinho `#151965` · fundo dark `#0b0c0f`
- Tipografia: Montserrat (títulos), Inter (texto), Bebas Neue (destaques)

Tema escuro e editorial para transmitir o nível premium dos equipamentos, com
os produtos apresentados em cards claros (efeito "vitrine").
