# S105-Ex1-Java-Utils-Nivel-1
# Replicador de Directorios

📄 **Descripción - Ejercicio**

Este proyecto es un ejercicio para crear una aplicación en Java que replique el contenido de un directorio en un nuevo directorio, ordenando los archivos y directorios alfabéticamente. La aplicación está diseñada para manejar varias operaciones de archivos y proporcionar retroalimentación al usuario sobre el proceso de replicación.

💻 **Tecnologías Utilizadas**

- Java SE 8 o superior
- Java NIO (New I/O) para operaciones de archivos
- API de Logging de Java para registros

📋 **REQUISITOS**

- Java Development Kit (JDK) 8 o superior
- Apache Maven (opcional, si se utiliza Maven para la gestión de dependencias)
- Un terminal o símbolo del sistema para ejecutar la aplicación

🛠️ **Instalación**

1. **Clonar el Repositorio**: 
   ```bash
   git clone https://github.com/MaraMarchello/S105-Ex1-Java-Utils-Nivel-1.git
   cd replicador-de-directorios
   ```

2. **Compilar el Proyecto**:
   - Si usas Maven:
     ```bash
     mvn clean install
     ```
   - Si usas javac:
     ```bash
     javac -d bin src/tascaS105Ex1/DirectoryReplicator.java
     ```

▶️ **Implementación**

1. **Ejecutar la Aplicación**:
   - Usando Maven:
     ```bash
     mvn exec:java -Dexec.mainClass="tascaS105Ex1.DirectoryReplicator" -Dexec.args="<ruta_directorio_origen>"
     ```
   - Usando Java:
     ```bash
     java -cp bin tascaS105Ex1.DirectoryReplicator <ruta_directorio_origen>
     ```

🌐 **DESPLIEGUE**

- Para desplegar la aplicación en un servidor, asegúrate de que el servidor tenga instalado el JDK requerido.
- Empaqueta la aplicación en un archivo JAR usando Maven u otra herramienta de construcción.
- Transfiere el archivo JAR al servidor y ejecútalo usando el comando Java:
  ```bash
  java -jar replicador-de-directorios.jar <ruta_directorio_origen>
  ```

🤝 **Contribución**

¡Las contribuciones son bienvenidas! Por favor, sigue estas pautas:

1. Haz un fork del repositorio.
2. Crea una nueva rama para tu característica o corrección de errores.
3. Realiza tus cambios con mensajes claros.
4. Sube tu rama a tu repositorio bifurcado.
5. Abre un pull request con una descripción detallada de tus cambios.

Para cambios importantes, por favor abre primero un issue para discutir lo que te gustaría cambiar.
