# Sprite de jardin de flores en Ensamblador
#sprite de un marciano en Ensamblador 

Este programa dibuja un sprite de un jardin de flores en un display de 16x16 píxeles y muestra el mensaje **"equipo los rafikis rifa mas que nadie"** en el display de texto. Está escrito en lenguaje ensamblador y es compatible con el simulador **ASM Simulator**.

## Descripción

El programa consta de dos partes principales:
1. **Mensaje en el Display de Texto**: Muestra el mensaje **"equipo los rafikis rifa mas que nadie"** en el display de texto.
2. **Sprite en el Display Visual**: Dibuja un sprite de un jardin de flores en un display gráfico de 16x16 píxeles.

## Código

El código está escrito en ensamblador y se divide en las siguientes secciones:
- **Datos**: Define el mensaje y el sprite.
- **Inicialización**: Configura el stack pointer y los punteros a los displays.
- **Subrutinas**: Incluye funciones para imprimir el mensaje y dibujar el sprite.

### Sprite de la Flor Roja

El sprite es una matriz de 16x16 píxeles, donde:
- `0x04` representa el color rojo.
- `0xFF` representa el fondo blanco.

### Mensaje

El mensaje **"equipo los rafikis rifa mas que nadie"** se muestra en el display de texto.

## Requisitos

- Simulador **ASM Simulator** (disponible en [ASM Simulator](https://parraman.github.io/asm-simulator/)).

## Autor

Santiago Maximiliano Vazquez Espinosa, Rafael Alejandro Hurtado Vasconcelos y Cristopher Ivan Lopez Duran

## version
1.0



