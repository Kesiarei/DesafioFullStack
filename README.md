# DesafioFullStack

# Desafio Full Stack Ubistart

Este projeto consiste no desenvolvimento de uma API REST e uma interface de usuário para gerenciar uma lista de tarefas (TODO). A aplicação permite que os usuários criem uma conta, façam login e gerenciem suas próprias tarefas. Além disso, há uma funcionalidade para administradores que permite listar todas as tarefas cadastradas.

Os recursos e funcionalidades do projeto incluem:

1. Criação de conta de usuário: Os usuários podem criar uma conta fornecendo um endereço de e-mail e uma senha.
2. Autenticação de usuário: Os usuários podem fazer login na plataforma com suas credenciais (e-mail e senha) para acessar suas tarefas.
3. Adição de tarefa: Os usuários podem adicionar uma nova tarefa à sua lista, fornecendo uma descrição e um prazo.
4. Finalização de tarefa: Os usuários podem marcar uma tarefa como concluída, registrando a data e a hora em que a tarefa foi finalizada.
5. Edição de tarefa: Os usuários podem editar uma tarefa existente, atualizando a descrição e o prazo. No entanto, tarefas já concluídas não podem ser editadas.
6. Listagem de tarefas do usuário: Os usuários podem visualizar todas as suas tarefas cadastradas, incluindo informações como o e-mail do usuário, descrição da tarefa, prazo e indicação se a tarefa está atrasada.
7. Autenticação de administrador: Existe um usuário administrador padrão que pode fazer login na plataforma.
8. Listagem de todas as tarefas: O administrador pode listar todas as tarefas cadastradas, paginadas por um número específico de tarefas por página. A lista contém informações como o e-mail do usuário, descrição da tarefa e prazo.
9. Filtragem de tarefas atrasadas: O administrador pode filtrar a lista de tarefas para exibir apenas as tarefas que estão atrasadas, também paginadas.

Com base nesses requisitos, o projeto visa fornecer uma solução de gerenciamento de tarefas em que os usuários possam criar suas contas, adicionar tarefas, marcar como concluídas e atualizar informações relevantes. Além disso, o administrador tem acesso a todas as tarefas cadastradas para monitorar o progresso e gerenciar as tarefas atrasadas.
## Para executar o projeto, siga as etapas abaixo:

1. Certifique-se de ter o Node.js e o MongoDB instalados em seu ambiente de desenvolvimento.

2. Faça o download do código-fonte do projeto e descompacte-o em um diretório de sua escolha.

3. Abra um terminal ou prompt de comando e navegue até o diretório raiz do projeto.

4. Instale as dependências do projeto executando o seguinte comando:
   ```
   npm install
   ```

5. Inicie o servidor MongoDB. Certifique-se de que o MongoDB esteja instalado e em execução em sua máquina. Você pode iniciar o servidor MongoDB executando o comando `mongod` em um novo terminal.

6. Configure a conexão com o banco de dados MongoDB. No arquivo `config.js`, você pode ajustar a URL de conexão se necessário. Por padrão, a URL está configurada como `mongodb://localhost:27017/todoapp`.

7. Inicie o servidor da API executando o seguinte comando:
   ```
   npm start
   ```

   Isso iniciará o servidor da API na porta `3000` (você pode alterar a porta no arquivo `config.js`, se necessário). Você verá a mensagem "API rodando em http://localhost:3000" no terminal quando o servidor estiver em execução.

8. Acesse a interface de usuário. Abra um navegador da web e acesse `http://localhost:3000` para acessar a interface de usuário do projeto.

Agora você pode criar uma conta de usuário, fazer login e gerenciar suas tarefas. A interface de usuário permitirá que você adicione tarefas, marque como concluídas, edite e liste suas próprias tarefas. Como administrador, você poderá fazer login e acessar a lista completa de tarefas, bem como filtrar as tarefas atrasadas.

Lembre-se de que você pode personalizar e ajustar o projeto de acordo com suas necessidades específicas. Consulte a documentação das bibliotecas utilizadas, como o Express.js e o Mongoose, para obter mais informações sobre como estender e personalizar o código.
## Suporte

Se você encontrar algum problema ao tentar executar o projeto ou tiver alguma dúvida relacionada ao código, sinta-se à vontade para entrar em contato conosco. Estamos aqui para ajudar!

Por favor, envie um e-mail para kesiag80@outlook.com descrevendo o problema ou a dúvida que você está enfrentando. Faremos o possível para responder o mais rápido possível e fornecer a assistência necessária para ajudá-lo a resolver o problema.

Estamos comprometidos em garantir que sua experiência com o projeto seja tranquila e bem-sucedida, então não hesite em nos contatar caso precise de suporte adicional. Estamos ansiosos para ajudá-lo a ter sucesso com o projeto!


