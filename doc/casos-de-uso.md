## Casos de Uso:

### Caso de uso 1: Gerenciar-se.

#### Atores:

- Cliente.
  
#### Fluxo principal:

- O usuário seleciona a opção “Criar conta”.
  
- O sistema leva o usuário até a tela de registro contendo um formulário.
  
- O usuário preenche os campos do formulário (informando nome, e-mail e criando uma senha).
  
- O sistema consulta o banco de dados para verificar a disponibilidade das informações fornecidas.
  
- O banco de dados retorna uma confirmação positiva.
  
- O sistema realiza o cadastro, salvando os dados do novo usuário.
  
- O sistema encaminha o usuário para a página principal do site.

### Caso de Uso 2: Efetuar login.

#### Atores: 

- Cliente

#### Fluxo principal:

- O usuário seleciona a opção "Login".

- O sistema leva o usuário até a tela de preenchimento de senha e email.

- Usuário preenche os campos da tela.

- O sistema consulta o banco de dados para a confirmação dos dados inseridos.

- O banco de dados retorna uma confirmação positiva.

- O sistema encaminha o usuário para a página principal do site.

  ### Caso de Uso 3: Buscar livros.

#### Atores: 

- Cliente e Administrador

#### Fluxo principal: 

- O sistema apresenta a página inicial do site.

- O usuário aperta na barra de pesquisa.

- O usuário digita o livro que deseja, o gênero de livro que deseja ou o autor.

- O usuário aperta no botão "Enter".

- O sistema consulta o banco de dados.

- O banco retorna os livros.

- Os livros são exibidos.

- FIZ ATÉ AQUI

 ### Caso de Uso 6: Categorias.

#### Atores: 

- Usuário

#### Fluxo principal:  

- O usuário seleciona o menu "Categorias".

- O sistema carrega a lista de categorias disponíveis.

- O usuário clica na categoria desejada.

- O sistema busca os produtos pertecentes àquela categoria no banco de dados.

- O sistema exibe os produtos filtrados pela categoria selecionada com informações.

 ### Caso de Uso 7: Carrinho de compras.

#### Atores: 

- Usuário

#### Fluxo principal:  

- O usuário clica no ícone do "carrinho de compras".

- O sistema redireciona o usuário para a página contendo os itens desejados.

- O usuário pode iniciar o processo de compra dos produtos desejados.

- O usuário preenche o cadastro com suas informações de endereço.

- O usuário seleciona uma forma de pagamento.
  
- O usuário finaliza a compra e é redirecionado para a pagina inicial.

#### Fluxo Alternativo A: Cancelar produto do Carrinho de compras

- O usuário clica no ícone do "carrinho de compras".

- O sistema redireciona o usuário para a página contendo os itens desejados.

- O usuário aperta na lixeira (excluir produto).

- O sistema exclui produto do banco de dados.

 ### Caso de Uso 8: Pagina de pedidos.

#### Atores: 

- Usuário

#### Fluxo principal:  

- O usuário clica no icone da pagina de pedidos.

- O sistema redireciona o usuário para a pagina contendo informações de seus pedidos.

- O usuário consulta seus pedidos e volta para pagina inicial.

 ### Caso de Uso 9: Logout

#### Atores: 

- Usuário

#### Fluxo principal:  

- O usuário acessa o menu do seu perfil com as configurações da sua conta e aperta o botão de "Logout".

- O sistema apresenta uma mensagem perguntando "Quer confirmar o Logout?".

- O usuário confirma.

- O sistema apaga o login do usuário.

- O sistema realoca o usuário para o menu do seu perfil com  as configurações da sua conta.

#### Fluxo Alternativo A: Cancelar Logout

- O usuário acessa o menu do seu perfil com as configurações da sua conta e aperta o botão de "Logout".

- O sistema apresenta uma mensagem perguntando "Quer confirmar o Logout?".

- O usuário decide que não quer mais fazer Logout e aperta o botão cancelar.

- O sistema redireciona o usuário para o menu do seu perfil com  as configurações da sua conta.

### Caso de Uso 10: Gerenciar Catálogo de produtos.

#### Atores: 

- Administrador 

#### Fluxo principal: 

- O administrador acessa o sistema.

- Seleciona a opção "Catálogo de Produtos".

- Visualiza a lista de produtos cadastrados.

- Clica em "Adicionar Produto".

- Preenche as informações do produto (nome, descrição, preço, imagem, categoria).

- Clica em "Salvar".

- O sistema adiciona o novo produto ao catálogo.

#### Fluxo Alternativo A: Excluir produto do catálogo

- O administrador acessa o sistema.

- Seleciona a opção "Catálogo de Produtos".

- Visualiza a lista de produtos cadastrados.

- Clica em "Excluir produto do catálogo".

- O sistema exclui produto do banco de dados.


### Caso de Uso 11: Gerenciar Categoria.

#### Atores:

- Admninistrador

#### Fluxos principal:

- O administrador acessa o sistema.

- Seleciona a opção "Categorias".

- Visualiza as categorias existentes.

- Clica em "Adicionar Categoria".

- Insere o nome da nova categoria.

- Clica em "Salvar".

- O sistema cadastra a nova categoria.

#### Fluxo Alternativo A: Excluir categoria

- O administrador acessa o sistema.

- Seleciona a opção "Categorias".

- Visualiza as categorias existentes.

- Clica em "Excluir Categoria".

- O sistema exclui categoria do banco de dados.

### Caso de Uso 12: Editar pedidos.

#### Atores:

- Administrador

#### Fluxo principal: 

- O administrador acessa o sistema.

- O administrador seleciona "Pedidos" e visualiza.

- O administrador clica em um pedido para ver detalhes.

- O administrador atualiza o status do pedido, por exempo, "em entrega" ou "concluído".

- O sistema registra a atualização.

### Caso de Uso 13: Gerenciar clientes. 

#### Atores: 

- Administrador

#### Fluxo principal: 

- O administrador acessa o sistema.

- O administrador vai até a seção "Clientes".

- O administrador visualiza a lista de clientes cadastrados.

- O administrador clica sobre um cliente para ver detalhes.

- O administrador pode optar por editar ou excluir o cadastro.

### Caso de Uso 14: Acessar relatório de vendas.

#### Atores: 

- Administrador

#### Fluxo principal:

- O administrador acessa o sistema.

- O administrador seleciona "Relatórios" no menu.

- O administrador escolhe o período desejado.

- O sistema exibe o relatório com as vendas no período.
