# novaescentroautomotivo

Site de produção da Novaes Centro Automotivo.

## Publicação na Vercel

1. Importe este repositório na Vercel.
2. Selecione **Other** em Framework Preset.
3. Deixe a Root Directory na raiz do repositório.
4. Deixe o Build Command vazio. O site já foi gerado e minificado.
5. Confirme que o Output Directory é **dist** (também definido em `vercel.json`).

A pasta `dist/` contém o site completo pronto para publicação. Os arquivos fonte e de referência ficam apenas no computador de desenvolvimento.

## Descoberta e compartilhamento

O pacote inclui metadados Open Graph e Twitter, dados estruturados `AutoRepair`, `robots.txt`, `sitemap.xml` e `llms.txt`. A URL canônica atual é `https://novaescentroautomotivo.vercel.app/`. Se um domínio próprio substituir essa URL, atualize os endereços absolutos antes de gerar e publicar um novo pacote.

Depois da publicação, verifique o domínio no Google Search Console e envie `https://novaescentroautomotivo.vercel.app/sitemap.xml`.

## Atualização

Após alterações locais, gere novamente a pasta `dist/`, confira o resultado e envie os novos arquivos ao GitHub. A Vercel publicará apenas `dist/`.
