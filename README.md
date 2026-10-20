<h1 align="center">Fernando Esquivia</h1>

<p align="center">
  <strong>Desarrollador Backend · Estudiante de Ingeniería de Software</strong><br>
  Python · FastAPI · PostgreSQL · SQLAlchemy · Pydantic
</p>

<p align="center">
  <sub><em>Backend developer building production-grade REST APIs with Python and FastAPI.<br>
  Currently going deeper into AI agents — tool use, cost control and security.<br>
  Based in Medellín, Colombia · Open to junior and internship roles.</em></sub>
</p>

---

## Sobre mí

Construyo APIs REST pensadas para aguantar producción: arquitectura en capas,
autenticación y autorización bien resueltas, y migraciones que no rompen lo que
ya está funcionando.

Lo que más me interesa no es que el código funcione, sino poder explicar **por qué
está así**: por qué una validación vive en el endpoint y otra en el servicio, por
qué un endpoint por acción en vez de uno que recibe todo.

Ahora estoy profundizando en **agentes de IA** sobre esas mismas bases de backend.

---

## Stack

**Backend**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-109989?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=for-the-badge&logo=alembic&logoColor=white)

**Herramientas**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

**Aprendiendo ahora**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

---

## Proyectos

### [TaskFlow API](https://github.com/Fernando-03-Git/taskflow-api)

> `FastAPI` · `PostgreSQL` · `SQLAlchemy 2.0` · `Alembic` · `JWT` · `Pytest`

API REST para gestión de proyectos y tareas en equipo. **20 endpoints** en cinco
módulos, con migraciones, pruebas y manejo uniforme de errores.

Lo interesante no son los endpoints, son **las tres capas de control de acceso**:

| Capa | Qué decide | Dónde vive |
|---|---|---|
| Autenticación | ¿Quién eres? | Dependencia de FastAPI |
| Rol | ¿Qué clase de cosas puedes hacer? | En el endpoint — no necesita la base de datos |
| Propiedad | ¿Puedes tocar **este** dato? | En el servicio — hay que cargar la fila para saberlo |

El criterio es ese: si se puede decidir sin consultar la base de datos, va en el
endpoint; si hay que saber de quién es el dato, va en el servicio.

---

### [NovaBank](https://github.com/Fernando-03-Git/NovaBank)

> `Python` · `Flet` · `SQLite`

Aplicación bancaria que corre en Android, iOS, web y escritorio **desde una sola
base de código**. Cuentas, depósitos, retiros, transferencias entre usuarios e
historial de transacciones.

Arquitectura separada en capas —`models`, `logic`, `views`, `database`— para que la
lógica de negocio no dependa de la interfaz.

---

### [Agent_IA](https://github.com/Fernando-03-Git/Agent_IA)

> `Python` · `Ollama` · `LangChain` · `Streamlit`

Laboratorio de experimentos con modelos de lenguaje corriendo **en local** con
Ollama. Chat con memoria de conversación, en consola y con interfaz web.

Es el punto de partida de lo que estoy construyendo ahora: entender el ciclo de un
agente escribiéndolo desde cero, sin frameworks.

---

## En qué estoy trabajando

- **Máquina de estados** para las tareas de TaskFlow: qué transiciones son válidas
  y quién puede hacer cada una
- **Dockerizar y desplegar** TaskFlow
- **Agentes de IA sin frameworks**, para entender el ciclo antes de usar una librería
- **Async en Python**: el event loop, concurrencia, y por qué importa cuando cada
  llamada tarda segundos

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Fernando-03-Git&layout=compact&theme=default&hide_border=true" height="140"/>
</p>

---

## Contacto

<p align="center">
  <a href="mailto:esquiviafernando33@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/fernando-esquivia-ortega-09a126266">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
</p>

<p align="center"><sub>📍 Medellín, Colombia</sub></p>
