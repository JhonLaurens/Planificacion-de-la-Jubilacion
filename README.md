# 📊 Planificación de la Jubilación

**Guía Interactiva sobre la Reforma Pensional Colombiana - Ley 2381 de 2024**

![Reforma Pensional](https://img.shields.io/badge/Ley-2381%20de%202024-blue)
![Estado](https://img.shields.io/badge/Estado-Vigente%20desde%20julio%202025-green)
![Educación Financiera](https://img.shields.io/badge/Educación-Financiera-yellow)

## 🎯 Descripción del Proyecto

Este proyecto presenta una **guía interactiva completa** sobre la nueva reforma pensional colombiana establecida por la Ley 2381 de 2024. Está diseñada para ayudar a los trabajadores colombianos a entender los cambios en el sistema pensional y planificar su futuro financiero de manera informada.

### ✨ Características Principales

- 🧮 **Calculadora Interactiva**: Simula la división de cotizaciones entre Colpensiones y AFP
- 📚 **Contenido Educativo**: Explicaciones claras sobre el nuevo sistema pensional
- 💰 **Planificación Financiera**: Herramientas para calcular cesantías y ahorro voluntario
- 📱 **Diseño Responsivo**: Optimizado para dispositivos móviles y escritorio
- ♿ **Accesible**: Cumple con estándares de accesibilidad web

## 🔧 Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con Tailwind CSS
- **JavaScript ES6+**: Interactividad y cálculos dinámicos
- **Responsive Design**: Compatible con todos los dispositivos

## 📋 Contenido de la Guía

### 1. Sistema Pensional Actual vs. Nuevo Modelo
- Explicación del pilar contributivo
- Comparación con el sistema anterior
- Línea de tiempo de implementación

### 2. Calculadora del Pilar Contributivo
- **Umbral de 2.3 SMLMV**: División automática de cotizaciones
- Visualización interactiva de aportes
- Cálculos en tiempo real

### 3. Gestión de Cesantías
- Cálculo de cesantías acumuladas
- Fechas importantes de pago
- Opciones de inversión (multiportafolios)

### 4. Planificación y Ahorro
- Simulador de ahorro para la jubilación
- Estrategias de ahorro voluntario
- Asesoría personalizada

## 🚀 Cómo Usar la Aplicación

### Instalación Local

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/planificacion-jubilacion.git
   cd planificacion-jubilacion
   ```

2. **Abre el archivo principal**:
   ```bash
   # Abre index_backup.html en tu navegador preferido
   start index_backup.html  # Windows
   open index_backup.html   # macOS
   xdg-open index_backup.html # Linux
   ```

3. **¡Listo!** No se requieren dependencias adicionales.

### Uso Online

Visita la aplicación en: [GitHub Pages](https://tu-usuario.github.io/planificacion-jubilacion/)

## 📊 Funcionalidades Clave

### Calculadora de Cotizaciones

```javascript
// Ejemplo de cálculo automático
const salario = 3000000; // COP
const umbral = 2.3 * SMLMV_2025; // 3,289,000 COP

if (salario > umbral) {
    baseColpensiones = umbral;
    baseAFP = salario - umbral;
} else {
    baseColpensiones = salario;
    baseAFP = 0;
}
```

### Información Legal Actualizada

- **Ley 2381 de 2024**: Promulgada el 16 de julio de 2024
- **Vigencia**: A partir del 1 de julio de 2025
- **Contribuciones al Fondo de Solidaridad Pensional**:
  - 4 a 6.9 SMMLV: 1.5% adicional
  - 7 a 10.9 SMMLV: 1.8% adicional
  - 11 a 18.9 SMMLV: 2.5% adicional
  - 19 a 19.9 SMMLV: 2.8% adicional
  - 20 SMMLV o más: 3.0% adicional

## 🎨 Diseño y UX

### Principios de Diseño
- **Claridad**: Información compleja presentada de forma simple
- **Interactividad**: Elementos que responden al usuario
- **Accesibilidad**: Compatible con lectores de pantalla
- **Responsividad**: Funciona en todos los dispositivos

### Paleta de Colores
- **Azul Institucional**: `#00305B` (Confianza y profesionalismo)
- **Amarillo Destacado**: `#FFDD00` (Atención y claridad)
- **Grises Neutros**: Para texto y fondos

## 📈 Métricas y Datos

### Estadísticas Incluidas
- 📊 **85%** de trabajadores tienen derecho a cesantías
- 💰 **12%** de interés anual sobre cesantías
- 🏠 **67%** usa cesantías para vivienda
- 💳 **15.2%** de la población ahorra regularmente

## 🔄 Actualizaciones y Mantenimiento

### Historial de Versiones

#### v2.0.0 (Junio 2025)
- ✅ Información actualizada según análisis detallado de la ley
- ✅ Corrección de tasas del Fondo de Solidaridad Pensional
- ✅ Actualización de fechas de cesantías (31 de enero para intereses)
- ✅ Mejora en la sección de asesoría con productos Coltefinanciera

#### v1.0.0 (Inicial)
- 🎉 Lanzamiento de la guía interactiva
- 🧮 Calculadora básica del pilar contributivo
- 📚 Contenido educativo sobre la reforma

## 👥 Contribuciones

### Cómo Contribuir

1. **Fork** el repositorio
2. **Crea** una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. **Commit** tus cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. **Push** a la rama (`git push origin feature/nueva-funcionalidad`)
5. **Abre** un Pull Request

### Áreas de Mejora
- 🔧 Nuevas calculadoras (proyección de pensión)
- 🌐 Soporte multiidioma
- 📊 Más visualizaciones de datos
- 🎯 Personalización por perfil de usuario

## ⚖️ Aspectos Legales

### Disclaimer
Este material es únicamente para **fines educativos**. Para decisiones específicas sobre tu pensión, consulta siempre con:
- Asesores financieros certificados
- Entidades oficiales (Colpensiones, AFP)
- Abogados especializados en seguridad social

### Derechos de Autor
© 2025 Coltefinanciera. Todos los derechos reservados.
Material de educación financiera.

## 📞 Contacto y Soporte

### Coltefinanciera
- 🌐 **Web**: [www.coltefinanciera.com.co](https://www.coltefinanciera.com.co/)
- 💬 **WhatsApp**: [Chat directo](https://api.whatsapp.com/message/FHJFAPESCA2NG1?autoload=1&app_absent=0)
- 🤖 **ColteBot**: Chatbot especializado en productos de ahorro

### Desarrollador
- 📧 **Email**: contacto@proyecto.com
- 🐛 **Issues**: [GitHub Issues](https://github.com/tu-usuario/planificacion-jubilacion/issues)

## 📚 Recursos Adicionales

### Documentación Oficial
- [Ley 2381 de 2024](https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=220479)
- [Ministerio del Trabajo](https://www.mintrabajo.gov.co/)
- [Superintendencia Financiera](https://www.superfinanciera.gov.co/)

### Material Educativo
- 📄 Documento de análisis detallado incluido
- 📊 Planillas de Excel para cálculos
- 🎥 Videos explicativos (próximamente)

---

**⭐ Si este proyecto te resulta útil, no olvides darle una estrella en GitHub!**

**🚀 Juntos construimos una mejor educación financiera para Colombia**
