<p align="center">
    <img src="https://user-images.githubusercontent.com/8560750/195950148-0c0df38e-5f96-45ae-87c3-6922738c612d.jpg" alt="Logo" width=1200 height=300>

  <p align="center">
    Ingenieria en Desarrollo y Gestion de Software - GIDS4102
    <br>
  </p>
</p>


## Contenido

- [Prototipos](#prototipos)
- [Autores](#autores)


## Prototipos

### Prototipo 1 Movimiento del automovil
[Descargar Protipo 1](https://github.com/FernandoG-CreacionDeVideojuegosGIDS4102/ActividadesFundamentos/raw/main/Protipo%201.unitypackage)


1. Se realizo la creacion del prototipo 1 importando los assets proporcionados, colocando una camioneta en la ruta.

![image](https://github.com/user-attachments/assets/0989106a-5942-4d12-b88b-f300a91b9f96)

2. Se le agrego un srcipt al vehiculo con el proposito de tener movimiento y el componente de Rigidbody, este ultimo da como resultado que la camioneta tenga fisicas y pueda colisionar con objetos.

![image](https://github.com/user-attachments/assets/3ec5b7a5-fe34-4b73-88a3-a48cd0bd9e11)
![image](https://github.com/user-attachments/assets/e3ad6898-08a4-436f-ad56-eb93ecf07b28)

3. El codigo agregado mueve y gira la camioneta en Unity según las teclas del usuario, ajustando la velocidad y dirección en función de los inputs vertical y horizontal

![image](https://github.com/user-attachments/assets/d12a2d50-ece2-4d3e-a36c-e4207b787c6f)

4. Por ultimo se agrego un obstaculo con el componente Rigidbody para que pueda colisionar el vehiculo con el objeto.

![image](https://github.com/user-attachments/assets/ebd43b1f-04ae-45f4-9c4e-8c101dfbefc4)
![image](https://github.com/user-attachments/assets/84f6c9cc-5fbb-4db3-b2cd-7c491b0ed3bc)

5. Funcionalidad del prototipo 1
 
https://github.com/user-attachments/assets/d9b9bd1b-b949-4fa5-9b21-5f422c862819

### Prototipo 2 Movimiento y eliminar enemigos

[Descargar Prototipo 2](https://github.com/FernandoG-CreacionDeVideojuegosGIDS4102/ActividadesFundamentos/raw/main/Prototipo%202.unitypackage)

1. El prototipo 2 consistia en agregar a un personaje y otros assets como animales o comida, despues de esto agregar el movimiento y ademas darle la funcionalidad al personaje de "disparar" y eliminar a los enemigos.

![image](https://github.com/user-attachments/assets/c34905a9-f9d3-4614-a15b-b5a06db01a97)

2. Al conjunto de animales se le agregaron los componentes:

  - **Box Collider**: El cual define una colisión en forma de caja alrededor del objeto, servirá para detectar la interacción física del proyectil enemigo.

![image](https://github.com/user-attachments/assets/a1facb30-5a98-4ee9-98fa-7e481115228b)

- **Script Detecta colisión**: Detectará la colisión entre dos objetos, el proyectil y el enemigo. Después de esto, eliminará ambos objetos al momento de la colisión.

![image](https://github.com/user-attachments/assets/192a8f5d-f201-4eef-9c6b-6bd3636c1e70)

- **Script Move**: Este script moverá a los animales continuamente hacia adelante (en el eje Z) y los destruirá si su posición en el eje X se sale de los límites (-21 y 23).

![image](https://github.com/user-attachments/assets/c9e5104a-cb06-4984-a2c2-b992fb6fa1a3)

3. A la pizza, la cual seria el proyectil se le agregaron los componentes:

- **Box Collider**: El cual define una colisión en forma de caja alrededor del objeto, servirá para detectar la interacción física del proyectil enemigo.

![image](https://github.com/user-attachments/assets/a1facb30-5a98-4ee9-98fa-7e481115228b)

- **Script Detecta colisión**: Detectará la colisión entre dos objetos, el proyectil y el enemigo. Después de esto, eliminará ambos objetos al momento de la colisión.

![image](https://github.com/user-attachments/assets/192a8f5d-f201-4eef-9c6b-6bd3636c1e70)

- **Script Move**: Este script moverá a los animales continuamente hacia adelante (en el eje Z) y los destruirá si su posición en el eje X se sale de los límites (-21 y 23).

![image](https://github.com/user-attachments/assets/c9e5104a-cb06-4984-a2c2-b992fb6fa1a3)

- **Rigidbody**: Este componente define los límites de colisión, y en conjunto con los scripts controla el movimiento y las interacciones, permitiendo que los objetos interactuen físicamente.

![image](https://github.com/user-attachments/assets/04d5c839-0913-4498-8c0e-28a5707b5256)

4. Para el personaje principal se le aplicaron los siguientes componentes:

![image](https://github.com/user-attachments/assets/afde2704-a45f-4b9b-905e-7947bd96c97a)
![image](https://github.com/user-attachments/assets/40228040-a280-494a-bb91-2112f30f3475)

**Script PlayerController**: Permite al jugador moverse horizontalmente en la pantalla y restringe su movimiento vertical dentro de un área definida en el eje Z. Además, permitira disparar proyectiles cada vez que se presiona la barra espaciadora.

![image](https://github.com/user-attachments/assets/f9ce93b4-65f3-4e19-bc40-fbcf98884f16)

- **Script CreaAnimales**: Este script genera animales en una posición aleatoria a lo largo del eje Z cada 2 segundos.

![image](https://github.com/user-attachments/assets/d6ce62fa-e61f-4d29-bc4d-0dcb7ae5e5eb)

5. Funcionalidad del prototipo 2

https://github.com/user-attachments/assets/a3eb9ead-37f0-40c4-8c28-39cedbc2fd5b

## Autores
Jesus Fernando Gonzalez Pedroza
