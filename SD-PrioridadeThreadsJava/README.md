Descrição:
Exemplo básico de manipulação ded threads em Java. 

Foram desenvolviddas duas classes principais dde threads:

BaixaPrioridade: Thread que simula uma execução de baixa prioridade.
AltaPrioridade: Thread que simula uma execução de alta prioridade.
O programa também demonstra como usar Shutdown Hooks para gerenciar encerramento de threads de forma controlada.

Estrutura do Projeto
LancadorPrioridade.java: Contém a implementação do programa.
README.md: Arquivo explicativo do projeto.

Ao iniciar o programa, ambas as threads são executadas:

BaixaPrioridade: Imprime mensagens continuamente.
AltaPrioridade: Imprime 5 mensagens, dorme por 10 ms e continua o ciclo.
O comportamento esperado é que a AltaPrioridade receba mais tempo de CPU em sistemas que respeitam prioridades de threads.

Etapas Realizadas: 
Criado um respositório para chamado: SD-PrioridadeThreadsJava
Incluído o algoritmo da professora presente em LancadorPrioridade.java
Compilado os programas
Executado o programa Lancador de prioridades.
