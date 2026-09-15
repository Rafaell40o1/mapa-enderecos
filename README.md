# Mapa do eleitorado do estado do Rio de Janeiro

Versão publicada: lista de locais ampliada, filtros recolhíveis e recuperação de 437 dos 492 endereços inicialmente pendentes. Há 4.985 locais publicados. Os 55 pendentes de coordenadas foram excluídos desta publicação e preservados nos arquivos locais para uma atualização futura. Os pontos recuperados são classificados como aproximados, com indicação de estabelecimento, endereço simplificado, rua, CEP, bairro ou cadastro escolar. Referências de bairro não representam a posição da escola. Links das fontes externas estão nas fichas quando disponíveis.

5.040 locais de votação, 92 municípios e 12.857.388 eleitores aptos, conforme as planilhas fornecidas com referência em 18/08/2026.

Filtros combináveis por município, bairro, zona eleitoral, mínimo/máximo de eleitores por local, mínimo de seções e precisão da localização. Inclui busca, ordenação, exportação CSV dos resultados e perfil municipal de idade, sexo, escolaridade e deficiência registrada.

O número de eleitores não representa alunos, capacidade ou ocupação da escola. Um local é identificado pela combinação município + zona + número do local; locais que compartilham um endereço permanecem separados. Os totais municipais são conferidos com a planilha de resumo. Perfis municipais não são atribuídos individualmente às escolas e não mudam com os filtros de local.

Geocodificação automática: pontos aproximados são destacados; registros sem coordenadas foram omitidos desta publicação. Novas coordenadas exigem município correspondente e tipo de resultado de endereço, rua ou estabelecimento, além de pontuação mínima. Coordenadas anteriormente obtidas para endereços iguais foram reutilizadas.

## Arquivos e publicação

Site estático: `index.html`, `app.css`, `app.js` e `dados/*.js`. Os dados são carregados por scripts para permitir também a abertura local, sem servidor. Não exige compilação. Precisa de internet para Leaflet e o mapa Esri.

GitHub Pages: branch `main`, pasta `/(root)`. A entrada `estado.template.html` é o modelo local de geração; não é necessária na publicação.

Fontes integradas: locais (02), resumo municipal (03), seções (04) e perfis municipais (09–12). Outros relatórios fornecidos apresentam agregações complementares e não são somados aos eleitores por local.

Verificações de filtros e integridade podem ser executadas abrindo `index.html?test=1`: o título retorna `TESTS PASS` quando todas passam.
