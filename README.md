# EBAC Exercícios LESS

# LESS: Estilização Dinâmica para Desenvolvimento Web

**LESS** é uma linguagem dinâmica de folhas de estilo (CSS) que aprimora as capacidades do CSS padrão. Ele oferece recursos poderosos para estilizar páginas da web, tornando seu código mais eficiente e flexível. Aqui estão os pontos-chave sobre o LESS:

## Recursos:

1. **Variáveis**:
   - Defina valores reutilizáveis (como cores, tamanhos de fonte ou margens) usando variáveis.
   - Atualize facilmente esses valores em todo o seu código.
2. **Aninhamento**:
   - Aninhe seletores dentro de outros seletores para criar uma estrutura mais organizada e legível.
   - Evite código repetitivo agrupando estilos relacionados.
3. **Mixins**:
   - Mixins permitem criar blocos de código reutilizáveis.
   - Use-os para estilos comuns (por exemplo, prefixos de fornecedores, gradientes) ou classes de utilidade personalizadas.
4. **Operações Matemáticas**:
   - Realize cálculos diretamente em suas folhas de estilo.
   - Ajuste valores dinamicamente com base no tamanho da tela ou outras condições.

## Por que Usar o LESS?

- **Código de Manutenção**:
  - O LESS ajuda a organizar seus estilos, tornando-os mais fáceis de manter e atualizar.
  - Alterações em variáveis se propagam automaticamente em todo o código.
- **Design Responsivo**:
  - Use media queries e mixins para criar layouts responsivos.
  - Adapte os estilos com base no tamanho da tela, melhorando a experiência do usuário.
- **Integração com Ferramentas de Compilação**:
  - O LESS pode ser compilado em CSS padrão usando ferramentas de compilação como Webpack, Gulp ou Grunt.
  - Automatize o processo de compilação para um fluxo de trabalho de desenvolvimento contínuo.

## Primeiros Passos:

1. **Instalação**:
   - Instale o LESS globalmente via npm (Node Package Manager):`npm install -g less`
2. **Estrutura de Arquivos**:
   - Crie um arquivo `.less` para seus estilos.
   - Compile-o em um arquivo `.css` usando o compilador LESS.

## Exemplo:

`// styles.less@cor-primaria: #3498db;body {  background-color: @cor-primaria;}// Compilar usando: lessc styles.less styles.css`

