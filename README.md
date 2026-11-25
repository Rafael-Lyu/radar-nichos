# Radar de Nichos Dark

Encontra canais do YouTube que postaram nos últimos dias, com muitas visualizações e poucos inscritos, agrupados por nicho.

Acesse: https://rafael-lyu.github.io/radar-nichos

Roda 100% no navegador usando a YouTube Data API v3. A chave da API é colada na tela e fica guardada só no seu navegador; ela não é enviada para este repositório nem para nenhum servidor além do Google.

## Modo OutLanguage

Na troca "Radar de canais / OutLanguage", no topo do formulário, o modo OutLanguage compara o mesmo nicho em vários idiomas (inglês, português, espanhol, francês, alemão) e aponta onde ele é forte num idioma e fraco em outro.

Para cada nicho e idioma, busca os vídeos de 4 minutos ou mais mais vistos do período (Shorts nunca entram) e separa:

- **nativos**: o idioma original do vídeo é o idioma buscado;
- **dublados**: canal de outro idioma com título ou áudio traduzido;
- **estrangeiros**: o resto.

Muitos views em dublagens e poucos nativos = o público existe, mas ninguém produz direto naquele idioma. Custa ~200 unidades de cota por nicho e idioma.
