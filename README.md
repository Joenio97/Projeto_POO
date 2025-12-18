# Projeto_POO

## Catalogo de Jogos Digitais

### Integrantes de equipe e distribuição de tarefas

Joenio Borges de Araújo: Modelagem OO, classes Jogo e Status.

Maria Fernanda Sousa Silva: Regras de negócio, estados e classe coleção.

Matheus Moraes Bernardo: Persistência de dados e classe relatorios.

Kauê Oliveira Fernandes: Interface (CLI), classe progresso, testes e documentação.

Principais classes do projeto

**Class: Jogo**

atributos: titulo, genero, avaliação

metodos: cadastrar, gerenciar

**Class  JogoPc(Jogo):**

super( ).__init__( atribtutos Jogos)

metodos:

**Class Coleção:**

atributos ( nome )

metodos: CriarColecao, adicionar, remover, editar, evitarDuplicação, listar

**Class Status:**

atributos: nãoIniciado, Jogando, finalizado

**Class Relatorio(Status)**

Self( ).__init__(atributos Status)

atributos: tempoJogado

metodos: calcularMédia de avaliação dos jogos finalizados, 
calcularPercentual de jogos por status, listarTop 5 jogos mais jogados,
registrarInicio, registraTermino

**Class Progresso( Relatorio):**

super( ).__init__( atributos relatorio)

metodos: atualizarTempojogado, atualizarStatus

**Class filtros:**

metodos: FiltrarGênero, FiltrarPlataforma, FiltrarStatus, FiltrarTitulo, BuscarParte doTitulo.
