# universidad-2019-2020

Trabajo de ingenieria mecatronica realizado entre septiembre de 2019 y abril de 2020
en el **Instituto Tecnologico de Los Mochis**, durante la carrera de Ingenieria
Mecatronica.

Complementa el repositorio [`arduino-sketches`](https://github.com/luisgr95/arduino-sketches),
que cubre el trabajo de electronica del mismo periodo.

## labview/

Instrumentos virtuales (`.vi`) de LabVIEW, febrero y marzo de 2020.

| Archivo | Tema |
|---|---|
| `PRACTICA 1 DIGITOS BINARIOS Y TEOREMA DE PITAGORAS.vi` | Representacion binaria y calculo de hipotenusa |
| `PRACTICA 2 CONVERSION DE UNIDADES DE TEMPERATURA.vi` | Conversion entre escalas termometricas |
| `PRACTICA 3 CONTROL DE NIVEL DE TANQUE.vi` | Control de nivel de liquido en tanque |
| `PRACTICA 4 COMPUERTAS LOGICAS BASICAS.vi` | Compuertas logicas fundamentales |
| `PRACTICA 5 DIVISOR DE VOLTAJE.vi` | Divisor resistivo de tension |
| `ejercicicio1.vi`, `Untitled 2.vi` | Ejercicios sueltos |

## inventor/

Modelado CAD de la materia **Diseno Mecanico Asistido por Computadora**: 46 piezas
(`.ipt`) y 3 ensambles (`.iam`) correspondientes a las practicas 1 a 23 y al examen
de la Unidad I.

## Un hilo entre materias

La **Practica 3 de LabVIEW** (control de nivel de tanque) aborda el mismo problema que
el sketch `Tanque/tanque.ino` del repositorio `arduino-sketches`, fechado en septiembre
de 2019: alli se resuelve con un sensor ultrasonico HC-SR04 calculando volumen, y aqui
con instrumentacion virtual. Son las dos caras del mismo ejercicio de control.

## Que no esta incluido

Los reportes de practica en Word y PDF **no forman parte de este repositorio**. Su
encabezado incluye numero de control y el nombre del docente, datos personales que no
corresponden a un repositorio publico. Se conservan localmente.

Tambien se excluye `p23.rar`, un comprimido de la practica 23 cuyo contenido puede
incluir esos mismos reportes.

## Requisitos para abrir los archivos

- Los `.vi` requieren **LabVIEW 2017** o posterior.
- Los `.ipt` y `.iam` requieren **Autodesk Inventor 2020** o posterior.

Ambos son formatos binarios propietarios: Git los versiona pero no puede mostrar
diferencias entre versiones.