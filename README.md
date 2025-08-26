# ANEXO 11 - Formulario Web

Este proyecto contiene un formulario web moderno y responsivo para ANEXO 11, diseñado para ser desplegado en GitHub Pages.

## Características

- ✨ Diseño moderno y responsivo
- 📱 Compatible con dispositivos móviles
- 🎨 Interfaz de usuario atractiva
- ✅ Validación de formularios en tiempo real
- 🌐 Listo para GitHub Pages

## Campos del Formulario

- **Nombre Completo** (requerido)
- **Número de Identificación** (requerido)
- **Fecha de Nacimiento** (requerido)
- **Género**
- **Teléfono** (requerido)
- **Correo Electrónico** (requerido)
- **Dirección Completa** (requerido)
- **Ciudad** (requerido)
- **Departamento/Estado**
- **Código Postal**
- **País** (requerido, predeterminado: Colombia)
- **Observaciones Adicionales**

## Despliegue en GitHub Pages

### Opción 1: Despliegue Automático

1. Haz un fork de este repositorio o clónalo en tu cuenta de GitHub
2. Ve a **Settings** > **Pages**
3. En **Source**, selecciona **Deploy from a branch**
4. Selecciona la rama **main** y la carpeta **/** (root)
5. Haz clic en **Save**
6. Tu formulario estará disponible en: `https://tu-usuario.github.io/nombre-del-repo`

### Opción 2: Despliegue Manual

1. Sube todos los archivos a tu repositorio de GitHub
2. Sigue los pasos 2-6 de la Opción 1

## Personalización

### Cambiar Colores
Modifica las variables CSS en el archivo `index.html`:

```css
/* Colores principales */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
```

### Agregar Nuevos Campos
Para agregar nuevos campos, sigue este patrón:

```html
<div class="form-group">
    <label for="nuevoCampo">Nuevo Campo</label>
    <input type="text" id="nuevoCampo" name="nuevoCampo">
</div>
```

### Modificar Validación
Edita la función JavaScript al final del archivo para personalizar la validación.

## Tecnologías Utilizadas

- HTML5
- CSS3 (con Grid y Flexbox)
- JavaScript ES6+
- Diseño responsivo con media queries

## Estructura del Proyecto

```
├── index.html          # Formulario principal
├── README.md           # Este archivo
└── ANEXO 11.docx      # Documento original de referencia
```

## Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## Soporte

Si tienes alguna pregunta o problema, por favor abre un issue en este repositorio.

---

**Nota**: Este formulario está diseñado para ser un ejemplo y puede requerir modificaciones según tus necesidades específicas de ANEXO 11.