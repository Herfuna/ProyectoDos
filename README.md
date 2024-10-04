# Diagrama de Clases:
![image](https://github.com/user-attachments/assets/7574c473-92f8-42ac-989f-c901387cce5b)

# Como Funciona?
se podria decir que funciona a base de arrays/vectores que hacen el trabajo mas facil, y que con ellos se pueden separar los datos de una manera mas sencilla de entender, en especial cuando se asignan las notas a los textfields

# Botones:
![image](https://github.com/user-attachments/assets/df3ad8ac-67e4-4724-ab3c-5aa1e60cd4ec)

# Boton Atras (<<)
El boton funciona dependiendo del indice que tiene la ventana en la parte superior izquierda, ya que ese se vincula con el ID del alumno, haciendo que los datos de dicho alumno se muestren

# Boton Siguiente (>>)
De la misma forma que el boton atras, dependiendo del indice este mostrara los datos que estan en relacion con el ID de ese alumno

# Boton Calcular Promedio:
Calcula el promedio de cada materia y asigna las notas correspondientes a cada texfields, si el programa detecta que una de estas casillas esta vacia, no podra continuar hasta que se llenen todos los campos


# Boton Guardar:
Obtiene los datos correspondientes, en su mayoria usa arrays, se conecta a la base de datos e inserta los datos validando si ya existe o no, si todo sale bien se mostrara un mensaje diciendo que se ha guardado correctamente

# Base de datos:
![image](https://github.com/user-attachments/assets/c73c3628-b91f-4b75-827a-a8faa582690a)
se compone de tres tablas, una de alumnos, materia y notas
LLave primaria: Id_Alumno, Id_Materia, Id_Notas
Llave foranea: id_Alumno, id_Materia, id_Notas
