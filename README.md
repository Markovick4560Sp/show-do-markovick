# Show do Markovick

Quiz de 69 perguntas no estilo de rede social, feito em um único arquivo HTML.

## Como editar
Abra `index.html` e procure o bloco **EDITE AQUI** no começo do `<script>`:
- `PERGUNTAS`: texto, opções e resposta certa (`certa: 0` = primeira opção)
- `AMIGAS`: nomes de quem sopra a resposta
- `USOS`: quantas vezes cada ajuda pode ser usada
- `MENSAGEM_FINAL`: texto que aparece no fim

## Publicar
Site estático, sem build. Na Vercel: Add New Project → importar este repositório → Framework Preset: **Other** → Deploy.
