# <img src = https://d33wubrfki0l68.cloudfront.net/f1f475a6fda1c2c4be4cac04033db5c3293032b4/513a4/assets/images/markdown-mark-white.svg  width = 50> **Guia Básico de Markdown** 
 Nada muito complicado, só o que você precisa para deixar seus READMEs mais organizados.

 #
## **Sumário**
[Titulação](#titulação)

[Enfâses](#ênfases)

[Links](#links)

[Listas](#listas)

[Códigos](#código)

[Imagens](#imagens)

[Tabela](#tabela)
#
#
## **Titulação**

Os títulos são marcados pelas '#', por exemplo: 

```
# Título 1 
## Título 2
### Título 3
#### Título 4
##### Título 5
```
# Título 1 
## Título 2
### Título 3
#### Título 4
##### Título 5

#
#
## **Ênfases**

- **Negrito**: Colocamos o texto entre asteriscos ou underlines duplos 
```
**Exemplo** ou __Exemplo__
```
- *Itálico*: Colocamos o texto entre asterisco ou underline
```
*Exemplo* ou _Exemplo_
```
- ***Também podemos usar as duas enfâses:***
```
***Exemplo*** ou ___Exemplo___
```
#
#

## **Links**

- **Links Titulados**:  
```
[]() - [Título do link](aquitucolocaolink.com)
```
- **Links Diretos**
```
<> - <aquitucolocaolink.com>
```
- **Links Âncora** : Links como o do sumário desse guia
```
[]() - [Título do Link](#titulo-minusculo-separado-por-hifen)
```
Exemplo Titulado: [Clique aqui para ver que é real!](https://portaldoscaesegatos.com.br/wp-content/uploads/2016/08/eurosaurus-20.jpg)

Exemplo Direto: google.com

Exemplo Âncora: [Sumário](#sumário)
#
#

## **Listas**

- **Tópicos**
```
- Item 1
    - Item 1.1
    - Item 1.2
- Item 2
- Item 3
```
### Exemplo : 
- Item 1
  - Item 1.1
  - Item 1.2
- Item 2
- Item 3
#
  
- **Lista Numerada**
```
1. Item 1
2. Item 2
3. Item 3
```
Exemplo : 
1. Item 1
2. Item 2
3. Item 3

#
#
## **Código**

- Linha de código : Colocar a linha entre ` (acento grave)

` print("Hello World!")`

- Múltiplas linhas de código : Colocar a o conteúdo entre ``` (três acentos graves)
```
if(int i = 0; i<10; i++)
{
    printf(i);
    printf("\n");
}
```
- Podemos especificar a linguagem que será apresentada nas linhas de códigos escrevendo seu nome logo após os três acentos graves, por exemplo: ```python
```python
print("Esta é uma linha em python!")
```
#
#

## **Imagens**
```
![]() - ![Título da imagem](Link da imagem)
```
Exemplo :

![Logo do GitHub](https://camo.githubusercontent.com/f116befea219e410bfd127754d966c015c2562f776874928efae907452155a1d/68747470733a2f2f7777772e69636f6e66696e6465722e636f6d2f646174612f69636f6e732f6f637469636f6e732f313032342f6d61726b2d6769746875622d3235362e706e67)

#
#

## **Tabela**
```
Nomes | Valores | Qtd.    -> Colunas separadas por '|'
:----:|:-------:|:---:    -> Linhas que separam a legenda do conteúdo são feitas 
Produto 1 | R$ 1 | 1         com '---', os ':' alinham o texto das colunas, 
Produto 2 | R$ 2 | 2         quando colocados em apenas uma das laterais alinham
Produto 3 | R$ 3 | 3         pela esquerda ou direita, e quando colocado nas 
Produto 4 | R$ 4 | 4         duas laterias centralizam o texto
```
Exemplo : 
Nomes | Valores | Qtd.
:----:|:-------:|:---:
Produto 1 | R$ 1 | 1
Produto 2 | R$ 2 | 2
Produto 3 | R$ 3 | 3
Produto 4 | R$ 4 | 4