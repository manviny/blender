# blender

## TEMA 0. Instalar Blender en Lliurex

#### Mirar PCs conectados
- nmap -sP 10.2.1.1/24 | grep 'report' | cut -d' ' -f5
#### Conectar a un PC
- ssh lliurex@10.2.1.171
#### Instalar
```
sudo add-apt-repository ppa:thomas-schiex/blender
sudo apt update
sudo apt install blender
```
```
sudo add-apt-repository ppa:thomas-schiex/blender && sudo apt update && sudo apt install blender
``` 



## TEMA 1

## Introducción
## Áreas
## Menús

- Ctrl + space  ->  agranda el area actual
- Ctrl + tab    ->  menu tarta


## Entorno
## Navegación
## Preferencias
## Modo Objeto
## Transformaciones
## Primitivas
## Jerarquía

## TEMA 2

## Modo edición

## Extrusión
- Al pulsar **E** creamos una nueva cara, esta queda en la malla aunqué no realicemos ninguna trasformación sobre ella  

<img src="https://raw.githubusercontent.com/manviny/blender/main/assets/extrusion.png" width="480">

## Edición proporcional
- Trabajo sobre mallas o retículas mediante el **modo proporcional**

<img src="https://raw.githubusercontent.com/manviny/blender/main/assets/edicion_proporcional.png" width="480">

## Un/Join objects
#### join objects
- select objects to join
- **ctrl+J** -> se unen las dos mallas en un solo objeto
#### Unjoin objects
- choose a point in one of the objects, **ctrl+L** (linked) to choose the whole linked object
- **P** (separate, part)
- Choose Selection
- Igualmente se pueden __separar caras de un objeto__

## Bucles y anillos
- En una esfera, seleccionar un punto y con la tecla **option** apretada, seleccionar una arista contigua. Esto selecciona todo el anillo. Funciona igualmente para aristas y caras.
- Manteniendo **shift** podemos seleccionar multiple aristas o caras

<img src="https://raw.githubusercontent.com/manviny/blender/main/assets/seleccion_anillo.png" width="480">

- **Loop Cut**  **cmd+R** wheel
- Permite cortar un objeto y ampliar número de cortes desde la ventana flotante
<img src="https://raw.githubusercontent.com/manviny/blender/main/assets/loopcut.png" width="480">

## Herramientas de edición

## Knife

## Bevel

## TEMA 3


## Modificadores

## Mirror

## Subsurf

## Array

## Materiales

## Asignación de material

## Vertex paint

## 

## 









