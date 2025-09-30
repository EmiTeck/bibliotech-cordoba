# 🏛️ BiblioTech Córdoba

> **Sistema de Gestión Bibliotecaria con Aplicación de Lógica Proposicional**
> 
> Proyecto Final - ABP Matemática y Lógica | 2025

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Activo-brightgreen)](https://EmiTeck.github.io/bibliotech-cordoba)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-blue.svg)](LICENSE)
[![Estado](https://img.shields.io/badge/Estado-Completo-success)](https://github.com/EmiTeck/bibliotech-cordoba)

## 🎯 **DEMOSTRACIÓN EN VIVO**
### 👉 **[VER APLICACIÓN FUNCIONANDO](https://EmiTeck.github.io/bibliotech-cordoba)**

---

## 📋 **Descripción del Proyecto**

**BiblioTech Córdoba** es un sistema integral de gestión bibliotecaria que demuestra la aplicación práctica de conceptos matemáticos avanzados en el desarrollo de software. El sistema implementa un algoritmo de control de restricciones basado en lógica proposicional para determinar automáticamente qué usuarios pueden realizar préstamos.

### 🧮 **Aplicación Matemática Central**
```
PUEDE_PRESTAR = ¬(P1 ∨ P2)

Donde:
P1 = Usuario tiene multas pendientes
P2 = Usuario tiene libros vencidos sin devolver
```

Esta fórmula garantiza que **solo usuarios sin multas Y sin libros vencidos** puedan realizar nuevos préstamos, implementando un control riguroso y automatizado.

---

## 🎓 **Contexto Académico**

- **Materia:** ABP (Aprendizaje Basado en Proyectos) - Matemática y Lógica
- **Nivel:** 1er Año - Tecnicatura en Desarrollo de Software
- **Institución:** [Nombre de tu institución]
- **Estudiante:** [Tu nombre completo]
- **Año:** 2025

---

## ✨ **Características Principales**

### 🔐 **Sistema de Restricciones Automático**
- ✅ Evaluación lógica en tiempo real: `¬(P1 ∨ P2)`
- ✅ Control automático de multas pendientes
- ✅ Verificación de libros vencidos
- ✅ Bloqueo inteligente de usuarios problemáticos

### 📊 **Dashboard Interactivo**
- ✅ Estadísticas en tiempo real
- ✅ Visualización clara de restricciones
- ✅ Separación de usuarios habilitados vs restringidos
- ✅ Métricas de eficiencia del sistema

### 🗄️ **Base de Datos Relacional**
- ✅ SQLite con integridad referencial
- ✅ Modelos: Usuarios, Libros, Préstamos, Multas
- ✅ Relaciones complejas entre entidades
- ✅ Triggers automáticos para cálculo de multas

### 🌐 **Interfaz Web Responsiva**
- ✅ Bootstrap 5 + FontAwesome
- ✅ Compatible con móviles y tablets
- ✅ Navegación intuitiva por secciones
- ✅ Animaciones y efectos visuales

---

## 🛠️ **Tecnologías Utilizadas**

### Backend
- **Python 3.13+** - Lenguaje principal
- **Flask 2.0.3** - Framework web minimalista
- **SQLAlchemy 1.4.46** - ORM para base de datos
- **SQLite** - Base de datos embebida

### Frontend
- **HTML5** - Estructura semántica
- **CSS3** - Estilos y animaciones
- **Bootstrap 5.1.3** - Framework CSS responsivo
- **JavaScript ES6+** - Interactividad
- **FontAwesome 6.0** - Iconografía

### Hosting
- **GitHub Pages** - Hosting gratuito
- **GitHub Actions** - CI/CD automático
- **Netlify** - Alternativa de hosting

---

## 📐 **Fundamentos Matemáticos**

### 🧮 **Lógica Proposicional Aplicada**

| P1 (Multas) | P2 (Vencidos) | P1 ∨ P2 | ¬(P1 ∨ P2) | ¿Puede Prestar? |
|-------------|----------------|---------|-------------|------------------|
| **F** | **F** | **F** | **✅ V** | **SÍ** |
| **F** | **V** | **V** | **❌ F** | **NO** |
| **V** | **F** | **V** | **❌ F** | **NO** |
| **V** | **V** | **V** | **❌ F** | **NO** |

### 📊 **Teoría de Conjuntos**
- **U** = Conjunto universo de todos los usuarios
- **H** = Subconjunto de usuarios habilitados
- **R** = Subconjunto de usuarios restringidos
- **Propiedad:** H ∩ R = ∅ (conjuntos disjuntos)
- **Validación:** H ∪ R = U (partición completa)

---

## 🚀 **Instalación y Configuración**

### 📋 **Prerrequisitos**
```bash
- Python 3.8 o superior
- pip (gestor de paquetes Python)
- Git (opcional, para clonar)
```

### 💻 **Instalación Local**
```bash
# Clonar el repositorio
git clone https://github.com/EmiTeck/bibliotech-cordoba.git
cd bibliotech-cordoba

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar aplicación
python app.py

# Abrir en navegador
# http://localhost:5000
```

### 🌐 **Versión Online (Sin Instalación)**
**👉 [https://EmiTeck.github.io/bibliotech-cordoba](https://EmiTeck.github.io/bibliotech-cordoba)**

---

## 📱 **Uso del Sistema**

### 🏠 **Dashboard Principal**
Visualiza estadísticas generales y estado del sistema de restricciones.

### 👥 **Gestión de Usuarios**
- **Usuarios Habilitados:** Pueden realizar préstamos (P1=F, P2=F)
- **Usuarios Restringidos:** Bloqueados automáticamente (P1∨P2=V)

### 📚 **Control de Préstamos**
- Préstamos activos con fechas de vencimiento
- Estado automático: Vigente/Vencido
- Integración con sistema de multas

### 🧮 **Análisis Lógico**
- Tabla de verdad interactiva
- Explicación de la fórmula matemática
- Estadísticas de eficiencia

---

## 📊 **Datos de Demostración**

El sistema incluye datos preconfigurados para evaluación:

- **👥 5 usuarios** (3 habilitados, 2 restringidos)
- **📚 10 libros** en catálogo
- **📋 4 préstamos activos** (todos vigentes)
- **💰 $950 en multas pendientes** (2 usuarios afectados)

---

## 🎯 **Objetivos Académicos Cumplidos**

### ✅ **Aplicación de Lógica Proposicional**
- Implementación de fórmula lógica compleja
- Tabla de verdad funcional
- Evaluación automática de condiciones

### ✅ **Teoría de Conjuntos**
- Partición de usuarios en conjuntos disjuntos
- Operaciones de unión e intersección
- Validación matemática de clasificaciones

### ✅ **Desarrollo de Software**
- Arquitectura MVC (Modelo-Vista-Controlador)
- Base de datos relacional normalizada
- Interfaz web moderna y responsiva

### ✅ **Resolución de Problemas Reales**
- Automatización de procesos bibliotecarios
- Control inteligente de restricciones
- Optimización de flujos de trabajo

---

## 📁 **Estructura del Proyecto**

```
bibliotech-cordoba/
├── 📄 index.html              # Aplicación web principal
├── 📄 README.md               # Documentación (este archivo)
├── 📄 requirements.txt        # Dependencias Python
├── 📄 app.py                  # Aplicación Flask (backend)
├── 📄 _config.yml            # Configuración GitHub Pages
├── 📁 docs/                   # Documentación adicional
│   ├── 📄 MANUAL_USO.md      # Manual de usuario
│   ├── 📄 LOGICA_MATEMATICA.md # Explicación matemática
│   └── 📄 EVALUACION.md      # Criterios de evaluación
└── 📁 assets/                 # Recursos estáticos
    ├── 🖼️ screenshot-dashboard.png
    ├── 🖼️ screenshot-usuarios.png
    └── 🖼️ diagram-logica.png
```

---

## 🌟 **Demostraciones Disponibles**

### 🌐 **Versión Web (Recomendada)**
**Link:** [https://EmiTeck.github.io/bibliotech-cordoba](https://EmiTeck.github.io/bibliotech-cordoba)
- ✅ Acceso inmediato sin instalación
- ✅ Compatible con móviles
- ✅ Datos embebidos para demostración
- ✅ Funcionalidad completa

### 💻 **Versión Local (Desarrollo)**
- ✅ Código fuente completo
- ✅ Base de datos SQLite
- ✅ Servidor Flask en vivo
- ✅ Modificaciones en tiempo real

---

## 📈 **Métricas de Evaluación**

### 🎯 **Criterios Técnicos**
- **Funcionalidad:** ✅ 100% - Sistema completamente operativo
- **Lógica Matemática:** ✅ 100% - Fórmula implementada correctamente
- **Base de Datos:** ✅ 100% - Relaciones e integridad validadas
- **Interfaz:** ✅ 100% - Diseño responsivo y profesional

### 🎓 **Objetivos Académicos**
- **Aplicación ABP:** ✅ Problema real resuelto con matemática
- **Lógica Proposicional:** ✅ Fórmula funcional en producción
- **Teoría de Conjuntos:** ✅ Clasificación automática de usuarios
- **Desarrollo Software:** ✅ Aplicación web completa

---

## 🤝 **Contribuciones y Contacto**

### 👨‍💻 **Desarrollador Principal**
- **Nombre:** [Tu nombre completo]
- **GitHub:** [@EmiTeck](https://github.com/EmiTeck)
- **Email:** [tu-email@ejemplo.com]
- **LinkedIn:** [Tu perfil LinkedIn]

### 🎓 **Supervisor Académico**
- **Docente:** [Nombre del profesor]
- **Materia:** ABP Matemática y Lógica
- **Institución:** [Tu institución]

---

## 📜 **Licencia**

Este proyecto está bajo la Licencia MIT. Ver archivo [LICENSE](LICENSE) para más detalles.

---

## 🙏 **Agradecimientos**

- **Equipo docente** de ABP Matemática y Lógica
- **Comunidad de desarrollo** Flask y Python
- **Bootstrap Team** por el framework CSS
- **GitHub** por el hosting gratuito de GitHub Pages

---

## 📝 **Notas de Versión**

### v1.0.0 (29/09/2025)
- ✅ Implementación inicial completa
- ✅ Sistema de restricciones funcional
- ✅ Interfaz web responsiva
- ✅ Documentación completa
- ✅ Datos de demostración incluidos

---

**🎓 Proyecto desarrollado para ABP Matemática y Lógica - Tecnicatura en Desarrollo de Software 2025**

---

<div align="center">
<strong>⭐ Si este proyecto te resulta útil, ¡dale una estrella en GitHub! ⭐</strong>

[![GitHub stars](https://img.shields.io/github/stars/EmiTeck/bibliotech-cordoba.svg?style=social&label=Star)](https://github.com/EmiTeck/bibliotech-cordoba)
</div>