# Exemplos AdvPL REST

Este repositório contém um conjunto de implementações de serviços REST em AdvPL
cautelosamente comentados com o objetivo de servir de referência à construção
de novas aplicações e auxiliar no aprendizado das características dessa tecnologia.

Os exemplos estão ordenados por complexidade e nomeados de acordo com suas
características funcionais.

- [Olá mundo!](./01.ola_mundo.apw) - seu primeiro webservice com apenas uma rota `GET` simples e retorno em JSON.
- [Transformar palavra](./02.transformar_palavra.apw) - webservice com duas rotas `GET` para deixar palavras em caixa alta ou baixa.
- [Campos por tabela](./03.campos_por_tabela.apw) - uma única rota `GET` que permite trazer os campos definidos na `SX3` para uma tabela existente na `SX2` recebendo o identificador do arquivo da tabela na própria URL.