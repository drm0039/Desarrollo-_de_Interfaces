# Ejercicio de Interfaces en Java

Aplicación de escritorio en **Java Swing** con ventanas de **inicio de sesión** y **registro de usuarios**.

---

## 📂 Estructura
```
src/main/java
 ├── AccesoUnificado.java   # Ventana principal
 ├── Inicio_de_sesión.java  # Login
 ├── Registrarse.java       # Registro
 └── org/example/App.java   # Clase main
```

---

## 🏗️ Clases
- **App.java** → inicia la aplicación.
- **AccesoUnificado.java** → menú principal.
- **Inicio_de_sesión.java** → formulario de login.
- **Registrarse.java** → formulario de registro.

---

## 🔑 Conceptos
- **Swing**: biblioteca gráfica de Java.
- **.form**: diseño visual generado en IntelliJ.
- **Eventos**: manejados con `ActionListener`.
- **Maven**: gestión del proyecto.

---

## ▶️ Ejecución
```bash
mvn clean install
mvn exec:java -Dexec.mainClass="org.example.App"
```

---

## 🚀 Mejoras futuras
- Almacenar usuarios en BD o ficheros.
- Validaciones más sólidas.
- Aplicar patrón **MVC**.

