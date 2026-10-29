# Modulistica Psicologo (app)

Dashboard com os 6 módulos e 120 modelos, busca, download direto (Word e PDF), favoritos e agenda.

## Estrutura
- index.html: o aplicativo
- documenti/1 a documenti/6: arquivos .docx e .pdf de cada módulo
  (nome exato de cada arquivo em LISTA-ARQUIVOS.txt)
- manifest.webmanifest, sw.js, icon.svg: permitem instalar como aplicativo no celular

## Publicar no GitHub Pages
1. github.com > New repository > nome (ex: modulistica) > Public > Create.
2. "uploading an existing file" > arraste TODO o conteúdo desta pasta > Commit changes.
3. Settings > Pages > Source: Deploy from a branch > Branch: main / (root) > Save.
4. Em 1 a 2 minutos o link aparece no topo da página Pages.
5. Cole esse link na área de membros da Hotmart.

## Adicionar documentos depois
Envie os arquivos para a pasta do módulo (Add file > Upload files) com o nome exato da LISTA-ARQUIVOS.txt.
Enquanto um arquivo não existir, o app mostra "Questo modello è in aggiornamento".
