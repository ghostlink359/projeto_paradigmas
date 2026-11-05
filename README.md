# Sistema de Biblioteca Acadêmica
### Projeto Integrador – Paradigmas de Linguagem de Programação

## 1. Sobre o projeto

O Sistema de Biblioteca Acadêmica é um projeto desenvolvido com o objetivo de demonstrar a aplicação de diferentes paradigmas de programação na resolução de um mesmo problema.

O sistema representa o funcionamento básico de uma biblioteca universitária, permitindo organizar livros, leitores e empréstimos. A proposta é demonstrar como diferentes abordagens de programação podem representar e solucionar situações relacionadas ao mesmo contexto.

## 2. Objetivos

- Aplicar conceitos de diferentes paradigmas de programação.
- Desenvolver soluções para um problema comum utilizando diferentes abordagens.
- Demonstrar os conceitos de orientação a objetos, programação funcional e programação lógica.
- Explorar um paradigma complementar e comparar suas características com as demais abordagens.

## 3. Paradigmas utilizados

### Orientação a Objetos – Python

Implementação baseada em classes e objetos, representando os principais elementos do sistema, como livros, leitores e empréstimos.

São utilizados conceitos como encapsulamento, abstração, herança e polimorfismo. A implementação também apresenta notificações orientadas a eventos.

Arquivo: `src/biblioteca.py`

### Programação Funcional – Python

Implementação de operações sobre o acervo utilizando funções, estruturas imutáveis e funções de ordem superior.

São utilizados recursos como `map`, `filter` e expressões `lambda`, demonstrando uma abordagem funcional para consultas e processamento de dados.

Arquivo: `src/funcional.py`

### Programação Lógica – Prolog

Implementação de uma base de conhecimento composta por fatos e regras lógicas, representando livros, leitores e empréstimos.

Através das regras e consultas, é possível realizar inferências e obter informações sobre a disponibilidade dos livros e os empréstimos registrados.

Arquivo: `logica/biblioteca.pl`

### Paradigma complementar – Orientado a Eventos

A implementação orientada a objetos também apresenta um mecanismo de notificações baseado em eventos.

Quando determinadas operações são realizadas, como empréstimos e devoluções, eventos são disparados e tratados pelos componentes responsáveis pelas notificações.

## 4. Estrutura do projeto

```text
projeto_paradigmas/
│
├── README.md
│
├── src/
│   ├── biblioteca.py
│   └── funcional.py
│
├── logica/
│   └── biblioteca.pl
│
├── docs/
│   ├── diagrama_classes.mmd
│   ├── diagrama_fluxos.mmd
│   └── diagrama_funcional.mmd
│
└── tests/
    └── testes_manuais.md
```

## 5. Tecnologias utilizadas

- **Python:** desenvolvimento das implementações orientada a objetos e funcional.
- **Prolog:** desenvolvimento da base de conhecimento e das regras lógicas.
- **SWI-Prolog:** ambiente utilizado para execução das consultas lógicas.
- **Mermaid:** elaboração dos diagramas de representação do projeto.

## 6. Testes e validação

As implementações foram verificadas por meio de testes e execuções específicas para cada paradigma.

Foram consideradas operações como consulta de livros, verificação de disponibilidade, identificação de empréstimos, processamento de dados e execução de consultas lógicas.

Os resultados e as evidências das execuções são apresentados na documentação do projeto.

## 7. Integrantes e responsabilidades

- **Patrick:** implementação orientada a objetos e diagrama de classes.
- **Gabriel:** implementação em Prolog e diagrama de fluxos.
- **Matheus:** implementação funcional, testes manuais e diagrama funcional.

## 8. Considerações finais

O projeto demonstra que diferentes paradigmas de programação podem ser utilizados para solucionar problemas semelhantes, cada um apresentando características próprias.

A comparação entre as implementações permite compreender suas diferenças, possibilidades de aplicação, vantagens e limitações, evidenciando a importância de escolher uma abordagem adequada às necessidades de cada problema.