# Sistema de Gestión de Usuarios

## Descripción

Proyecto desarrollado en Java como trabajo final del curso de Programación Orientada a Objetos.

El sistema permite administrar usuarios mediante consola utilizando Programación Orientada a Objetos, manejo de excepciones, validaciones y buenas prácticas de desarrollo.

## Funcionalidades

- Inicio de sesión de administradores.
- Registro de administradores.
- Alta de usuarios Tester.
- Listado de usuarios.
- Búsqueda de usuarios por email.
- Edición del perfil del administrador.
- Cambio de contraseña.
- Eliminación de usuarios Tester.
- Cierre de sesión.
- Salida del sistema.

## Validaciones implementadas

- Campos obligatorios.
- Validación de formato de email.
- Control de emails duplicados.
- Contraseña mínima de 8 caracteres.
- Confirmación de contraseña.
- Validación de opciones del menú.
- Manejo de datos inválidos.

## Excepciones utilizadas

### Estándar de Java

- InputMismatchException

### Personalizadas

- DatosInvalidosException
- EmailDuplicadoException
- UsuarioNoEncontradoException

## Conceptos aplicados

- Programación Orientada a Objetos.
- Encapsulamiento.
- Herencia.
- Polimorfismo.
- Colecciones (ArrayList).
- Patrón Singleton.
- Manejo de excepciones.

## Estructura del proyecto

```
src
├── Admin.java
├── Main.java
├── SistemaUsuarios.java
├── Tester.java
├── TipoTester.java
├── Usuario.java
├── DatosInvalidosException.java
├── EmailDuplicadoException.java
└── UsuarioNoEncontradoException.java
```

## UML

El diagrama UML forma parte de la entrega y representa la estructura de clases del sistema.

## Autor

Alexis Gutiérrez
