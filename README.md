<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/1046/1046857.png" />

# 🏠 Rental House Management System

### Plataforma web de gestión inmobiliaria y administración de alquileres 🚀

<p align="center">
  <b>Rental House Management System (RHMS)</b> es una plataforma desarrollada con Django para automatizar la gestión de propiedades, pagos de renta, servicios públicos y comunicación entre administradores e inquilinos.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/RentalManagement-System-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Django-WebFramework-092E20?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/Python-Backend-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Community-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Rental House Management System (RHMS)** es una aplicación web diseñada para ayudar a administradores inmobiliarios e inquilinos a gestionar propiedades, pagos de servicios y comunicación de manera eficiente y sin interrupciones.

La plataforma permite visualizar pagos anteriores, consumo de electricidad y agua, reportes de mantenimiento y notificaciones dentro de un sistema centralizado.

El sistema fue desarrollado para:

- 🏠 Gestionar propiedades
- 👥 Administrar inquilinos
- 💳 Gestionar pagos de renta
- ⚡ Monitorear consumo eléctrico
- 💧 Controlar consumo de agua
- 📅 Programar visitas
- 📩 Gestionar comunicaciones
- 📊 Visualizar reportes

---

# ✨ Características

## 🏘️ Gestión inmobiliaria

- 🏠 Registro de propiedades
- 🏢 Gestión de edificios
- 📋 Administración de unidades
- 🖼️ Gestión multimedia
- ⚙️ Control de mantenimiento

---

## 💳 Gestión de pagos y servicios

- 💰 Administración de rentas
- ⚡ Seguimiento de electricidad
- 💧 Seguimiento de agua
- 📊 Historial de pagos
- 📈 Visualización de consumos

---

## 👥 Gestión de usuarios

- 👤 Registro de inquilinos
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- 📧 Confirmación por correo
- ⚡ Administración centralizada

---

## 📩 Comunicación y reportes

- 📧 Mensajería integrada
- 📋 Gestión de quejas
- 🛠️ Reportes de mantenimiento
- 📅 Programación de visitas
- 🚪 Gestión de desalojos

---

# 👨‍💼 Módulos del sistema

## 👤 Accounts Module

Este módulo administra usuarios y autenticación.

### Funcionalidades:

- 🔐 Registro e inicio de sesión
- 👤 Gestión de perfiles
- 📧 Verificación de correo
- 🔑 Recuperación de contraseña
- ⚡ Administración de cuentas

---

## 🏠 Rental Property Module

Este módulo administra propiedades y unidades.

### Funcionalidades:

- 🏢 Gestión de edificios
- 🏠 Administración de unidades
- 📍 Gestión de ubicaciones
- 🖼️ Álbumes de propiedades
- ⚙️ Notificaciones de mantenimiento

---

## 💳 Utilities & Rent Module

Este módulo controla pagos y servicios públicos.

### Funcionalidades:

- 💰 Gestión de pagos
- ⚡ Seguimiento eléctrico
- 💧 Seguimiento de agua
- 📈 Historial de consumo
- 📋 Facturación

---

## 🛠️ Complaints & Reports Module

Este módulo gestiona reportes y soporte.

### Funcionalidades:

- 📋 Reportes de unidades
- 🚨 Gestión de quejas
- 📞 Contactos de ayuda
- 🛠️ Solicitudes de mantenimiento
- 📄 Historial de incidencias

---

## 📅 Work Order Module

Este módulo administra órdenes de trabajo y personal.

### Funcionalidades:

- 👷 Gestión de personal
- 📋 Órdenes de trabajo
- 💰 Pagos de servicios
- 📊 Seguimiento operativo
- ⚡ Administración técnica

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,bootstrap,js" />
</p>

- HTML5
- CSS3
- Bootstrap
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=python,django" />
</p>

- Python
- Django Framework
- Arquitectura MVC
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql" />
</p>

- PostgreSQL
- MySQL
- Relaciones SQL
- Persistencia de datos

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- Pip
- Virtualenv

---

# 📂 Estructura del proyecto

```bash
PlataformaGestionInmoviliariaCakePHP/
│
├── accounts/                 # Gestión de usuarios
├── complaints/               # Reportes y quejas
├── core/                     # Funciones principales
├── rental_property/          # Propiedades y unidades
├── utils/                    # Servicios y pagos
├── work_order/               # Órdenes de trabajo
├── reporting/                # Reportes administrativos
├── relationships/            # Diagramas relacionales
├── templates/                # Plantillas HTML
├── static/                   # Recursos estáticos
├── manage.py                 # Entrada principal Django
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- Python 3.9+
- Django
- PostgreSQL / MySQL
- Pip
- Virtualenv

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaGestionInmoviliariaCakePHP.git
```

---

## 2️⃣ Crear entorno virtual

```bash
python -m venv venv
```

---

## 3️⃣ Activar entorno virtual

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

## 4️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## 5️⃣ Configurar base de datos

Editar:

```bash
settings.py
```

Agregar:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'rhms',
        'USER': 'postgres',
        'PASSWORD': '',
        'HOST': 'localhost',
        'PORT': '5432',
    }
}
```

---

## 6️⃣ Ejecutar migraciones

```bash
python manage.py migrate
```

---

## 7️⃣ Ejecutar servidor

```bash
python manage.py runserver
```

---

# 📊 Funcionalidades principales

## 🏠 Gestión inmobiliaria

- Administración de propiedades
- Gestión de edificios
- Control de mantenimiento
- Programación de visitas

---

## 💳 Gestión financiera

- Seguimiento de pagos
- Historial de rentas
- Facturación de servicios
- Control de consumos

---

## 👥 Gestión de usuarios

- Registro y autenticación
- Gestión de perfiles
- Mensajería integrada
- Comunicación administrador ↔ inquilino

---



# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web con Django
- Gestión inmobiliaria
- Bases de datos relacionales
- Sistemas de autenticación
- Automatización de pagos
- Comunicación integrada
- Arquitectura MVC

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- 💳 Integración Stripe y Mpesa
- ☁️ Infraestructura cloud
- 🤖 Reportes inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones push
- 📈 Analytics avanzados

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Django Developer

Desarrolladores apasionados por plataformas inmobiliarias y automatización administrativa 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje y administración inteligente de propiedades y alquileres.

---

<div align="center">

### 🏠 Rental House Management System — administración moderna de propiedades y alquileres 🚀

</div>
