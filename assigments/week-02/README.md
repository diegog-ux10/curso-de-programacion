# 📊 Evaluación de la Semana

### Proyecto: Curriculum Personal en HTML

Para aprobar esta semana, deberás crear un proyecto que cumpla con los siguientes requisitos:

#### Requisitos del Repositorio:
- [ ] Crear una rama con el formato: `nombre-portafolio-semana-01`
- [ ] Todos los cambios deben estar commiteados en esta rama
- [ ] El proyecto debe contener solo archivos HTML (sin CSS ni JavaScript)

#### Requisitos Técnicos del Curriculum:

1. **Estructura y Semántica:**
   - [ ] Uso exclusivo de contenedores semánticos (header, main, section, footer, etc.)
   - [ ] Solo usar div/span cuando no exista una alternativa semántica apropiada
   - [ ] Mínimo 2 secciones diferentes (`<section>`)

2. **Encabezados:**
   - [ ] Usar 3 niveles diferentes de encabezados (h1, h2, h3)
   - [ ] Mantener una jerarquía lógica de encabezados

3. **Contenido Multimedia:**
   - [ ] Incluir al menos una imagen personal o profesional
   - [ ] La imagen debe tener sus atributos alt y title apropiados

4. **Enlaces:**
   - [ ] Incluir 3 enlaces a sitios externos
   - [ ] Los enlaces deben abrirse en una nueva pestaña
   - [ ] Pueden ser a redes profesionales (LinkedIn, GitHub, etc.)

5. **Listas:**
   - [ ] Mínimo 3 listas en total
   - [ ] Al menos una lista ordenada (`<ol>`)
   - [ ] Al menos una lista desordenada (`<ul>`)
   - [ ] Pueden usarse para: habilidades, experiencia, educación, etc.

6. **Contenido Textual:**
   - [ ] Al menos 1 párrafo (`<p>`) con información relevante
   - [ ] Texto bien estructurado y con buena ortografía

7. **Formulario de Contacto:**
   - [ ] Implementar un formulario de contacto con:
     - [ ] Campo para correo electrónico
     - [ ] Campo para número telefónico
     - [ ] Botón de envío
   - [ ] Usar las etiquetas y tipos de input apropiados
   - [ ] Incluir labels para cada campo

### Estructura Sugerida del Curriculum:
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Curriculum - [Tu Nombre]</title>
</head>
<body>
    <header>
        <!-- Información principal: Nombre, título profesional, foto -->
    </header>
    
    <main>
        <section id="perfil">
            <!-- Resumen profesional -->
        </section>
        
        <section id="experiencia">
            <!-- Experiencia laboral en lista -->
        </section>
        
        <section id="educacion">
            <!-- Formación académica en lista -->
        </section>
        
        <section id="habilidades">
            <!-- Skills técnicos y blandos en listas -->
        </section>
    </main>
    
    <aside>
        <section id="contacto">
            <!-- Formulario de contacto -->
        </section>
    </aside>
    
    <footer>
        <!-- Enlaces a redes, copyright, etc. -->
    </footer>
</body>
</html>
```

### Criterios de Evaluación:
- Cumplimiento de todos los requisitos técnicos mencionados
- Correcto uso de la semántica HTML
- Estructura lógica y ordenada del contenido
- Código limpio y bien indentado
- Uso apropiado de Git (commits descriptivos y branch correctamente nombrada)