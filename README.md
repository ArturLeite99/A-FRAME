# A-FRAME

Experiências de realidade virtual e aumentada com A-Frame.

- `index.html`: cena 3D e página inicial.
- `image-tracking/index.html`: realidade aumentada por deteção de imagem.
- `location/index.html`: realidade aumentada com localização GPS.

## Executar

Abre a pasta do projeto num servidor Web local, por exemplo, através da extensão Live Server do VS Code.

A câmara e a localização exigem uma ligação segura HTTPS; `localhost` também é considerado seguro pelos navegadores. Não abras as páginas diretamente como ficheiros (`file://`).

## Deteção de imagem

A página utiliza uma imagem de referência e necessita também do ficheiro `targets.mind`, compilado a partir dessa imagem com o compilador de alvos do MindAR. Coloca os ficheiros na pasta `image-tracking/assets/`, de acordo com os caminhos definidos em `image-tracking/index.html`.

## Localização

O objeto está configurado para as coordenadas `41.5000, -8.0000`. Para o visualizar noutra localização, altera a latitude e longitude no atributo `gps-new-entity-place` em `location/index.html`.