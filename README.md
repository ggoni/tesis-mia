### Documento TESIS: 

Mantener actualizado [acá](https://alumnosuaicl-my.sharepoint.com/:w:/r/personal/ggoni_alumnos_uai_cl/_layouts/15/doc2.aspx?sourcedoc=%7B3EB12E04-6A5E-4680-B63F-8B77F0FF0628%7D&file=Template%20Tesis%20MIA%20UAI%20-%20v2.docx&action=default&mobileredirect=true&DefaultItemOpen=1&ct=1638016116577&wdOrigin=OFFICECOM-WEB.MAIN.OTHER&cid=3c25bc43-160a-4968-a13b-e21ed8c13e57)

# Comentarios Profesor

## Entrega lunes 30 de septiembre

Comentarios Antes:


```

Estimados Estudiantes,

  Se les recuerda que los comentarios específicos a los grupos se encuentran disponibles en la plantilla:

https://docs.google.com/spreadsheets/d/1kt3splYqrS1f0xT7pj9rioXPm0H0niWQCgDzCMge9Bs/edit#gid=0

Además, algunos comentarios generales más bien metodológicos:

 

El trabajo debe tener claramente diferenciado y especificado el (1) modelo/método de solución de la (2) METODOLOGÏA DE 
EXPERIMENTACiÖN (i.e., pasos que un tercero debería seguir para reproducir sus experimentos) sobre cómo Uds utilizan 
SU modelo/método/técnica para probar sus respectivas hipótesis. Me fijé que en varios trabajos esto no es muy claro. 
Para aclarar, sigan la siguiente analogía:
Por ejemplo: 

           Ténica/modelo de Solución: Nosotros  desarrollamos una nueva vacuna para el covid-19 basada en la técnica M 
           modificada ...

           Metodología de experimentación (para probar la(s) hipótesis): Mire, para probar   la nueva vacuna basada en 
           la técnica M, seguimos la siguiente metodología de experimentación:

                   a) Recolectar datos de experiencias pasadas para contrastar, etc etc

                   b) Conseguir voluntarios para la vacunación. Dividir en grupos de     

                      control y prueba.

                   c) Programar la vacunación  (logística, tránsporte, disponibilidad de

                        insumos, etc).

                   d) Aplicar la vacuna con la técnica M

                  e)  Monitorear a los pacientes y realizar pruebas de anticuerpos, etc etc

                   f) Realizar los análisis y comparaciones

                   g) Validar la(s) hipótesis

                   h) Publicar resultados

Si Uds. se fijan, la metodología experimental para probar la vacuna es casi la misma para  todos los fabricantes. 
Sin embargo, el aporte (y diferencia) está en el paso (d) que es donde se aplica la nueva técnica M contra el 
covid-19. Más aún, si esto fuera innovación, es la técnica la que se patenta, 
no la metodología de experimentación. Por tanto, el aporte del laboratorio que la fabrica no está en la metodologia 
experimental sino en la nueva fórmula o técnica que desarrolló!!. Espero que esta analogía les sea útil para 
"austar" sus respectivos trabajos.

Se recomienda que en alguna slide agreguen algún párrafo explícito (especialmente para la defensa) que mencione el 
aporte o valor agregado del trabajo de Uds.  Las presentaciones hablan de varios temas (y son MUCHAS defensas), 
entonces es altamente probable que la comisión olvidé a veces dónde está la contribución (o diferencias) de sus 
tesis.  En algunas presentaciones esto salta a la vista mientras que en otras, no es tan evidente, de ahí que es 
mejor asegurarse y explicitarla(s).

```

Comentarios Después

```


En general, se aprecian los siguientes problemas generales:

Muy mala redacción y organizacion de los informes.
Se debe incluir un RESUMEN inicial de 200 palabras (aprox).
Varios documentos sobrepasaron el largo informado inicialmente: 20 paginas. Puede haber holguras, sin embargo, algunos documentos aún no terminan y ya contienen más de 40 páginas.
Numerar las secciones y sub-secciones para entender qué está dentro de qué.
Formatear con el estilo que corresponde la bibliografía (NO links). Se recomienda estilos como APA o similar: https://apastyle.apa.org/style-grammar-guidelines/paper-format/sample-papers
Dentro de la sección en que se describe la "solución" debe explicarse en algpun párrafo, el "aporte" o "diferencias" del trabajo.
En la sección de la "solución" se recomienda comenzar con una explicación general del enfoque, sus principales ideas, supuestos, etc 
y LUEGO los detalles correspondientes. De lo contrario, no se entiende el documento.

```

## Detalle feedback lunes 30 de septiembre



- Comentarios [acá](https://docs.google.com/spreadsheets/d/1kt3splYqrS1f0xT7pj9rioXPm0H0niWQCgDzCMge9Bs/edit#gid=0)




# Pendientes al 10/10/21

- [X] Aumentar fotos: muy pocas con daño=0
- [x] Revisar [Redimensionamiento imágenes](https://auth0.com/blog/image-processing-in-python-with-pillow/)
- [X] Elegir versión del modelo
- [ ] Preguntas a Gonzalo Ruz:
1. *¿Es razonable pasar los montos a daño a un factor del valor inicial?* 

    Sí
    
2. *¿Qué aspectos debiésemos tener en cuenta al convertir el modelo de regresión a clasificación?*
3. _¿Vale la pena hacer lo anterior? Por el momento estamos usando uno de **regresión**_
4. *Queremos demostrar/descartar que en este tipo de problemas un modelo que usa inputs "tabulares" + imágenes es más acucioso que un modelo que solo usa imágenes ¿Comentarios?*
5. *¿Cuántas veces deberíamos correr la comparación para considerar que hemos encontrado una diferencia significativa?*

    Está OK con 100 y uso de test t
6. <s>Hay solo 93 fotos de vehículos sin daño, lo que nos deja con un dataset desbalanceado ¿Cuáles serían estrategias más razonables para llegar a 400?</s>
7. *Es sensato realizar tratamiento previo de imágenes para mejorar el resultado?* No se recomienda, por tiempo disponible
8. *Hace sentido para la Tesis utilizar transfer learning para capas iniciales?*

    Puede ser, más razonable modelo "tradicional" como línea base. Es más recomendable ajustarse a tiempo disponible y no llenarse de hipótesis.
9. *Deberíamos incluir en la Tesis el caso de las casas como punto de partida de nuestro estudio?*

    Sí, mencionarlo explícitamente


# Sugerencias

- [X] Usar un modelo "tradicional" para base de comparación (Revisar una comparación: Muy probablemente, se va a preguntar con "solo datos")

- [X] Revisar parámetros en importancia relativa

- [ ] Desarrollar tema de workflow

- [ ] Incluir explicación de métricas

