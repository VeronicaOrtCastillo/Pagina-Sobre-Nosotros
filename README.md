## Equipo: Java Force & Los Scripts (Equipo 2)

**Repo:** `https://github.com/VeronicaOrtCastillo/Pagina-Sobre-Nosotros`
**Entrega:** Lunes 30 de marzo, 23:30

---

## Rubrica (3 criterios)
1. La pagina debe ser **responsiva** (desktop, tablet y movil)
2. Utiliza al menos **1 animacion o efecto** usando CSS/JS
3. La herramienta de desarrolladores **no da errores**

---

## 1. Objetivo

Crear la pagina **"Quienes Somos"** de La 5ta Esencia como equipo, donde cada integrante trabaja en su propia rama de Git y hace commits individuales.

La pagina incluye:
- Historia de la empresa
- Mision, Vision y Valores
- Tarjetas de presentacion de los 10 integrantes
- Diseño responsivo con la paleta Reserva Clasica
- Al menos 1 animacion CSS

---

## 2. Estructura del proyecto

```
Pagina-Sobre-Nosotros/
├── index.html          <- Pagina principal (quienes somos)
├── css/
│   └── styles.css      <- Estilos divididos por secciones
├── img/
│   ├── logo.jpeg       <- Logo de la marca
│   ├── hero.jpg        <- Imagen hero de fondo
│   └── team/           <- Fotos individuales del equipo
│       ├── alex.jpg
│       ├── brenda.jpg
│       ├── chris.jpg
│       ├── vianey.jpg
│       ├── angel.jpg
│       ├── daniel.jpg
│       ├── fer.jpg
│       ├── eduardo.jpg
│       ├── vero.jpg
│       └── victor.jpg
└── README.md    <- Este archivo
```

---

## 3. Convencion de ramas

Cada integrante trabaja en su propia rama:

```
feature/quienes-somos-nombre
```

| Integrante | Ramas                         |
|------------|-------------------------------|
| Alex       | `feature/quienes-somos-alex`  |
| Brenda     | `Brenda`                      |
| Chris      | `feature/quienes-somos-chris` |
| Vianey     | `eyvian_feature`              |
| Angel      | `Angel-feature`               |
| Daniel     | `Daniel-feature`              |
| Fer        | `FerAO-feature`               |
| Eduardo    |`feature/quienes-somos-eduardo`|
| Vero       | `vero/feature`                |
| Victor     | `victor-feature`              |

---

## 4. Flujo de trabajo en Git

### Paso 1: Clonar el repo
```bash
git clone https://github.com/VeronicaOrtCastillo/Pagina-Sobre-Nosotros.git
cd Pagina-Sobre-Nosotros
```

### Paso 2: Crear tu rama
```bash
git checkout main
git pull origin main
git checkout -b TU-NOMBRE-feature
```

### Paso 3: Hacer tu trabajo
Edita SOLO los archivos y secciones que te corresponden (ver seccion 6).

### Paso 4: Commits
```bash
git add .
git commit -m "DESCRIPCION DE LO REALIZADO"
```

### Paso 5: Push de tu rama
```bash
git push origin TU-NOMBRE-feature
```

### Paso 6: Crear Pull Request
Ve a GitHub > Pull requests > "New Pull Request" > base: main - compare: TU-NOMBRE-feature

**NUNCA hagas push directo a main.**

---

## 5. Convencion de commits

Formato: `tipo: descripcion corta`

Ejemplos:
```
feat: agrega estructura base HTML
feat: agrega tarjeta de presentacion de Alex
style: agrega estilos de la seccion hero
style: hace responsive las tarjetas del equipo
fix: corrige error en ruta de imagen
docs: agrega instrucciones del proyecto
```

---

## 6. Distribucion del trabajo (10 integrantes)

---

### Integrante 1: VERO (Veronica Ortiz)
**Rol:** Estructura base + Header + Footer
**Rama:** `vero/feature`
**Archivos:** `index.html`

**Que hace:**
- Crea el archivo `index.html` con la estructura completa (dentro de `<main>`)
- Header con logo y navegacion
- Footer con contacto
- Vincula `css/styles.css`

**Que NO toca:** Las tarjetas del equipo ni los estilos CSS

---

### Integrante 2: FER (Fernando Aquino)
**Rol:** Seccion Hero + Historia
**Rama:** `FerAO-Feature`
**Archivos:** `index.html` (dentro de `<main>`)

