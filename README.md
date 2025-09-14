Hola!, esto es un compilado de ejemplos básicos para ecribir en markdow, la forma más sencilla que encontramos hasta ahora es utilizando VSCode (por las dudas VSCode no nos paga nada, igual mal no estaría 😉 ), en donde podemos ver el texto raw y el final de manera simultánea.

![Vista Previa](imagenes/markdown_vistaprevia.png "Se puede activar la vista previa con el incono de lupa sobre el archivo que estamos procesando")

A lo largo del documento, indicaremos el formato y a continuación la salida para tener la referencia, puedes también desargar el README.md y analizarlo directamente en tu VSCode. 
cuando veas la barra '/' esta está para eliminar el formateo de markdown y asi veas como se coloca el texto plano para que, en este caso github, lo formatee.
Cualquier mejora o formato que se nos haya pasado por algo no dudes en contactarnos.



# Títulos
los títulos se generar colocando '#' delante del renglón, a medida que agreges más '#' iras incrementando el nivel del subtítulo

/ # 🧰 Esto es un título de 1er nivel (1 #)  
# 🧰 Esto es un título de 1er nivel (1 #)

/ ## SUBTÍTULOS: Esto es un título de segundo nivel (2 #)  
## SUBTÍTULOS: Esto es un título de segundo nivel (2 #)

/ ### y así sucesivamente (3 #)  
### y así sucesivamente (3 #)


Esto es texto normal
si solo apretamos enter no genera un salto de linea

hay que dar dos enter para un salto de línea pero queda separado.

Si queremos que dos líneas queden juntas hay que dejar 2 espacios al final de la oración  
y luego apretar enter.

Se puede destacar \`parte\` de una oracion poniendola entre " \` "  
Se puede destacar `parte` de una oracion poniendola entre " \` "  
(acento grave o invertido)

## Resaltar Texto
Para resaltar el texto utilizar * a cada lado.  

2 veces a cada lado para texto en \**negrita**  
2 veces a cada lado para texto en **negrita**  
1 vez a cada lado para texto en \*cursiva*  
1 vez a cada lado para texto en *cursiva*  
3 veces a cada lado para texto en \*\**\*negrita y cursiva****  
3 veces a cada lado para texto en ***negrita y cursiva***  

## Citas
Para citas se utiliza ">" al inicio de la cita  

/> Texto citado de alguien  
/> muy famoso

> Texto citado de alguien  
> muy famoso


## Imagenes
* Se tiene que indicar el texto que aparece si la imagen no se encuentra,  
* el link a la imagen, (puede ser dentro del repo o web) 
* y un texto descriptivo que se muestra cuando se pasa el mouse por arriba  

\!\[Robot aprendiendo markdown]\(imagenes/gemini_robotLibro.jpg "Esto aparece si pasas el mouse por arriba de la imagen")  
\> Imagen generada por un modelo de IA de Google>

![Robot aprendiendo markdown](imagenes/gemini_robotLibro.jpg "Esto aparece si pasas el mouse por arriba de la imagen")  
> Imagen generada por un modelo de IA de Google  

Se puede colocar un `hipervínculo` a una imagen  

\[![Robot GitHub]\(imagenes/gemini_robotPC.jpg "Visita nuestro GitHub!")]\(https://github.com/ec4lab/LandPAge)  
\> Imagen generada por un modelo de IA de Google 

[![Robot GitHub](imagenes/gemini_robotPC.jpg "Visita nuestro GitHub!")](https://github.com/ec4lab/LandPAge)  
> Imagen generada por un modelo de IA de Google 

## Líneas  

Podemos hacer una línea colocando 3 " - " seguidos

\---

---

El texto arriba de una línea queda grande
---

## Código

Podemos formatear un párrafo como código poneando 3 " ` " antes y después del párrafo.

Código sin formato:
```
#Comentario del código
C:\Users\VsCode\Programas\ejemplo_git
```

Podemos indicar el tipo de código inmediatamente después de los 3 " `" superirores:

Código en consola (bash):  
```bash
#Nos movemos a la carpeta del proyecto
cd C:\Users\VsCode\Programas\ejemplo_git
#Creamos el entorno virtual ".venv" técnicamente podría tomar cualquier nombre, pero es una buena práctica utlizar .venv
python -m venv .venv #en Ubuntu
```
Código python:
```python
import pandas as pd
#comentario de python
def main():
    print('Hola mundo')
```

## Tablas:
Se hacen poniendo " | "

| Licencia     | Qué permite                                   | Ideal si...                          |
|---|---|---|
| MIT          | Cualquiera puede usar/modificar/comercializar | Querés algo libre y flexible         |
| GPLv3        | Libre, pero obliga a compartir mejoras        | Querés que las mejoras sean públicas |
| Apache 2.0   | Como MIT, pero protege contra patentes        | Proyecto serio o empresarial         |
| Sin licencia | Legalmente, nadie puede usar tu código        | Lo dejás para vos                    |

Se puede alinear el texto dentro de cada columna colocando " : " en la fila de las líneas:  
|>>si ponemos nada<<|>> si ponemos " : " a ambos lados <<|>> si ponemos " : " al final <<|
|---|:---:|---:|
|izquierda|centrado|derecha|


## Listas
solo hay que iniciar la oración con " * "  
* item 1
* item 2
* item 3


---

## 📫 Hypervínculos
Muchos ejemplos que se ven aquí fueron tomados de tutotialmarkdown.com

Tutorial sintaxis de Markdown [tutorialmarkdown.com](https://tutorialmarkdown.com/sintaxis)


## 📝 Licencia

Este proyecto está licenciado bajo la Licencia MIT.  
Podés usar, copiar, modificar y distribuir el software libremente, siempre que incluyas el aviso de derechos de autor original.

Para más información, consultá el archivo [LICENSE](LICENSE).

---

## 📫 Contacto

**EC4lab**  
[GitHub: ec4lab](https://github.com/ec4lab)

---