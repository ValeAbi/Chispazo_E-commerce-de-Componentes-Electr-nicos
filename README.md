# Chispazo
#Valeria Abigail González Sada ⭐ Product Owner (líder)
#Aldo Briones Martinez
#Alfonso Plaza Esquivel
#Ailton Omar Garrido Garcia
#Ana Valeria Reyna Peña
#Daniela Avigail Varela Alvarado
#Enrique Calderón Santana
#Jessica Angeles Resendiz Arroyo
#Miguel Angel Sanchez Cruz
#Uriel Franco Jaramillo


# ⚡ Chispazo – E-commerce de Componentes Electrónicos

Chispazo es una tienda en línea de componentes electrónicos desarrollada en equipo como **proyecto final del bootcamp de Java Full Stack de Generation**. Nació para que comprar componentes sea más fácil y para que quien está empezando no se pierda en el intento.

> 🌐 **Demo:** [enlace a la demo]

---

## 📋 Tabla de contenido

- [Funcionalidades](#-funcionalidades)
- [Tecnologías](#-tecnologías)
- [Estructura del proyecto](#-estructura-del-proyecto)
- [Base de datos](#-base-de-datos)
- [Instalación y ejecución](#-instalación-y-ejecución)
- [Metodología de trabajo](#-metodología-de-trabajo)

---

## 🛍️ Funcionalidades

**Para el cliente**
- 🔌 Catálogo de componentes: microcontroladores, sensores, resistencias, LEDs, cables y más
- 🔍 Búsqueda y filtrado por categoría
- 📄 **Datasheet** disponible en cada producto
- 🛒 Carrito de compras y flujo de compra completo
- 👤 Registro e inicio de sesión
- 📦 Consulta del detalle de pedidos

**Para el administrador**
- Gestión de productos, inventario y pedidos

**Funcionalidades extra**
- 🧮 **Calculadora de resistencias** con función de cálculo de potencia
- 🤖 **Asistente virtual (chatbot)** que orienta al usuario en la elección de componentes y en su compra

---

## 🛠️ Tecnologías

| Área | Tecnologías |
|------|-------------|
| Backend | Java, Spring Boot, API REST, Spring Security |
| Base de datos | MySQL |
| Frontend | HTML, CSS, JavaScript |
| Herramientas | Git, GitHub, Gradle |
| Metodología | Scrum |

---

## 📁 Estructura del proyecto

```
Chispazo/
├── backend/                       # Lógica del backend
├── chispita-backend/              # Servicio del asistente virtual / backend
├── Html/                          # Páginas HTML
├── css/                           # Estilos
├── js/                            # Scripts del frontend
├── img/                           # Imágenes
├── index.html                     # Página principal
├── e_commers_chispazo.sql         # Script de la base de datos
├── Diagrama EER_base de datos_Chispazo.png
└── README.md
```

---

## 🗄️ Base de datos

El script `e_commers_chispazo.sql` contiene la estructura de la base de datos. El modelo entidad-relación se encuentra en:

![Diagrama EER](<Diagrama EER_base de datos_Chispazo.png>)

---

## 🚀 Instalación y ejecución

### Requisitos previos

- [Git](https://git-scm.com/)
- [JDK 17](https://adoptium.net/) o superior
- [MySQL](https://dev.mysql.com/downloads/) 8 o superior
- Un IDE como IntelliJ IDEA o VS Code (opcional)

### Pasos

**1. Clonar el repositorio**

```bash
git clone https://github.com/ValeAbi/Chispazo_E-commerce-de-Componentes-Electr-nicos.git
cd Chispazo_E-commerce-de-Componentes-Electr-nicos
```

**2. Crear la base de datos**

Abre MySQL e importa el script:

```bash
mysql -u TU_USUARIO -p < e_commers_chispazo.sql
```

**3. Configurar la conexión**

En el archivo `application.properties` del backend, ajusta tus credenciales:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/NOMBRE_DE_LA_BD
spring.datasource.username=TU_USUARIO
spring.datasource.password=TU_CONTRASEÑA
```

**4. Ejecutar el backend**

```bash
cd backend
./gradlew bootRun
```

(En Windows PowerShell: `gradlew.bat bootRun`)

**5. Abrir el frontend**

Abre `index.html` en tu navegador, o sírvelo con una extensión como Live Server en VS Code.

---

## 👥 Metodología de trabajo

Trabajamos con **Scrum**: organizamos el proyecto en sprints, con reuniones diarias (dailies), planificación y retrospectivas. Usamos Git y GitHub para colaborar mediante ramas, sin pisarnos el código.



- 
