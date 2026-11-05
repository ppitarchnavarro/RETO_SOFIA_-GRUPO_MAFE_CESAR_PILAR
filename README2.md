
# 💻 RETO_SOFIA - GRUPO_MAFE_CESAR_PILAR

## 👥 Integrantes
- María Fernanda Pico Duque
- Pilar Elisa Pitarch Navarro
- César Renart Olivert

---

## 📌 Lenguaje: C
### Tema: Condicionales

En este reto analizamos las principales diferencias y similitudes entre **C y Python**, centrándonos en el uso de los condicionales.

## 1. ¿Cómo se declaran las variables?

- En **C** es necesario declarar el tipo de dato de cada variable (`int`, `float`, `char`, etc.).
- En **Python** no es necesario especificar el tipo de dato al declarar una variable.
- En C, cada instrucción debe terminar con un **punto y coma (`;`)**.

**Ejemplo en C:**
```c
int edad = 20;
float altura = 1.75;
```

## 2. ¿Cómo se delimitan los bloques de código?

- En **C**, los bloques de código se delimitan mediante **llaves `{ }`**.
- En **Python**, los bloques se definen mediante la indentación.
- En C, los espacios y las tabulaciones no determinan los bloques de código, aunque se recomienda utilizarlos para mejorar la legibilidad.

**Ejemplo en C:**
```c
if (edad >= 18) {
    printf("Eres mayor de edad");
}
```

## 3. ¿Qué cambia en la sintaxis respecto a Python?

Las principales diferencias son:

| Elemento | Python | C |
|---|---|---|
| Condicional | `if edad >= 18:` | `if (edad >= 18)` |
| Inicio de bloque | `:` e indentación | `{ }` |
| Fin de instrucción | Salto de línea | `;` |
| AND lógico | `and` | `&&` |
| OR lógico | `or` | `\|\|` |
| NOT lógico | `not` | `!` |
| Mostrar texto | `print("Hola")` | `printf("Hola");` |
| Comentario | `# Comentario` | `// Comentario` |

### Ejemplo comparativo

**Python:**
```python
edad = 20

if edad >= 18:
    print("Eres mayor de edad")
```

**C:**
```c
#include <stdio.h>

int main() {
    int edad = 20;

    if (edad >= 18) {
        printf("Eres mayor de edad");
    }

    return 0;
}
```

## 4. ¿Qué parte de la lógica se mantiene igual?

- El **flujo de ejecución** de los condicionales se mantiene.
- La **lógica booleana** funciona de la misma manera.
- Se utilizan condiciones que pueden evaluarse como verdaderas o falsas.
- Las estructuras `if`, `else if` / `elif` y `else` permiten tomar decisiones dependiendo de las condiciones.

---

## ✅ Conclusión

Aunque **C y Python tienen diferencias importantes en su sintaxis**, la lógica de programación es prácticamente la misma.

La principal diferencia es que **C requiere una sintaxis más explícita**, como declarar los tipos de variables, utilizar llaves para delimitar bloques y finalizar las instrucciones con punto y coma.
