# VERA PC — Vegetação

Mapa operacional para identificar rapidamente pontos de vegetação dentro dos trechos urbanos de Porto Nacional.

## Base geográfica carregada

A base foi extraída do KMZ consolidado e contém **somente trechos**, sem postes e sem chaves:

| Alimentador | Trechos | km |
|---|---:|---:|
| AL01072001 | 234 | 10,19 |
| AL02072001 | 258 | 11,23 |
| AL03072001 | 127 | 9,32 |
| AL04072001 | 352 | 18,69 |
| AL05072001 | 266 | 13,48 |
| AL06072001 | 321 | 20,29 |
| LD01072001 | 33 | 3,94 |
| LD02072001 | 76 | 8,03 |
| LD03072001 | 48 | 4,80 |
| **Total** | **1.715** | **99,97** |

## Como usar

1. Abra o site publicado no GitHub Pages.
2. Mantenha um ou mais alimentadores visíveis no painel à esquerda.
3. No mapa satélite, clique sobre a vegetação.
4. O aplicativo cria o ponto, associa automaticamente o alimentador e o trecho mais próximo e permite definir tipo, prioridade e observação.
5. Exporte os pontos em GeoJSON ou CSV ao fim da vistoria.

Os registros ficam salvos localmente no navegador. Use **Exportar GeoJSON** ou **Exportar CSV** para garantir cópia externa e consolidar os dados em outro computador.

## Publicação

No repositório, habilite GitHub Pages em **Settings → Pages**, selecionando a branch `main` e a pasta `/ (root)`.
