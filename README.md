# 📚 Curso de Python desde Cero 🐍  
Bienvenido/a al repositorio del **Curso de Python desde Cero**, donde aprenderás paso a paso los conceptos fundamentales de Python, uno de los lenguajes de programación más populares y versátiles del mundo.

Este curso está diseñado para quienes desean comenzar su camino en la programación o reforzar sus bases en Python.
Todo el curso completo se encuentra en los diferentes archivos incluidos en el repositorio, sin embargo, os dejo una breve descripción de cada apartado, el curso será ampliado mucho más en un futuro‼️

---

## 📋 Tabla de Contenidos  
1. [Introducción](#introducción)  
2. [Instalación de Python](#instalación-de-python)  
3. [Variables y Tipos de Datos](#variables-y-tipos-de-datos)  
4. [Operadores en Python](#operadores-en-python)  
5. [Estructuras de Control](#estructuras-de-control)  
6. [Listas y Diccionarios](#listas-y-diccionarios)  
7. [Funciones](#funciones)  
8. [Próximos Pasos](#próximos-pasos)  

---

## 📖 Introducción  
Python es un lenguaje de programación de alto nivel y propósito general, conocido por su legibilidad y simplicidad. Este curso te llevará desde los conceptos más básicos hasta la creación de funciones personalizadas.

---

## 🛠 Instalación de Python  
1. Descarga Python desde la página oficial: [https://www.python.org/downloads/](https://www.python.org/downloads/)  
2. Sigue las instrucciones de instalación para tu sistema operativo.  
3. Verifica la instalación ejecutando el siguiente comando en la terminal:  
   ```bash
   python --version
   ```

---

## 🧮 Variables y Tipos de Datos  
En Python, una variable es un espacio de memoria donde almacenamos información. Existen diferentes tipos de datos como números, cadenas de texto, y booleanos.

### Ejemplo:  
```python
# Asignación de variables
nombre = "Juan"
edad = 25
es_estudiante = True

# Imprimir variables
print("Nombre:", nombre)
print("Edad:", edad)
print("¿Es estudiante?", es_estudiante)
```

---

## ➕ Operadores en Python  
Los operadores se utilizan para realizar operaciones matemáticas, de comparación y lógicas.

| Operador  | Descripción      | Ejemplo         |
|-----------|------------------|-----------------|
| `+`       | Suma             | `a + b`         |
| `-`       | Resta            | `a - b`         |
| `*`       | Multiplicación   | `a * b`         |
| `/`       | División         | `a / b`         |
| `==`      | Igualdad         | `a == b`        |
| `!=`      | Diferente        | `a != b`        |
| `and`     | Operador lógico  | `a and b`       |
| `or`      | Operador lógico  | `a or b`        |

---

## 🔄 Estructuras de Control  
Las estructuras de control permiten alterar el flujo de ejecución de un programa.

### Condicionales (`if`, `else`, `elif`):  
```python
edad = 18

if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")
```

### Bucles (`while`, `for`):  
```python
# Bucle while
contador = 0
while contador < 5:
    print("Contador:", contador)
    contador += 1

# Bucle for
for i in range(5):
    print("Número:", i)
```

---

## 📋 Listas y Diccionarios  
Las listas y los diccionarios son estructuras de datos muy útiles en Python.

### Listas:  
```python
frutas = ["manzana", "banana", "cereza"]
print(frutas[0])  # Salida: manzana

# Añadir un elemento
frutas.append("naranja")
print(frutas)
```

### Diccionarios:  
```python
persona = {
    "nombre": "Juan",
    "edad": 25,
    "ciudad": "Madrid"
}

print(persona["nombre"])  # Salida: Juan

# Añadir un nuevo par clave-valor
persona["profesión"] = "Programador"
print(persona)
```

---

## 🧩 Funciones  
Las funciones son bloques de código reutilizables que realizan una tarea específica.

### Definición de una función:  
```python
def saludar(nombre):
    print(f"Hola, {nombre}!")

saludar("Juan")  # Salida: Hola, Juan!
```

### Función con retorno de valor:  
```python
def sumar(a, b):
    return a + b

resultado = sumar(5, 3)
print("Resultado:", resultado)  # Salida: Resultado: 8
```

---

## 🚀 Próximos Pasos  
- Profundizar en Programación Orientada a Objetos (POO)  
- Manejo de errores y excepciones  
- Manipulación de archivos  
- Proyectos prácticos  

---

## ⭐ Contribuye al Repositorio  
Si encuentras útil este curso, ¡dale una estrella al repositorio! ⭐  
¿Tienes sugerencias o mejoras? ¡No dudes en abrir un issue o enviar un pull request!  
