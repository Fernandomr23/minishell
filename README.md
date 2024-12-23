# Minishell

![Minishell](https://img.shields.io/badge/42_Madrid-Minishell-blue)

Minishell es un proyecto desarrollado en 42 Madrid como parte del plan de estudios de la escuela. El objetivo es crear un shell minimalista que replique el comportamiento de bash y otras shells, implementando funcionalidades clave para la ejecución de comandos y gestión del entorno.

---

## Características

- Soporte para comandos ejecutables.
- Gestión de redirecciones (`>`, `>>`, `<`, heredoc).
- Pipes (`|`) para encadenar comandos.
- Variables de entorno y su manejo (`export`, `$VAR`).
- Implementación de señales (Ctrl-C, Ctrl-D, Ctrl-\).
- Manejo de errores y códigos de salida específicos.

---

## Instalación

1. Clona este repositorio:

   ```bash
   git clone https://github.com/Fernandomr23/minishell.git
   ```
2. Accede al directorio del proyecto:

   ```bash
   cd minishell
   ```
3. Compila el proyecto:

   ```bash
   make
   ```
4. Ejecuta el shell:

   ```bash
   ./minishell
   ```

---

### Ejemplo

```bash
minishell$ echo "Hola Mundo" > salida.txt
minishell$ cat salida.txt
Hola Mundo
```

---

## Arquitectura

El proyecto está organizado en los siguientes módulos:

- **Parsing**: Maneja la interpretación y validación de comandos.
- **Execution**: Coordina la ejecución de comandos internos y externos.
- **Environment**: Controla las variables de entorno.
- **Redirection**: Gestiona los operadores de redirección.
- **Signals**: Implementa la gestión de señales.

## Equipo

- [Fernando Morenilla](https://github.com/Fernandomr23)
- [Francisco Vizcaya](https://github.com/tinilla133)

