# Como contribuir

Estas regras valem para todos os repositórios da organização GamificaPampa.

## Onde cada coisa fica

| Conteúdo                            | Repositório                                |
| ----------------------------------- | ------------------------------------------ |
| Página do site do hub               | `gamificapampa.github.io`                  |
| Jogo ou material para crianças      | `recursos-pedagogicos/criancas/<nome>/`    |
| Material de formação de professores | `recursos-pedagogicos/professores/<nome>/` |
| Kit do formador (só a equipe)       | `equipe/<formacao>/` (privado)             |
| Logo, mascote, fonte ou cor         | `identidade-visual`                        |
| Slides de uma palestra              | `apresentacoes/AAAA-MM-DD-evento-cidade/`  |

O repositório `equipe` é privado e não vai para o site. Nele fica o que só quem conduz uma formação usa (roteiro, slides dos encontros, folhas para imprimir, certificado, convite e proposta) e as anotações internas. O que os professores participantes usam continua em `recursos-pedagogicos`.

## Regras

1. Nomes de pastas e arquivos em minúsculas, sem acento, com hífen entre as palavras.
2. Toda pasta nova de recurso ou apresentação tem um `README.md` que diz o que é, para quem é e de qual projeto veio.
3. Use os logos, a fonte e as cores de `identidade-visual` pelo caminho `/identidade-visual/`, sem copiar os arquivos.
4. Dados pessoais ficam fora do git. Respostas de questionários, nomes e e-mails de professores, alunos e escolas vão para o Google Drive institucional, com acesso restrito à equipe.
5. Mudanças na branch `main` entram por pull request, com uma descrição curta do que mudou.
6. Mensagens de commit seguem o padrão Conventional Commits, por exemplo `feat: adiciona jogo da memória`.
