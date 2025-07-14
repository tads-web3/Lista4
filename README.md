# Lista4
Prática com validações, controle de erros e testes

UsuarioService

    Deve adicionar pessoa corretamente
    Deve retornar pessoa por ID existente
    Deve lançar exceção ao buscar ID inexistente

LivroService

    Deve adicionar livro corretamente
    Deve listar apenas livros disponíveis
    Deve marcar livro como emprestado
    Deve marcar livro como disponível novamente após devolução

EmprestimoService

    Deve permitir empréstimo se a pessoa não estiver bloqueada e tiver menos de 3 empréstimos
    Não deve permitir empréstimo se o livro não estiver disponível
    Não deve permitir empréstimo se a pessoa já tiver 3 livros
    Não deve permitir empréstimo se a pessoa estiver bloqueada
    Deve calcular dataDeDesbloqueio corretamente com base em atraso
    Deve agendar devolução para dia útil (pular sábados e domingos)

Testes de integração recomendados (não limitantes nem obrigatórios):

    Testar o endpoint de cadastro de pessoas
    Testar o endpoint de empréstimo
    Testar o endpoint de devolução de um livro
