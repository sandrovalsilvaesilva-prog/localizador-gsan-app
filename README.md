# Consulta de Localização GSAN

Aplicativo local para consultar uma base `.gsan` separada e abrir coordenadas no Google Maps.

## Arquivos principais

- `index.html`: localizador.
- `base-amostra.gsan`: base pequena para teste.
- `manifest.webmanifest`: manifesto para empacotamento como app/PWA.
- `service-worker.js`: cache básico quando publicado por HTTPS, como GitHub Pages.
- `abrir-localizador.bat`: atalho local para abrir no Windows.

## Uso

1. Abra `index.html`.
2. Carregue uma base `.gsan`.
3. Pesquise por matrícula, cliente, endereço, bairro, rota ou sequência.
4. Use `Abrir no Mapa` para abrir a localização no Google Maps.

## Atualização da base

A base não fica embutida no aplicativo. Gere uma nova base `.gsan` no computador e carregue/substitua no localizador.
