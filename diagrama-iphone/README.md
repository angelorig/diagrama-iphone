### Diagrama UML (Mermaid)
```mermaid
    classDiagram

        
    class ReprodutorMusical{
        <<Interface>> 
        +tocar()void
        +pausar()void
        +selecionarMúsica()void
    }

    class AparelhoTelefonico {
         <<Interface>>
        +ligar()void
        +atender()void
    }

    class NavegadorInternet {
         <<Interface>>
        +exibirPágina()
        +atualizarPágina()
        +adicionarAba()
    }

    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
