
# Machine Learning Operations

## Introducción 

En este articulo utilizaremos diversas herramietnas como Python para realizar algunos ejercicios que serán utiles para aprender los conceptops profundos que se verán más adelante.



| Concepto      | Descripción     |
|---------------|-----------------|
| Variable      | Una ubicación con nombre en la memoria que almacena un valor. Las variables no tienen un tipo explícito y pueden reasignarse.                     |
| Asignación    | El operador `=` establece un nombre de variable a un valor.                                                                                     |
| Cadena f      | Literales de cadena formateados que permiten expresiones incrustadas utilizando la sintaxis `f"..."`.                                            |
| Entero        | Número entero positivo o negativo sin punto decimal. Admite operaciones matemáticas.                                                             |
| Float         | Número con punto decimal. Común para mediciones y operaciones matemáticas con fracciones.                                                         |
| Booleano      | Un valor `True` o `False` utilizado a menudo para la lógica.                                                                                     |
| None          | No representa ningún valor asignado. Comúnmente visto como un valor de retorno por defecto.                                                       |
| if            | Inicia un bloque condicional que se ejecuta si la condición es verdadera.                                                                        |
| else          | Añade un bloque que se ejecuta si la condición `if` anterior era falsa.                                                                          |
| Excepción     | Errores que interrumpen el flujo normal del programa. Se utiliza para atrapar y manejar errores.                                                 |
| try/except    | Estructura que atrapa excepciones: primero ejecuta el código en el bloque `try` y, si ocurre un error, lo maneja en el bloque `except`.         |



```bash
#print try some of these key terms out
# Variable to store a value
name = "John"  

# Reassign variable
name = "Jane" 

# f-String prints variable 
print(f"Hello {name}")

# Integer
num = 10  

# Float 
dec = 10.5 

# Boolean
is_true = True

# None 
empty = None

# If condition evaluates the Boolean
if is_true:
  print("Condition was true")

# Else catches when if was False  
else: 
  print("Condition was false")
  
# Try block attempts this code
try:
  result = num / 0
# Except catches the ZeroDivisionError   
except ZeroDivisionError as e:
  print("Cannot divide by 0")

```


