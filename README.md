# Tarefa 01 - MER e MR

- nome: Felippe da Silva Guedes
- matricula: 20220068057
- email: felippe.silva.142@ufrn.edu.br

# Modelagem de Sistema de Divulgação de Jogos.

![2023-09-28 (2)](https://github.com/uFelippeSilva/tarefa01bd/assets/112040769/28c459de-8c6f-4763-919c-0ba6c1671031)

# esquema relacional do sistema feito acima.

- Tabela Usuario (__codigo__ __usuario__, nome, email)
- Tabela Jogo (__id__, nome, descricao, data_criacao, url_download, tipo, classificacao_etaria)
- Tabela Comunidade (__id__, nome, descricao, tipo)
- Tabela ComentaJogo (__id__, texto, __codigo__ __usuario__, __Id__ __jogo__)
- Tabela ComentaComunidade (__id__, texto,__codigo__ __usuario__, __id__ __comunidade__)
