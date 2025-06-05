Instruções de uso:

Ao iniciar o programa, você poderá cadastrar um novo usuário, escolha a opção correspondente e informe nome, CPF e senha. O sistema valida o CPF e cancela o cadastro caso seja inválido. Após cadastrar, você pode fazer login informando CPF e senha. O login é obrigatório para acessar funções como cadastrar livros, editar, alugar e devolver.

Ao cadastrar um livro, informe ID, título, ano de publicação, ISBN e autor. O sistema salva os dados em arquivo e permite que o livro seja gerenciado posteriormente. A busca por livro pode ser feita pelo ID, retornando as informações e disponibilidade.

Você pode editar os dados do livro pelo ID, alterando as informações e o status de disponibilidade. Para alugar um livro, é preciso estar logado e buscar pelo ID ou título. Só é possível alugar livros que estejam disponíveis. Da mesma forma, para devolver um livro, informe o ID e o sistema atualizará sua disponibilidade.

O programa também permite exibir todos os livros cadastrados e todos os usuários cadastrados (sem mostrar as senhas).

Os dados ficam salvos em dois arquivos: usuarios.txt e livros.txt. O formato de cada linha em usuarios.txt é nome, CPF e senha separados por ponto e vírgula. Já no livros.txt, cada linha contém ID, título, autor, ano, ISBN e status de disponibilidade (“s” para disponível, “n” para alugado).

Por fim, escolha a opção “Sair” para encerrar o programa com segurança.