**Que hace:**
- Seccion hero con imagen de fondo y titulo
- Seccion "Nuestra Historia" con el texto oficial

**Que NO toca:** Header, footer, tarjetas, CSS

---

### Integrante 3: BRENDA (Brenda Villar)
**Rol:** Seccion Mision y Vision
**Rama:** `Brenda`
**Archivos:** `index.html` (dentro de `<main>`)

**Que hace:**
- Seccion con tarjetas de Mision y Vision

---

### Integrante 4: VICTOR (Victor Hernandez)
**Rol:** Seccion Valores (6 tarjetas)
**Rama:** `victor-feature`
**Archivos:** `index.html` (dentro de `<main>`)

**Que hace:**
- Grid de 6 valores con iconos

---

### Integrante 5: ALEX (Alejandro Gonzalez)
**Rol:** Titulo de seccion equipo + Tarjetas integrantes 1-5
**Rama:** `feature/quienes-somos-alex`
**Archivos:** `index.html` (dentro de `<main>`)

**Que hace:**
- Titulo "Nuestro Equipo"
- Tarjetas de: Alex, Brenda, Chris, Vianey, Angel

---

### Integrante 6: DANIEL (Daniel Aguilar)
**Rol:** Tarjetas integrantes 6-10 + cierre de seccion
**Rama:** `Daniel-feature`
**Archivos:** `index.html` (dentro de `<main>`)

**Que hace:**
- Tarjetas de: Daniel, Fer, Eduardo, Vero, Victor
- Cierra la seccion equipo

---

### Integrante 7: CHRIS (Christian Escamilla)
**Rol:** CSS Base + Variables + Reset + Header/Footer/Hero
**Rama:** `feature/quienes-somos-chris`
**Archivos:** `css/styles.css`

**Que hace:**
- Variables CSS (paleta Reserva Clasica)
- Reset y tipografia base
- Estilos del header, footer y hero

---

### Integrante 8: EDUARDO (Eduardo Villedas)
**Rol:** CSS Secciones (Historia, Filosofia, Valores)
**Rama:** `feature/quienes-somos-eduardo`
**Archivos:** `css/styles.css` (agrega al final)

**Que hace:**
- Estilos de las secciones Historia, Filosofia y Valores
- Incluye la animacion CSS requerida (fade-in)

---

### Integrante 9: ANGEL (Angel Juarez)
**Rol:** CSS Tarjetas del equipo
**Rama:** `Angel-feature`
**Archivos:** `css/styles.css` (agrega al final)

**Que hace:**
- Estilos de las tarjetas del equipo
- Efecto hover en las tarjetas

---

### Integrante 10: VIANEY (Vianey Lopez)
**Rol:** CSS Responsive + Revision final
**Rama:** `eyvian_feature`
**Archivos:** `css/styles.css` (agrega al final)

**Que hace:**
- Media queries para tablet y movil
- Revisa que no haya errores en consola
- Prueba en Chrome DevTools

---

## 7. Orden de trabajo recomendado

Para evitar conflictos, trabajen en este orden:

| Orden | Quien         | Que hace                  |
|-------|---------------|---------------------------|
| 1ro   | **Vero**      | Estructura base HTML      |
| 2do   | **Chris**     | CSS base + variables      |
| 3ro   | **Fer**       | Seccion Hero + Historia   |
| 3ro   | **Brenda**    | Seccion Mision/Vision     |
| 3ro   | **Victor**    | Seccion Valores           |
| 4to   | **Alex**      | Tarjetas equipo 1-5       |
| 4to   | **Daniel**    | Tarjetas equipo 6-10      |
| 5to   | **Eduardo**   | CSS secciones + animacion |
| 5to   | **Angel**     | CSS tarjetas equipo       |
| 6to   | **Vianey**    | CSS responsive + revision | 

---

## 8. Checklist final

- [ ] Pagina se ve bien en desktop (>1024px)
- [ ] Pagina se ve bien en tablet (768px)
- [ ] Pagina se ve bien en movil (480px)
- [ ] Al menos 1 animacion CSS funciona (hover o fade-in)
- [ ] Consola de desarrolladores sin errores
- [ ] Todos los commits son individuales
- [ ] Cada integrante trabajo en su propia rama
- [ ] Todo se integro en main via Pull Request

---

## 9. Link del repositorio
```
https://github.com/VeronicaOrtCastillo/Pagina-Sobre-Nosotros 
```

**Fecha limite: Lunes 30 de marzo, 23:30**
