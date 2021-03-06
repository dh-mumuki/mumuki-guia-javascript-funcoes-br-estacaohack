E o que podemos fazer que não seja matemática? Podemos trabalhar com **strings**!
E se você se recorda, as **strings** são um tipo de dados. Representamos as cadeias de texto escrevendo dentro de aspas (“ “) literalmente.

E o que podemos fazer então com as strings? Por exemplo, podemos calcular quantos caracteres existem no total, e para isso iremos utilizar um recurso chamado length, onde colocamos a **string** seguida de `.length`. Veja alguns exemplos:

```javascript
 "biblioteca".length // devolve 10
 "babel".length  	// devolve 5
```
E lembre-se que também podemos somar **strings**!
Embora que, o termo correto seja **concatenar**, ou seja,  obter uma nova string juntando duas ou mais **strings**.

```javascript
 "aa" + "bb"   	// devolve "aabb"
 "aa" + " " + "bb" // devolve "aa bb"
```

> Vamos testar: Iremos criar uma função chamada **tamanhoNomeCompleto**, que recebe um nome e um sobrenome como **parâmetros**, e que irá devolver o tamanho total, contando um espaço extra para separar ambos:

```javascript
tamanhoNomeCompleto("Enzo", "Silva")
//  devolve 10
```
