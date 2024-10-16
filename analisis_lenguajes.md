# Análisis de Lenguajes de Programación

## 1. JavaScript (NodeJS)
- **Modelo de ejecución**: Interpretado.
- **Bytecode**: No utiliza bytecode, es ejecutado directamente por el motor V8 (en el caso de NodeJS).
- **Programas**: Motor V8 ejecuta el código de JavaScript.
- **Virtualización**: No utiliza un sistema de virtualización de aplicación específico, pero se ejecuta en una máquina virtual (el motor V8).

## 2. Java
- **Modelo de ejecución**: Compilado a bytecode y ejecutado mediante compilación JIT.
- **Bytecode**: Sí, utiliza bytecode generado por el compilador `javac`.
- **Programas**: `javac` (compilador), JVM (máquina virtual para ejecutar el bytecode), `java` (ejecutor).
- **Virtualización**: Se ejecuta en la Java Virtual Machine (JVM).

## 3. Python
- **Modelo de ejecución**: Interpretado.
- **Bytecode**: Sí, genera bytecode (.pyc) antes de la ejecución.
- **Programas**: `python` (intérprete).
- **Virtualización**: No utiliza un sistema de virtualización específico, aunque puede ejecutarse en entornos virtuales como `virtualenv`.

## 4. C
- **Modelo de ejecución**: Compilado.
- **Bytecode**: No utiliza bytecode, el código es compilado directamente a lenguaje máquina.
- **Programas**: `gcc` (compilador), `ld` (enlazador).
- **Virtualización**: No utiliza virtualización de aplicación.

## 5. C++
- **Modelo de ejecución**: Compilado.
- **Bytecode**: No utiliza bytecode, el código se compila directamente a código máquina.
- **Programas**: `g++` (compilador), `ld` (enlazador).
- **Virtualización**: No utiliza virtualización de aplicación.

## 6. C#/.NET
- **Modelo de ejecución**: Compilado a bytecode (CIL - Common Intermediate Language) y ejecutado con compilación JIT.
- **Bytecode**: Sí, utiliza bytecode.
- **Programas**: `csc` (compilador), CLR (Common Language Runtime).
- **Virtualización**: Utiliza la CLR como máquina virtual.

## 7. Ruby
- **Modelo de ejecución**: Interpretado.
- **Bytecode**: Algunos intérpretes (como YARV) utilizan bytecode.
- **Programas**: `ruby` (intérprete).
- **Virtualización**: No utiliza un sistema de virtualización específico.

## 8. PHP
- **Modelo de ejecución**: Interpretado.
- **Bytecode**: Algunos motores como Zend generan bytecode.
- **Programas**: `php` (intérprete).
- **Virtualización**: No utiliza un sistema de virtualización específico.

## 9. Go
- **Modelo de ejecución**: Compilado.
- **Bytecode**: No utiliza bytecode, el código se compila directamente a binarios.
- **Programas**: `go` (compilador).
- **Virtualización**: No utiliza virtualización de aplicación.

## 10. Rust
- **Modelo de ejecución**: Compilado.
- **Bytecode**: No utiliza bytecode, el código se compila a binarios nativos.
- **Programas**: `rustc` (compilador).
- **Virtualización**: No utiliza virtualización de aplicación.

## 11. Dart
- **Modelo de ejecución**: Compilado a bytecode o compilado JIT dependiendo del entorno.
- **Bytecode**: Sí, utiliza bytecode cuando se ejecuta en la máquina virtual Dart VM.
- **Programas**: `dart` (compilador y ejecutor), Dart VM.
- **Virtualización**: Utiliza Dart VM como sistema de virtualización.

