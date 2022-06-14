# Teste de seleção Front-end  Imobibrasil

## Regras:
- A programação deve ser feita na linguagem PHP, banco de dados MySQL e front-end usando HTML e CSS. 
- Para este desafio você deve utilizar PHP sem frameworks como: Laravel, Cake ou CodeIgnite.
- Neste teste iremos disponibilizar acesso a um servidor com FTP, PHP e Mysql na plataforma cPanel.

## Diferenciais para análise:
- Código organizado e limpo.
- Montar a estrutura do projeto na ferramenta de sua preferência.


## O projeto:
Você foi encarregada de desenvolver uma landing page bonita e moderna para os clientes da imobibrasil. Nossos clientes são corretores de imóveis e precisam destacar imóveis para as suas campanhas do Google ads. Para este projeto você irá precisar criar uma tabela de imóveis e carregar as informações para o front-end.
Aqui tem um exemplo de uma lading page que usamos hoje http://www.imobibrasil.net/hs/empreendimento-jardim-das-flores-6783


### Lading Page
Abaixo os requisitos da funcionalidade:

- Sua landing page pode ser inspirada em um modelo pronto de sites como o ThemeForest.
- Para este teste utilize somente frameworks de Front-end não reativos.
- Utilize o nosso exemplo atual de landing page para mapear os campos e áreas que utilizamos.
- Campos que não existem na tabela imóvel podem ser inseridos direto no HTML.

### Imóveis
Abaixo os requisitos da funcionalidade:

- Não é necessário criar a CRUD dos imóveis.
- Você pode inserir manualmente as linhas na tabela pelo PHPmyAdmin.
- Campos: Id, título do imóvel, descrição, preço e data do cadastro.

### Tabela Fotos
Abaixo os requisitos da funcionalidade:
- A tabela fotos também não requer a criação de CRUD.
- O relacionamento com a tabela imóveis será 1:N (um para muitos)
- Você pode inserir manualmente as linhas pelo PHPmyAdmin.
- Quanto aos arquivos de fotos você pode fazer o upload manulmente pelo FTP.
- Campos: Id, Id_imovel, nome_arquivo, ordem

## Tabelas necessárias:
- imoveis
- fotos
