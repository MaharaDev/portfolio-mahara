# Mahara — Meu universo criativo ✦

Meu portfólio pessoal: um encontro entre desenvolvimento, criatividade e aprendizado contínuo. A identidade combina roxo, lilás e verde em uma experiência espacial, jovem e interativa.

**[Visite o portfólio](https://mahara-dev.pages.dev/)**

## O que você encontra

- Apresentação e trajetória pessoal.
- Skills com filtros por linguagens, ferramentas e design.
- Projetos em uma órbita horizontal com movimento automático.
- Capas com a identidade dos projetos Lucas Fernando Advogado e Mahara & Lucas.
- Detalhes dos projetos e links para os sites publicados.
- Playground para misturar ideias e explorar possibilidades.
- Atmosferas Cosmos e Aurora, constelações e interações com o cursor.
- Links para WhatsApp, LinkedIn e GitHub.

## Tecnologias

| Tecnologia | Uso neste projeto |
| --- | --- |
| React | Componentes e estados da interface |
| TypeScript | Tipagem do código |
| HTML e CSS | Estrutura, identidade visual e responsividade |
| Motion | Animações e transições |
| Canvas | Constelações animadas |
| Lucide React | Ícones |
| Vite | Desenvolvimento e compilação |
| Cloudflare Pages | Hospedagem do site |

## Executar no computador

Use Node.js 22.12 ou superior, compatível com o Vite 7.

```bash
npm ci
npm run dev
```

Abra o endereço informado pelo terminal. O projeto usa a porta `4173` por padrão.

## Gerar a versão de produção

```bash
npm run build
```

O comando verifica os tipos com TypeScript e gera o site na pasta `dist`.

Para conferir a compilação localmente:

```bash
npm run preview
```

## Organização

```text
public/projects/          Imagens usadas nas capas dos projetos
src/main.tsx             Componentes, conteúdo e interações
src/style.css            Identidade visual e layouts responsivos
index.html               Documento de entrada
CLOUDFLARE.md            Como publicar e atualizar o site
PROJECT-TECHNOLOGIES.md   Registro das tecnologias dos projetos externos
```

## Acessibilidade e movimento

O site respeita a preferência de movimento reduzido do dispositivo. A órbita dos projetos interrompe o avanço durante interação, foco por teclado ou abertura dos detalhes. Os diálogos aceitam Escape e devolvem o foco ao botão de origem. As constelações suspendem a animação fora da área visível e em abas em segundo plano.

## Publicação

O endereço principal é **https://mahara-dev.pages.dev/**. A publicação no Cloudflare Pages usa upload direto do conteúdo compilado de `dist`. Confira o passo a passo em [CLOUDFLARE.md](CLOUDFLARE.md).

Este repositório não está conectado a uma publicação automática: enviar alterações ao GitHub não atualiza o site sozinho.

## Projetos apresentados

- [Meu universo digital](https://mahara-dev.pages.dev/)
- [Lucas Fernando Advogado](https://lucasfernandoadv.com.br/)
- [Mahara & Lucas — Casamento](https://mahara-lucas.web.app/)
- [Chamexx Entregas](https://chamexxentregas.com.br/)

As tecnologias dos sites externos foram identificadas nos arquivos públicos. As fotografias e identidades visuais pertencem aos respectivos projetos; sua presença neste repositório não concede autorização geral de reutilização.

## Vamos nos conectar

- [LinkedIn](https://www.linkedin.com/in/erikamahdev/)
- [GitHub](https://github.com/MaharaDev)
- [WhatsApp](https://wa.me/5547999327163)

Feito de código, curiosidade e um pouco de mim. Em evolução. Sempre. ♡