# Workload Generator

O **Workload Generator** é uma ferramenta que automatiza a criação de cargas de trabalho e simulações de desempenho para projetos de software, permitindo gerar rapidamente testes de stress, benchmark e análises de capacidade para aplicações em .NET, Node.js, Python, Go.

## Tecnologia

- **Linguagem principal:** Go  
- **Por que da escolha:** Testes de carga e simulações de alta performance são melhor suportados pelo Go, com concorrência eficiente e baixo overhead.

## Arquitetura

- **Arquitetura recomendada:** Modular / Event-Driven  
- **Por que da escolha:** Simulações de carga se beneficiam de módulos independentes que podem gerar eventos e workloads em paralelo.
