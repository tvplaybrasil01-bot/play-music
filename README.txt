# PLAY MUSIC — versão inicial

## O que está incluído
- Interface responsiva para celular e computador
- Pesquisa local nas faixas demonstrativas
- Filtros por estilo musical
- Favoritos temporários na sessão atual
- Estrutura PWA (manifest, ícone e service worker)

## Importante
Esta versão é apenas a estrutura visual inicial. As faixas são demonstrativas e não reproduzem áudio. Ainda não há catálogo de streaming conectado, nem login, sincronização de favoritos ou playlists persistentes.

## Próxima etapa
Escolher e configurar uma fonte autorizada de streaming (por exemplo, uma API de catálogo independente que permita esse uso), respeitando as condições da API e as licenças de cada faixa. Só depois disso habilitaremos os botões de reprodução real.

## Testar
Hospede os arquivos em um host estático com HTTPS. Depois abra o endereço no Android. Em navegadores compatíveis, use o menu do navegador e escolha "Adicionar à tela inicial" / "Instalar app".
