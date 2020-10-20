# Arquetipos
#### Arquetipos personalizados y como una breve introduccion a la creación de `arquetipos` propios, para profundizar en el tema, los invito a consultar la documentación de `maven`.

***

### Requerimientos
> Java 1.8 

> maven-3.6.3 
### Clonar repositorio
#### `git clone https://github.com/wilberArgueta/Archetypes.git`

---

### quickstart-se
#### Arquetipo para generar un proyecto para aplicativos con `java se`.

---

### Seleccionar arquetipo
#### `cd quickstart-se`

### Instalar localmente el arquetipo
#### `mvn install`

### Comando para crear un proyecto con `maven` apartir del arquetipo
#### `mvn archetype:generate -DarchetypeGroupId=com.github.wilberargueta -DarchetypeArtifactId=quickstart-se -DarchetypeVersion=0.0.1 -DgroupId=<mygroupid> -DartifactId=<my-artifactId>` -Dversion=<version> -DinteractiveMode=false

---

# Conclusion
#### Espero les sirva como ejemplo para poder crear su propios arquetipos, para generar proyectos personalizados.
### Sientanse libres de modificar o agregar arquetipos, saludos!.