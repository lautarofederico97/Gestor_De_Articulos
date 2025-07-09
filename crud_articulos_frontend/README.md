# 🧪 Proyecto Final - Gestor de Artículos

¡Hola! 👋 Este es mi proyecto final del curso Talento Tech. Se trata de una app web sencilla para gestionar artículos (tipo CRUD), conectada con un backend en Java + Spring Boot y una base de datos MySQL local. Ideal para practicar fullstack.

---

## 🚀 ¿Qué hace esta app?

Podés:

- Agregar artículos (nombre y precio).
- Editarlos o eliminarlos.
- Ver todo en una tabla linda con Bootstrap.
- Todo se guarda en una base de datos local (MySQL).

---

## ⚙️ Tecnologías que usé

### Frontend:
- HTML5
- CSS + Bootstrap 5
- Bootstrap Icons
- JS Vanilla

### Backend:
- Java + Spring Boot
- Spring Data JPA
- MySQL (corriendo en `localhost`)

---

## 🛠️ Cómo lo ponés a andar (backend)

1. Asegurate de tener MySQL andando.
2. Creá una base de datos llamada `articulos_db`.
3. Configurá el `application.properties` con tu user y pass:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/articulos_db
spring.datasource.username=root
spring.datasource.password=tu_clave
spring.jpa.hibernate.ddl-auto=update
```

4. Corré el proyecto desde tu IDE o con:

```bash
./mvnw spring-boot:run
```

---

## 💻 ¿Y el frontend?

Abrí el `index.html` directamente en tu navegador o servilo con Live Server si usás VSCode. La magia ocurre gracias al `app.js` que conecta con el backend.

---

## 📬 Contactame

Si querés chusmear más cosas mías o decirme qué te pareció:

- 💼 [LinkedIn](https://www.linkedin.com/in/lautaro-flores-491301119)
- 🐙 [GitHub](https://github.com/lautarofederico97)

También podés escribirme directo desde el formulario en el footer de la web 😉

---

## 🧉 Bonus

Sí, le puse un favicon, un logo de Freepik, y hasta un formulario de contacto funcional con Formspree. ¿Qué más querés? 😎

---

## 🎓 Fin

Gracias por pasar. Este fue mi proyecto final, hecho con mucho café ☕ y ganas de aprender.
