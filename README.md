# examenDAM

Primero inicializamos git

git init

A continuación clonamos el repositorio

git clone -o examenDAM

Nos metemos dentro

cd examenDAM

Una vez dentro podemos ver los repos configurados con

git remote -v

Llegados aquí subimos el repo clonado a nuestro repositorio

git remote add origin https...

git branch -M main

git push -u origin main

Para cambiar el nombre a un commit primero hacemos un commit con normalidad

git commit

A continuación cambiaremos el nombre con 

git commit --amend --author "Pepito <pepito@gmail.com>"

```mermaid
flowchart TD
A((Inicio)) --> B(int numero = 0)
B --> C{"while (numero < 10)"}
C -->|Si| D('introduce un número')
D --> E["numero = resposta.nextInt()"]
E --> G('o numero = ' + numero)
G --> C
C -->|No| F((Fin))
```
