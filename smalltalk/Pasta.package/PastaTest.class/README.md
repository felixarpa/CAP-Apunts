# Pasta

### setUp

Abans de crear el metode a la classe integer `euro` per crear instancies de Pasta.

```smalltalk
setUp
```

A la classe integer afegim el nou metode:

```smalltalk
euro ^
	Pasta moneda: 'EUR' quantitat: self
```

Que retorna una instancia de pasta quan li passes el missatge `euro` a un *Integer*

```smalltalk
setUp
```

### testIguals

```smalltalk
testIguals
```

### testSuma

```smalltalk
testSuma
```