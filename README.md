# Casa Intencional — site

Site estático (HTML + CSS, sem build).

- `index.html`: página inicial (dobras 1 a 4).
- `sobre-nos.html`, `cursos.html`, `mentorias.html`, `blog.html`: subpáginas.
- `assets/site.css`: menu, ícones das redes sociais, rodapé e estilos das subpáginas (compartilhado por todas as páginas).
- `assets/`: logo, ramo e fotografias.

Conteúdo pendente aparece marcado com a etiqueta **A DEFINIR** (classe `a-definir`). Ao colocar o texto real, remova o `<span class="a-definir">`.
Links das redes sociais: procurar `data-rede="youtube|instagram|tiktok"` e trocar `href="#"` pelo endereço do perfil.

## Publicar na Cloudflare Pages

Conecte este repositório em Cloudflare Pages com:
- Framework preset: None
- Build command: (vazio)
- Build output directory: `/`
