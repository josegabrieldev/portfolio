# Dev Gabriel — Plano de Desenvolvimento

> Documento de referência para organizar a implementação, acompanhar decisões e manter a qualidade do portfólio.

## 1. Visão do projeto

Construir um portfólio profissional para apresentar os serviços, projetos, conhecimentos e formas de contato de Dev Gabriel como desenvolvedor Front-End.

O projeto será desenvolvido com HTML, CSS e JavaScript, priorizando código compreensível, organização, semântica e boas práticas.

## 2. Objetivos da primeira versão

- Apresentar a identidade profissional e a proposta de trabalho.
- Exibir os principais serviços oferecidos.
- Destacar projetos desenvolvidos.
- Apresentar uma breve introdução profissional.
- Explicar o processo de trabalho.
- Oferecer formas claras de contato.
- Disponibilizar uma experiência funcional e consistente em dispositivos móveis.

## 3. Estratégia responsiva

A implementação seguirá uma abordagem Mobile First.

### Etapa 1 — Primeira versão publicável
- Priorizar a referência visual mobile de 390px.
- Construir a estrutura semântica da página.
- Implementar os estilos e as interações necessárias.
- Realizar testes e revisão antes da publicação.

### Etapa 2 — Tablet
- Adaptar a composição para telas de tablet.
- Aproveitar melhor o espaço horizontal.
- Revisar grids, espaçamentos e navegação.

### Etapa 3 — Desktop
- Planejar uma composição adequada para telas maiores.
- Refinar hierarquia, proporções e distribuição do conteúdo.
- Testar diferentes larguras de tela.

As medidas de referência orientam o planejamento visual, mas não significam que o layout ficará limitado a uma largura específica.

## 4. Princípios de desenvolvimento

- **Semântica:** utilizar elementos HTML de acordo com seu significado.
- **Acessibilidade:** considerar navegação por teclado, foco visível, contraste e tecnologias assistivas.
- **SEO:** organizar títulos, metadados, conteúdo e links de forma adequada.
- **Responsividade:** evitar layouts dependentes de uma única largura.
- **Manutenibilidade:** escrever código organizado e fácil de compreender.
- **Desempenho:** cuidar de imagens, fontes, carregamento e recursos utilizados.
- **Consistência visual:** seguir o Design System e os tokens aprovados.

## 5. Fluxo de implementação

Cada etapa seguirá este processo:

1. Planejar o que será desenvolvido.
2. Entender os conceitos necessários.
3. Implementar no VS Code.
4. Revisar o código.
5. Corrigir os pontos identificados.
6. Testar no navegador.
7. Registrar uma etapa concluída com Git.

## 6. Organização do trabalho por tecnologia

### HTML
Começar com uma estrutura limpa e sem classes ou IDs desnecessários.

A estrutura será definida com elementos semânticos. Classes serão adicionadas quando começarmos a estilização, de acordo com uma convenção de nomenclatura consistente. IDs serão utilizados quando houver uma necessidade real, como identificação de destinos de navegação ou integração com JavaScript.

### CSS
Definir uma convenção de nomenclatura antes de criar os componentes.

Organizar os estilos com base nos tokens do Design System, responsabilidades dos componentes e necessidades de responsividade.

### JavaScript
Planejar as interações antes de implementá-las.

Definir identificadores e seletores de forma intencional, evitando adicionar IDs sem necessidade.

## 7. Revisão e qualidade

Durante as revisões, observar:

- Estrutura e semântica do HTML.
- Hierarquia de títulos.
- Organização e nomenclatura do CSS.
- Responsabilidade e clareza do JavaScript.
- Acessibilidade e usabilidade.
- SEO técnico e conteúdo.
- Desempenho e responsividade.
- Funcionamento real no navegador.

Os apontamentos serão separados por prioridade: problemas que precisam ser corrigidos, melhorias recomendadas e sugestões opcionais.

## 8. Versionamento com Git

Utilizar commits pequenos e significativos, sempre que uma etapa importante estiver concluída e testada.

As mensagens serão objetivas e seguirão um padrão consistente, por exemplo:

- `docs: update project README`
- `docs: add development plan`
- `feat: add homepage semantic structure`
- `style: add global design tokens`
- `feat: implement mobile navigation`
- `fix: correct contact form validation`

Antes de cada commit, revisar as alterações e conferir o estado do repositório.

## 9. Forma de trabalho

A implementação será feita pelo próprio desenvolvedor, com orientação técnica durante o processo.

O objetivo é compreender as decisões, aprender os conceitos e desenvolver autonomia, em vez de apenas copiar soluções prontas.

Este documento poderá ser atualizado conforme novas decisões forem aprovadas.