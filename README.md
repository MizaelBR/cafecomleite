# Repositorio Cafe com Leite

Este repositorio é para teste de git e github, e sera apagado em breve!

## Ensinando um pouco de Markdown

Markdown é uma linguagem de marcação, feita para organizar conteudo, como html.  
Ela usa comando mais simples do que o html e o github usa-o para que os usuarios descreva seus trabalhos com titulos,  
link e imagens.  
Irei demostrar um pouco dos comandos que sei. Caso tenha curiosidade deixarei um link para saber mais sobre,  
mas abordarei tudo um pouco aqui.  
E se voce entrar acessar o arquivo README.md que mostra este mini-tutorial, vera que é feito em Markdown!

**Are you READY?**

## Titulos

Para fazer titulos voce usa o #.  
Se colocar # é o titulo principal.
se colocar ## o titulo seria um secundario e vai até o titulo com 6 #.
Exemplo

# Titulo

Este é feito `# Titulo`.

## Titulo

Este é feito `## Titulo`.

### Titulo

Este é feito `### Titulo`.

#### Titulo

Este é feito `#### Titulo`.

##### Titulo

Este é feito `##### Titulo`.

###### Titulo

Este é feito `###### Titulo`.

## Estilos em textos

Negrito coloca-se dois asteriscos ** ou dois underlines __.  
exemplo:  
**Negrito com asteriscos** e __negrito com underlines__  
`**Negrito com asteriscos** e __negrito com underlines__`

Italico coloca-se um asteriscos * ou um underline _.  
exemplo:  
*italico com asteriscos* e _italico com underline_  
`*italico com asteriscos* e _italico com underline_`

Voce pode fazer junção dos dois estilos:  
Oi, isto é **_cafe_** com **_leite_**?  
`Oi, isto é **_cafe_** com __*leite*__?`

## Links

Para fazer **links**, tem duas maneras.  
A mais facil é: `[Texto do link](Link.com)`

Ex.:
[google](google.com)  
`[google](google.com)`

A segunda manera é assim:  
Ex.:  
[Github da Daniella][daniella-link]

[daniella-link]: https://github.com/daniellamlima  

``` md
[Github da Daniella][daniella-link]

[daniella-link]: https://github.com/daniellamlima
```
## Imagens

O uso de imagens é parecido com o uso de links,  
a unica difetença é colocar uma exclamação no inicio.  
E da mesma forma tem dois modo de usar
Ex.:  
1. Primeira maneira: ` ![Titulo para imagem](https://octodex.github.com/images/Fintechtocat.png) `  
![Titulo para imagem](https://octodex.github.com/images/Fintechtocat.png)


2. Segunda maneira:  
```md
![Gif Octocat][Octogif]

[octogif]: https://octodex.github.com/images/hula_loop_octodex03.gif
```

![Gif Octocat][Octogif]

[octogif]: https://octodex.github.com/images/hula_loop_octodex03.gif

## Citação
Para citar uma frase ou um texto, basta usar "
maior do que (>)"
 no início das linha e dar um espaçamento depois.
Ex.:

> Lindo por do sol.  
> Brinda-nos neste dia.  
> Vira poesia.

```
> Lindo por do sol.
> Brinda-nos neste dia.
> Vira poesia.
```

Ao citar algo ele se destaca do resto do texto.

Outra citação:
> Obs.:  
> Ao usar o carro nunca esqueça do cinto de segurança.

## Tabela
Como fazer tabela no markdown.
Tabela tem as celulas de titulo e as de conteudos.
Irei fazer uma tabela de notas para este exemplo.

Nome | Nota 1 | Nota 2 | Média
----- | ----- | ----- | -----
Maria | 5 | 2 | 3,5
João | 7 | 1 | 3

```
Nome | Nota 1 | Nota 2 | Média
----- | ----- | ----- | -----
Maria | 5 | 2 | 3,5
João | 7 | 1 | 3
```
Vamos agora ajustar o texto dentro da tabela.
Para isto vamos usar "dois pontos (:)".

> Ajuste Esquerdo   :-----
> Centralizado         :-----:
> Ajuste Direita         -----:

Ex.:

Nome | Mercadoria | Valor
:----- | :-----: | -----:
Ana Maria | Ovos | R$ 12,00
João Paulo | Pão | R$ 2,00
Miguel Silva | Carne | R$ 20,00

```
Nome | Mercadoria | Valor
:----- | :-----: | -----:
Ana Maria | Ovos | R$ 12,00
João Paulo | Pão | R$ 2,00
Miguel Silva | Carne | R$ 20,00
```

_continua..._
