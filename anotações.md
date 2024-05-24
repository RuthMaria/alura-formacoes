 ### Quando usar img e background-image?
 
 <p> Usa-se img quando você quer mostrar um texto alternativo para o usuário quando a imagem não carrega, faz parte do conteúdo da página.</p>p
  Usa-se background-image quando não faz diferença a imagem ser carregada ou não, ela é apenas decorativa, o seu contexto não muda a leitura da página, não faz parte do conteúdo.<br>

### Quando usar âncora ou button?

<p>Quando clicamos em um botão e ele redireciona para outra página, a melhor opção é âncora por questões de SEO.</p>
Quando o click ao botão executa apenas uma função, a melhor opção é usar a tag button mesmo.<br>

--- 

<p>Um truque para que o tamanho das unidades 'rem' seja equivalente ao de 'px' é definir
o html com 62,5%.
Desse modo o valor em píxel será sempre o valor definido em 'rem' vezes 10.</p>

```
html{
    font-size: 62,5%;
}

h1{
    font-size: 1.2rem;  //equivalente a 12px
}

p{
    font-size: 2.4rem; //equivalente a 24px
}
```

--- 

### Testes

Na prática do desenvolvimento de software, é crucial entender e aplicar diferentes tipos de testes para garantir a qualidade e confiabilidade do código. Aqui estão as principais diferenças entre três tipos de testes comuns: teste unitário, teste integrado e teste end-to-end (E2E):

1 - Teste Unitário:

 Definição: Teste focado em verificar o comportamento de unidades individuais de código, como funções, métodos ou classes, de forma isolada.
 Objetivo: Validar se cada unidade de código funciona conforme o esperado e produz os resultados corretos.
 Ferramentas no Angular: Para testes unitários em Angular, as ferramentas mais comuns são o Jasmine e o Jest. O Jasmine é um framework de teste de comportamento para          JavaScript amplamente utilizado. Já o Jest é uma estrutura de teste mais recente que oferece recursos adicionais, como snapshot testing e uma API de mocking mais avançada.

2 - Teste Integrado:

Definição: Teste que verifica a interação entre diferentes unidades de código, como componentes, serviços e módulos, para garantir que eles funcionem corretamente juntos.
Objetivo: Identificar e corrigir problemas de integração entre diferentes partes do sistema.
Ferramentas no Angular: Para testes integrados em Angular, as ferramentas Jasmine, Karma e Jest são comumente usadas. O Jest pode ser configurado para executar testes tanto unitários quanto integrados, tornando-o uma escolha versátil para ambos os tipos de teste.

3 - Teste End-to-End (E2E):

Definição: Teste que simula a interação do usuário com o sistema como um todo, desde a entrada de dados até a visualização dos resultados, através da automação de um navegador.
Objetivo: Verificar se o sistema funciona corretamente do ponto de vista do usuário, identificando problemas de usabilidade, integração e funcionalidade.
Ferramentas no Angular: Para testes E2E em Angular, as ferramentas mais comuns são o Protractor, Cypress e Playwright. O Protractor é uma escolha tradicional para testes E2E em aplicações Angular, enquanto o Cypress e o Playwright são opções mais modernas e poderosas, oferecendo uma sintaxe amigável e uma ampla gama de recursos para automação de testes em navegadores.

Esses três tipos de testes desempenham papéis distintos na garantia da qualidade do software e são cruciais para o desenvolvimento de aplicações robustas e confiáveis em Angular. Ao aplicar uma combinação adequada desses testes em seu projeto, você pode identificar e corrigir problemas em diferentes níveis de granularidade, desde pequenas unidades de código até a integração completa do sistema.
