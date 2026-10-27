# Publicação no Cloudflare Pages

Endereço público principal: https://mahara-dev.pages.dev/

Projeto: `mahara-dev`. Publicado por upload direto em 27/10/2026, na conta Cloudflare da proprietária. Nenhum plano pago ou domínio pago foi contratado.

## Atualizar o site

1. Na pasta `portfolio`, execute `npm run build`.
2. Crie um ZIP com o conteúdo da pasta `dist`, com `index.html` na raiz do ZIP.
3. No painel Cloudflare, abra Compute → Workers & Pages → mahara-dev.
4. Crie uma nova implantação de produção, envie o ZIP e publique.
5. Confira https://mahara-dev.pages.dev/.

Exemplo de empacotamento no PowerShell, executado na pasta `portfolio`:

```powershell
Compress-Archive -Path 'dist/*' -DestinationPath '../mahara-cloudflare.zip' -Force
```

O pacote inclui apenas o site compilado e suas imagens. Não envie `node_modules`, `.git`, credenciais ou todo o código-fonte ao upload direto.

O projeto usa upload direto; não há atualização automática por GitHub. A publicação antiga no Sites continua separada. Ao fazer futuras atualizações destinadas ao endereço principal, publique também no projeto Cloudflare acima.
