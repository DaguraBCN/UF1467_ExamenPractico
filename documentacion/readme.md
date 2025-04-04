# 🚀 UF1467_ExamenPractico 🚀

Es la creación de un repositorio donde esta subido el examen practico de la unidad UF1467.
En el cual hemos corregido varios errores en un HTML, CSS y Javascript
Hemos creado un fichero CSV, excel, un fichero word y un PDF.
---

## 📋 Tabla de Contenidos

- [🚀 UF1467\_ExamenPractico 🚀](#-uf1467_examenpractico-)
  - [Hemos creado un fichero CSV, excel, un fichero word y un PDF.](#hemos-creado-un-fichero-csv-excel-un-fichero-word-y-un-pdf)
  - [📋 Tabla de Contenidos](#-tabla-de-contenidos)
  - [📦 Instalación](#-instalación)
    - [Requisitos](#requisitos)
    - [Pasos](#pasos)
  - [▶️ Uso](#️-uso)
    - [Funcionalidades principales:](#funcionalidades-principales)
  - [🧰 Tecnologías](#-tecnologías)
  - [📁 Estructura del Proyecto](#-estructura-del-proyecto)
  - [🤝 Contribución](#-contribución)
  - [🪪 Licencia](#-licencia)
  - [👤 Autor](#-autor)
  - [🗕 Estado del Proyecto](#-estado-del-proyecto)

---

## 📦 Instalación

### Requisitos

- VS Code
- Word
- Excel
- CSV
- Git

### Pasos

>[!NOTE]
>Corregimos el bucle for

```javascript
for (let i = 1; i <= 1000; i++) { 
      
      const fecha = generarFechaAleatoria();
      const cantidad = Math.floor(Math.random() * 10) + 1;
      const producto = productos[Math.floor(Math.random() * productos.length)];
      const precioUnitario = (Math.random() * 90 + 10).toFixed(2); // entre 10.00 y 100.00
      const importe = (cantidad * precioUnitario).toFixed(2);

      const fila = [fecha, cantidad, `"${producto}"`, importe].join(",");
      filas.push(fila);
    }
```

---

## ▶️ Uso

Abre tu navegador y accede a:

```
http://localhost:8000/
```

### Funcionalidades principales:

- Aprobar el examen del módulo UF1467

---

## 🧰 Tecnologías

- **Backend:** Javascript
- **Frontend:** HTML, CSS
- **Extras:** Excel, Word

---

## 📁 Estructura del Proyecto

```
UF1467_EXAMENPRACTICO/
├── codigo/
│   ├── index.html
│   ├── main.js
│   ├── style.css
│   └── ...
├── documentacion/
│   ├── datos.xlsx
│   ├── readme.md
│   ├── UF1467_ExamenPractico.docx
│   ├── UF1467_ExamenPractico.pdf
│   ├── ventas_1000_resgistro.csv
│   └── ...
```

---

## 🤝 Contribución

¡Las contribuciones son bienvenidas!

1. Haz un fork
2. Crea una nueva rama: `git checkout -b feature/mi-feature`
3. Haz commit de tus cambios: `git commit -m 'Agrega nueva funcionalidad'`
4. Sube tu rama: `git push origin feature/mi-feature`
5. Abre un Pull Request

---

## 🪪 Licencia

Este proyecto no tiene licencia. Consulta el archivo [LICENSE](LICENSE) para más información.

---

## 👤 Autor

**David Gutierrez Ramos**  
GitHub: [@DaguraBCN](https://github.com/DaguraBCN)

---

## 🗕 Estado del Proyecto

📈 En desarrollo

- [x] CRUD de tareas
- [ ] Autenticación avanzada
- [ ] Despliegue en producción
