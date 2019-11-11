!     Universidade Federal de Mato Grosso
!     Bacharelado em Física
!     Tópicos de Física Computacional
!     Autora: Mariane Dias de Souza Gomes
!     Algoritmo feito a partir do problema de Monty Hall.
!     Neste algoritmo consideramos que o participante sempre troca de porta.

      program montyhall

!       Define semente para números gerados de forma pseudo-aleatória. Podemos mudar a seed para gerar outra sequência aleatória posteriormente
        integer,parameter :: seed = 8743

!       PC - porta do carro; PP - porta participante
!       erro - número de vezes que o participante irá errar
!       acerto - número de vezes que o participante irá acertar

        integer PC, PP, m, erro, acerto

!       Inicia primeiro número pseudo-aleatório
        call srand(seed)

        erro = 0
        acerto = 0

        do i=1,30000

!          Escolha da porta que contém o carro (PC)

           PC = 3.*rand()+1.

!          Escolha da porta pelo participante

           PP = 3.*rand()+1.

!         Se o participante escolhe a porta do carro, ele erra.
          If (PC.eq.PP) then
		      erro = erro + 1

!          Se não ele ganha o carro, já que o apresentador elimina a única porta vazia que resta.
           else
               acerto = acerto + 1
           endif

        enddo

        print *,"O participante errou a porta ", erro, " vezes"
        print *,"O participante acertou a porta ", acerto, " vezes"

      end program montyhall
