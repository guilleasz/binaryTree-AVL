# Arbol AVL


Arbol binario auto balanceado hecho en Javascript.

## Crear un arbol

```javascript
tree = new ArbolBinario()
```

## Agregar Elementos

```javascript
tree.add(5)
```

## Eliminar Elementos

```javascript
tree.delete(5)
```


## Buscar Nodo

```javascript
tree.search(5)
```


## Navegar en el Arbol

El árbol tiene una propiedad root donde se coloca el primer valor. Los nodos tienen propiedades left y right para ir para la izquierda o derecha del arbol.


## Auto Balanceo

Cada vez que elimines o agregues un elemento el arbol va a chequear que se encuentre balanceado, y si no se va a balancear por si solo.
