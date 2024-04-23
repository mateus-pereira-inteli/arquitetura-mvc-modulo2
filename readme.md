A diagramação abaixo utiliza o padrão de estruturação MVC, o padrão MVC é dividido em três componentes.
Model: Comunicação com o banco de dados.
View: Entrega a intêrface para o usuário.
Controller: Intermediário entre a View e a Model.

<img src="./diagramacao.png">

[Link para leitura](https://drive.google.com/file/d/1nf5gP0mLMxU7R2FbCIufo2RAXUwoKuzd/view?usp=sharing)

Realizei esta diagramação me baseiando nas duas principaís funcionalidades da aplicação web, a gestão e cadastro de usuários e cadastro/atualização dos manuais.

Podemos observar na diagramação acima a Entidade do Model em ligação com o banco de dados, mostrando a comunicação entre os dois, podemos ver o Model em ligação com o Controller onde vizualizamos o controle das funções da nossa aplicação, conectando assim com a View, que será entregue ao usuário.

Na tabela users adcionei as seguintes colunas:<br>
id: Chave Primária<br>
name: Nome do usuário<br>
email: E-mail do usuário<br>
password: Senha do usuário<br>
role: Nivel de permissão do usuário<br>
created_at: Data/hora que foi criado no banco<br>
updated_at: Ultima atualização deste registro <br>

Na tabela manuais adcionei as seguintes colunas:<br>
id: Chave Primária<br>
name: Nome do manual<br>
descricao: Descrição do manual<br>
created_at: Data/hora que foi criado no banco<br>
updated_at: Ultima atualização deste registro

