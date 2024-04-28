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
