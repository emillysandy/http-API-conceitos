# On11-TodasEmTech-s6-Introducao-Node
Turma Online 11 - Todas em Tech | Back-end | 2021 | Introdução à API:
HTTP e NodeJS

## Para o lar


1) Qual a relação entre os métodos HTTP e o CRUD?

HTTP é um protocolo de transferência que possibilita que as pessoas que inserem a URL do seu site na Web possam ver os conteúdos e dados que nele existem. A sigla vem do inglês Hypertext Transfer Protocol.

Já o CRUD é a composição da primeira letra de 4 funções básicas de um sistema que trabalha com banco de dado

A relação entre os dois são:

✅ C: Create (criar) - criar um novo registro
    - Se relaciona com o método POST do HTTP.

👁 R: Read (ler) - ler (exibir) as informações de um registro
    - Se relaciona com o método GET do HTTP. 

♻️ U: Update (atualizar) - atualizar os dados do registro
    - Se relacionna com o método PUT e PATCH do HTTP.

❌ D: Delete (apagar) - apagar um registro
    - Se relaciona com método DELETE do HTTP.

2) Comente, com exemplos, a diferença entre o PUT e o PATCH.

O PATCH aplica modificações parciais a um recurso,já o PUT permite apenas substituições completas de um documento.


3) Assim como na aula, apresente os dados dos JSONs no console 
    - No colors-rgb.js apresente o nome da cor e o codigo RGB como no exemplo: "gainsboro - rgb(220, 220, 220, 1)"
    - No estados-cidade.js apresente o nome do Estado, a sigla e todas as cidadades, sem arrays aparentes no console
    - No filmes.js apresente titulo, plot, generos e lingua. Genero e lingua devem ser apresentados em arrays no console.

4) Defina o conceito de idempotência e como uma API pode ser idempotente

Idempotência acontece quando se chama a mesma função com o mesmo valor e o resultado é exatamente o mesmo, sendo executada uma ou inúmeras vezes.Uma API idempotente significa que o endpoint pode ser chamado várias vezes sem resultados diferentes. Não importa se o método é chamado apenas uma ou dez vezes. O resultado deve sempre o mesmo. Isso se aplica apenas ao resultado, não ao próprio recurso.

5) Cite alguns diferentes padrões de projetos de software

Design Patterns (comumente relacionados na literatura de TI como “Padrões de Projeto”) são soluções para problemas comuns que encontramos no desenvolvimento ou manutenção de um software orientado a objetos.

Os principais padrões de projetos são:
- Abstract Factory
- Factory Method
- Singleton
- Adapter
- Template Method