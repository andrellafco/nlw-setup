#HTML

Hypertext Markup Language

# 1. Tag

- Elemento

# 2. Attributes

- Configurações do elemento

# CSS

Cascading Style Sheets
Folha de estilo em cascata 

# 3. Declarations 

- propriedade e valor

## O que é HTML?

- Estruturar textos, criar links, imagens, vídeo, etc ...
- Hypertext Markup Language
    
    Linguagem de marcação de texto
    

---

## Hypertext

- Hipertexto
- Texto que contém links

---

## Markup

- Marcação do texto
- Elemento HTML ou **`tag`**
    
    Existem inúmeras tags e cada uma deles irá servir para um determinado propósito. Ex.: imagem, texto grande, link, parágrafo, etc...
    

---

## Sintaxe de uma tag

Como escrevemos tags HTML?
<p>conteúdo</p>
<!-- Aqui vem um comentário -->

## Atributos

Adicionam informações e/ou configurações à uma tag

Como escrevemos atributos?
<a href="https://rocketseat.com.br">Ver site</a>
<img src="image.jpg" />


## O que é CSS?

- Estilos para o HTML
- Cascading Style Sheets
    
    Folha de Estilo em Cascata
    
- Apresentação visual para o cliente

## Declaration

- **Declaração**
    
    Pedaço de código que irá ditar as propriedades e valores a serem aplicadas a um elemento HTML
    
- Como escrevemos ?
body {
  background: black;
	/* color: green; Essa linha será ignorada */
}

## Cascading

- **Cascata**

    Quando há 2 (ou mais) declarações a última será mais relevante
body {
  background: red;
}

body {
  background: blue;
}

## Specificity

- Especificidade

    Cada seletor tem um peso e a soma dos pesos, será levada em conta para que determinada declaração seja mais específica

#id {
  /* peso 100 */
}

.class {
  /* peso 10 */
}

element {
  /* peso 1 */
}

*A cascata perde prioridade e é priorizada a especificidade da declaração*


## Box Model

- **Tudo são caixas**

    Todos os elementos HTML serão considerados uma caixa, assim como uma caixa de papelão

- **Caixas possuem determinadas propriedades**

    Conteúdo, Largura, Altura, Borda, Preenchimento (espaço interno), Espaçamento (espaço externo)  