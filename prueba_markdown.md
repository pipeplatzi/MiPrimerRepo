markdown
# Guía rápida de Markdown

¡Bienvenido a este archivo de ejemplo! Aquí aprenderás los elementos básicos de **Markdown**, un lenguaje de marcado ligero.

---

## 1. Estilos de texto

* Esto es texto en **negrita** (usando dos asteriscos).
* Esto es texto en __negrita__ (usando guiones bajos).
* Esto es texto en *cursiva* (usando un asterisco).
* Esto es texto en _cursiva_ (usando un guion bajo).
* Esto es ***negrita y cursiva*** a la vez.
* Esto es texto ~~tachado~~.
* Puedes resaltar texto usando `código en línea`.

---

## 2. Encabezados (Títulos)

# Encabezado 1 (El más grande)
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6 (El más pequeño)

---

## 3. Listas

### Lista con viñetas (desordenada)
* Elemento uno
* Elemento dos
  * Sub-elemento A
  * Sub-elemento B
* Elemento tres

### Lista numerada (ordenada)
1. Primer paso
2. Segundo paso
3. Tercer paso

### Lista de tareas (Checklist)
- [x] Aprender los conceptos básicos de Markdown
- [x] Escribir el primer archivo `.md`
- [ ] Practicar todos los días

---

## 4. Enlaces e imágenes

Puedes agregar un enlace a un sitio web, por ejemplo, visita [Markdown.es](https://markdown.es/sintaxis-markdown/) para más detalles.

También puedes insertar imágenes (ejemplo de sintaxis):
![Texto alternativo de la imagen](https://placeholder.com)

---

## 5. Citas (Blockquotes)

> La simplicidad es la máxima sofisticación.
> — *Leonardo da Vinci*
> 
> > Las citas también pueden estar anidadas.

---

## 6. Bloques de código

Puedes mostrar código de programación delimitándolo con tres acentos graves (` ``` `):

```javascript
// Ejemplo en JavaScript
function saludar(nombre) {
    console.log("¡Hola, " + nombre + "!");
}
saludar("Markdown");
```

---

## 7. Tablas

| Herramienta | Tipo | Gratuita |
| :--- | :--- | :---: |
| VS Code | Editor de código | Sí |
| Obsidian | Notas y PKM | Sí |
| Typora | Editor visual | De pago |

---

## 8. Notas o alertas especiales (GFM)

> [!TIP]
> **Consejo útil:** Usa siempre una línea en blanco antes y después de las listas o bloques para que se rendericen bien.

> [!NOTE]
> Los archivos Markdown se guardan típicamente con la extensión `.md`.