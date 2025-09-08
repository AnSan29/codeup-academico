# Sistema Académico CodeUp

### Requisitos
- Java 17
- Maven
- Git

### Instalación y ejecución
```bash
git clone https://github.com/AnSan29/codeup-academico.git
cd codeup-academico
mvn compile
mvn exec:java -Dexec.mainClass="com.codeup.academico.App"
```

# Estructura inicial

```bash
.
├── pom.xml
├── src
│ ├── main
│ │ └── java
│ │ └── com
│ │ └── codeup
│ │ └── academico
│ │ ├── Academico.java
│ │ ├── App.java
│ │ └── domain
│ │ └── Estudiante.java
│ └── test
│ └── java
└── target
├── academico-1.0-SNAPSHOT.jar
├── classes
│ └── com
│ └── codeup
│ └── academico
│ ├── Academico.class
│ ├── App.class
│ └── domain
│ └── Estudiante.class
├── generated-sources
│ └── annotations
├── generated-test-sources
│ └── test-annotations
├── maven-archiver
│ └── pom.properties
├── maven-status
│ └── maven-compiler-plugin
│ ├── compile
│ │ └── default-compile
│ │ ├── createdFiles.lst
│ │ └── inputFiles.lst
│ └── testCompile
│ └── default-testCompile
│ ├── createdFiles.lst
│ └── inputFiles.lst
└── test-classes

```



---

## ✅ Ejercicio práctico del día
1. Crear un **estudiante** y un **curso** en código.  
2. Imprimirlos en consola con `System.out.println()`.  
3. Hacer commit en la rama `feature/setup`.  
4. Crear un Pull Request a la rama `develop` en GitHub.  

---

📌 **Resultado esperado hoy**  
- Entorno Java + Maven + IDE configurado en Linux.  
- Proyecto Java funcionando.  
- Repositorio GitHub conectado con ramas (`develop` y `feature/setup`).  
- Primer commit con `App.java` y `Estudiante.java`.  
- README inicial creado.  
