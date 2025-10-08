---
id: 1737841652-com-trabaja-react
aliases:
  - ¿Comó trabaja react?
tags: []
---

# 02 ¿Comó trabaja react?

React funciona de la siguente manera:

Nuestra aplicacción contiene un DOM
(Document Object Model) donde
se motarás nuestros componenetes pero además,
tendremos un DOM virtual, que significa esto?
que tendremos una copia de nuestro DOM original, pero
para que es esto?, la forma en que trabaja react es que
cuando hay un trigger en nuestra aplicación, como puede ser
un botón una llamada a una API o algo que nos haga cambiar la UI
react comparará los cambios del DOM Virtual y con los del DOM,
para poder detectar que parte de la aplicaciones es lo que
se modifico, una vez lo identifica este creará un commit
aplicandolo al DOM y evidentemente el cambio de UI al usuario,
basicamente asi es como va funcionar React.

Ejemplo:
Nos encontramos en un restaurant, y llega un cliente (Trigger) y
dice quiero un plato de chilaquiles, hace que el mesero valla con el cocinero
y prepare el platillo (Comparando el esto inicial, restaurante vacio con el
final, restaurante con cliente y cocinero) el cocinero prepara el platillo
(Proceso interno del componente) y le da el platillo al mesero, este lo lleva
al cliente y así se crea un (Commit).
