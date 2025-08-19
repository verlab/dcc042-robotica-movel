# DCC042 - Robótica Móvel

Nesse repositório encontram-se os Jupyter Notebooks e as cenas de simulação do CoppeliaSim utilizados ao longo da disciplina.

## Ementa

História da Robótica. Descrição Espacial e Transformações. Espaço de configurações. Locomoção. Cinemática de robôs móveis. Controle. Navegação. Planejamento de caminhos. Sensores. Localização. Mapeamento. SLAM. Paradigmas robóticos. Sistemas multi-robôs.

## Objetivos

Esta disciplina abordará os principais conceitos de Robótica Móvel. Serão vistos aspectos relacionados à locomoção, navegação, planejamento de caminhos, percepção, localização e mapeamento. Ao final, os alunos devem ser capazes de entender esses conceitos, bem como implementar pequenas aplicações em simuladores e plataformas robóticas reais, além de prosseguir no desenvolvimento de projetos de pesquisa.

## Conteúdo



| Assunto                                       | Aulas             | Jupyter              | CoppeliaSim     |
|:----------------------------------------------|:-----------------:|:--------------------:|:---------------:|
| Apresentação do curso                         |  [Vídeo](https://youtu.be/qWWKAMMnPs8) - [Slides](https://drive.google.com/file/d/16EcZqbMsq4w-gy1JuWJFkCLLmUiSxZv-/view?usp=sharing)  |                    |           |
| História e Atualidades                        |  [Vídeo](https://youtu.be/FtLzd2LY7T4) - [Slides](https://drive.google.com/file/d/14J9dALWPGVY1qzoSx3h9yJYQFTTQYXoc/view?usp=sharing)  |                    |           |
| Ferramental                                   |  [Vídeo](https://youtu.be/Ohrau23GmQk) - [Slides](https://drive.google.com/file/d/1TmWJxVjGy_MqZljqCs07ESk3-qxtkvf3/view?usp=sharing) <br> [Slides (ZeroMQ)](https://drive.google.com/file/d/1JK3L6e6gW5_8ugxl0852i2t--U7WdP58/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula03-ferramental.ipynb) <br>[Notebook (ZeroMQ)](../main/jupyter-notebooks/aula03-ferramental-zmq.ipynb)  |  [Pioneer](../main/cenas-coppeliasim/aula03-pioneer.ttt) <br> [Bill (ZeroMQ)](../main/cenas-coppeliasim/aula03-bill-zmq.ttt) <br> [Pioneer (ZeroMQ)](../main/cenas-coppeliasim/aula03-pioneer-zmq.ttt) |
| Descrição espacial e Transformações rígidas   |  [Vídeo](https://youtu.be/RDUKZt00-oI) - [Slides](https://drive.google.com/file/d/1Ra94gTtL0exznbURIjL_uKL8XHPn1wPY/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula04-descricao-espacial-transformacoes-rigidas.ipynb)  |           |
| Transf. homogêneas e Espaço de configurações  |  [Vídeo](https://youtu.be/lJfxVbuBVkE) - [Slides](https://drive.google.com/file/d/15IFPS6twEb69NhkUpsWVy8iO73KGGfmc/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula05-transformacoes-homogeneas-espaco-configuracoes.ipynb)  |           |
| Locomoção – Conceitos e Mecanismos            |  [Vídeo](https://youtu.be/wNkUOfk5HDw) - [Slides](https://drive.google.com/file/d/1_2BvW8f7oUDA3osTCsvNwyQMdT2Y-5uR/view?usp=sharing)  |                    |           |
| Locomoção – Modelos cinemáticos               |  [Vídeo](https://youtu.be/P1PIQilYliQ) - [Slides](https://drive.google.com/file/d/1tCxXqrZ94_4FyKE8By_-FDkFWlM-3Z3A/view?usp=sharing)  |  [Notebook (Legacy API)](../main/jupyter-notebooks/aula07-locomocao-modelos-cinematicos.ipynb) <br> [Notebook (ZeroMQ)](../main/jupyter-notebooks/aula07-locomocao-modelos-cinematicos-zmq.ipynb)  |  [Robotino](../main/cenas-coppeliasim/aula07-robotino.ttt), [Pioneer](../main/cenas-coppeliasim/aula07-pioneer.ttt)   |
| Controle – Introdução                         |  [Vídeo](https://youtu.be/Y-opiS_gjhk) - [Slides](https://drive.google.com/file/d/18t-rwkNsRynWjjyEvVNsCwFDWUrddkFI/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula08-controle-introducao.ipynb)  |  [Cena](../main/cenas-coppeliasim/aula08-controle-introducao.ttt)  |
| Controle – Cinemático                         |  [Vídeo](https://youtu.be/uAwjyo6P08I) - [Slides](https://drive.google.com/file/d/1EiuDr9O-1pc8rDJHCm_t_o8Age2TWfa3/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula09-controle-cinematico.ipynb)  |  [Robotino](../main/cenas-coppeliasim/aula09-controle-robotino.ttt), [Pioneer](../main/cenas-coppeliasim/aula09-controle-pioneer.ttt)   |
| Paradigmas Robóticos                          |  [Vídeo](https://youtu.be/B15kbEPK0iM) - [Slides](https://drive.google.com/file/d/1kfAZYTFhwCkZRXScMjoG4s3FhgndvT4K/view?usp=sharing)  |                    |           |
| Planejamento de caminhos – Bug Algorithms     |  [Vídeo](https://youtu.be/uto-IPidMyI) - [Slides](https://drive.google.com/file/d/1MzzdPFmfV-M4uVOgyvMPR_b67_d_zgPn/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula11-planejamento-caminhos-bug.ipynb)  |  [Cena](../main/cenas-coppeliasim/aula11-bug-wall-follow.ttt)  |
| Planejamento de caminhos – Campos Potenciais  |  [Vídeo](https://youtu.be/GBr8b40LBNg) - [Slides](https://drive.google.com/file/d/1TXXX5yL48QkH6433cJhpIy6cIVFoBq-S/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula12-planejamento-caminhos-campos-potenciais.ipynb)  |           |
| Planejamento de caminhos – Roadmaps           |  [Vídeo](https://youtu.be/1ct_BgMqkdc) - [Slides](https://drive.google.com/file/d/1TNHXz8neDaT6GEyJ2nyh9VWxrTQlTo01/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula13-planejamento-caminhos-roadmaps.ipynb)  |           |
| Planejamento de caminhos – PRM/RRT            |  [Vídeo](https://youtu.be/aZgiuvmHNS4) - [Slides](https://drive.google.com/file/d/1ECXem_SeZesay4Ls4Ai42LgX234jCe4P/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula14-planejamento-caminhos-prm-rrt.ipynb)  |           |
| Revisão de probabilidade                      |  [Vídeo](https://youtu.be/3SvwmOXXi1w) - [Slides](https://drive.google.com/file/d/1nX6zDvroEoIIo1rR6fULrP31LxivSXEB/view?usp=sharing)  |                    |           |
| Sensores                                      |  [Vídeo](https://youtu.be/QC0HdHgHysE) - [Slides](https://drive.google.com/file/d/1cmWfgl2JKZYVbHwoeCSxdnvuy6OXsp36/view?usp=sharing)  |                    |           |
| Mapeamento – Introdução                       |  [Vídeo](https://youtu.be/Yrqz9ZIAxDc) - [Slides](https://drive.google.com/file/d/17Q0EuDkXkmvvsWAWMej0v8rE88bV2YEs/view?usp=sharing)  |                    |           |
| Mapeamento – Occupancy Grid                   |  [Vídeo](https://youtu.be/aROLZ8zB-2Y) - [Slides](https://drive.google.com/file/d/1dvmsh0tcJsHPDyU2QR5MYszkSXD3rSTD/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula18-mapeamento-occupancy-grid.ipynb)  |           |
| Localização – Kalman                          |  [Vídeo](https://youtu.be/mXLwe9OEoeI) - [Slides](https://drive.google.com/file/d/1sIQxAWU0TLkwtRrEh1puKCvZAvKuRcJ7/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula19-localizacao-kalman.ipynb)  |           |
| Localização – Markov                          |  [Vídeo](https://youtu.be/dypoOHO_-eY) - [Slides](https://drive.google.com/file/d/1qUL4kXcz9-BzDdwK_bRsNt18-k6pmYzp/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula20-localizacao-markov.ipynb)  |           |
| Localização – MCL                             |  [Vídeo](https://youtu.be/oBPa0h8T9D8) - [Slides](https://drive.google.com/file/d/1UeICJJXd7UIcZot3jQyv2gRV4XfdHexk/view?usp=sharing)  |  [Notebook](../main/jupyter-notebooks/aula21-localizacao-mcl.ipynb)  |           |
| SLAM - Introdução                             |  [Vídeo](https://youtu.be/rKU7oabW3i4) - [Slides](https://drive.google.com/file/d/1KZoCjENHgTZZgVtssJTL9TIXiLS-waCN/view?usp=sharing)  |                    |           |
| Sistemas multi-robôs                          |  [Vídeo](https://youtu.be/pOSPOhdQkZI) - [Slides](https://drive.google.com/file/d/12GFMADLzJk3WcrmMLOj-MyE-pZ7V5CIg/view?usp=sharing)  |                    |           |
