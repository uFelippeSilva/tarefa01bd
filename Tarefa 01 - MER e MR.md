# Tarefa 01 - MER e MR

- nome: Felippe da Silva Guedes
- matricula: 20220068057
- email: felippe.silva.142@ufrn.edu.br

# Modelagem de Sistema de Divulgação de Jogos.

![2023-09-28 (0)](https://github.com/uFelippeSilva/tarefa01bd/assets/112040769/2b9f95ba-e348-47b8-99c4-55d1cca0525a)


# esquema relacional do sistema feito acima.

- Tabela Usuario (__codigo__ __usuario__, nome, email)
- Tabela Jogo (__id__, nome, descricao, data_criacao, url_download, tipo, classificacao_etaria)
- Tabela Comunidade (__id__, nome, descricao, tipo)
- Tabela ComentaJogo (__id__, texto, __codigo__ __usuario__, __Id__ __jogo__)
- Tabela ComentaComunidade (__id__, texto,__codigo__ __usuario__, __id__ __comunidade__)
