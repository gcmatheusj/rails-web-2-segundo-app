# README

[Heroku App](https://rails-web-2-segundo-app.herokuapp.com/)

Respostas das questões abertas do Roteiro 2

### 9
a - id: notice. Quando a tela é atualizada a mensagem some, porém a tag <p></p> que renderiza a mensagem continua no codigo fonte, e as informações do usuário cadastrado continua em tela.

b - O usuário é cadastrado sem email.

c - O usuário é cadastrado com o email inválido.

d - Sim, aparece uma mensagem de confirmação perguntando se quero excluir o usuário e em seguida uma mensagem de sucesso.

### 12 
No arquivo users_controller.rb, linha 67: @user = User.find(params[:id])

### 13 
edit.html.erb

### 15
a - id: notice. Quando a tela é atualizada a mensagem some, porém a tag <p></p> que renderiza a mensagem continua no codigo fonte e as informações do micropost cadastrado continua em tela.

b - O micropost é criado, porém sem o content e o id do user.

c - O micropost é criado normalmente.

d - Todos os micropost foram destruidos com sucesso.

### 17 
a - Uma mensagem de erro é exibida, informando que o content é muito grande (máximo de 140 caracteres).

b - id: error_explanation