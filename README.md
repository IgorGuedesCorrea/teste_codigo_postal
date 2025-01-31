# teste_codigo_postal

## Descrição
O teste consistiu no carregamento de uma base de códigos postais e, posteriormente, no enriquecimento desses dados com o conselho e distrito associado a cada um desses códigos. Por fim, os dados foram carregados em um banco de dados.

## Tecnologias Utilizadas
Para desenvolver este projeto, utilizei as seguintes bibliotecas:
- `pandas`
- `requests`
- `json`
- `sqlalchemy`
- `time`
- `tqdm`

Para facilitar o enriquecimento dos dados, utilizei uma API do CTT Código Postal, automatizando o preenchimento dos campos necessários. A base precisou de pouquíssimo tratamento; apenas alguns códigos não possuíam a formatação correta para a pesquisa, pois não estavam divididos pelo hífen (separação entre CP3 e CP4).

## Processo
1. Carregamento da base de códigos postais.
2. Enriquecimento dos dados utilizando a API do CTT Código Postal.
3. Tratamento dos dados inconsistentes.
4. Exportação do arquivo final em `.csv`.
5. Armazenamento dos dados em um banco de dados PostgreSQL.

## Desafio Extra
Para o desafio extra, foi necessário criar uma API simples conectada ao banco de dados PostgreSQL para consumo das informações geradas anteriormente.

## Contato
Caso tenha dúvidas ou sugestões, entre em contato!
