# Exemplos AdvPL REST

Este repositório contém um conjunto de implementações de serviços REST em AdvPL
cautelosamente comentados com o objetivo de servir de referência à construção
de novas aplicações e auxiliar no aprendizado das características dessa tecnologia.

Os exemplos estão ordenados por complexidade e nomeados de acordo com suas
características funcionais.

- [Olá mundo!](./01.ola_mundo.apw) - seu primeiro webservice com apenas uma rota `GET` simples e retorno em JSON.
- [Transformar palavra](./02.transformar_palavra.apw) - webservice com duas rotas `GET` para deixar palavras em caixa alta ou baixa.
- [Campos por tabela](./03.campos_por_tabela.apw) - uma única rota `GET` que permite trazer os campos definidos na `SX3` para uma tabela existente na `SX2` recebendo o identificador do arquivo da tabela na própria URL.
- [Headers](./04.headers.apw) - demonstração de como receber e enviar headers HTTP.
- [Status](./05.status.apw) - devolvendo códigos de status HTTP.
- [Receber JSON](./06.receber_json.apw) - recebendo JSON como corpo de uma requisição via `POST`.
- [Tarefas](./07.tarefas.apw) - cadastro completo de lista de tarefas contemplando `GET`, `POST`,
`PUT` e `DELETE` com múltiplos caminhos e validações.
- [Download de arquivo](./07.download_de_arquivo.apw) - `TODO` - demonstração de como podemos forçar o download de
um arquivo do servidor e customizar suas propriedades.
- [Renderizar imagem](./08.renderizar_imagem.apw) - `TODO` - utilizando a mesma técnica do download de arquivo, permitimos
renderização de imagens através de rotas específicas.
- [Upload de imagem](./09.upload_de_imagem.apw) - `TODO` - permitimos que nosso servidor seja capaz de receber
arquivos de imagem do cliente.
- [Cookies](./10.cookies.apw) - `TODO` - utilizando cookies para gerenciar sessões dos usuários.
