# VERA PC — Vegetação

Mapa operacional para identificar rapidamente pontos de vegetação dentro dos trechos urbanos de Porto Nacional, usando imagem de satélite.

## Base de trechos

Na primeira abertura, clique em **Carregar KMZ** e selecione o arquivo consolidado de Porto Nacional. O aplicativo lê apenas as linhas dos trechos urbanos, descartando postes e chaves, e mantém a base salva neste navegador.

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

## Uso rápido

1. Abra o site publicado no GitHub Pages.
2. Clique em **Carregar KMZ** e selecione a base consolidada, somente na primeira vez neste navegador.
3. Filtre os alimentadores desejados no painel à esquerda.
4. Clique sobre a vegetação no mapa satélite. O app associa o ponto ao alimentador e trecho mais próximos.
5. Preencha tipo, prioridade e observação; depois exporte os registros em GeoJSON ou CSV.

Os pontos são salvos localmente no navegador. Use **Exportar pontos** ou **Exportar CSV** ao fim da vistoria para manter uma cópia externa e consolidar em outro equipamento.

## Publicação

No repositório, habilite GitHub Pages em **Settings → Pages**, selecionando a branch `main` e a pasta `/ (root)`.
