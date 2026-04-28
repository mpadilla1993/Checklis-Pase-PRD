# ✅ Checklist – Pase a Producción RDE desde CDH (Operativa)

**Sistema:** PEGA‑CDH  
**Fecha:** 24/03/2026  

---

## 1️⃣ Creación y preparación del Branch

- [ ] Ingresar a **GIT → Branches / Repos**
- [ ] Seleccionar el repositorio **CDH**
- [ ] Crear un **nuevo Branch**
- [ ] Ingresar nombre del branch
- [ ] Seleccionar rama base **Develop**
- [ ] Crear el branch

---

## 2️⃣ Clonado del repositorio

- [ ] Ingresar al branch recién creado
- [ ] Presionar **Clone**
- [ ] Copiar la **URL del repositorio**
- [ ] Generar credenciales (si aplica)
- [ ] Abrir **GitHub Desktop** en servidor de pruebas
- [ ] Seleccionar **Clonar repositorio**
- [ ] Pegar la URL
- [ ] Seleccionar folder de trabajo
- [ ] Presionar **Clonar**

---

## 3️⃣ Selección de Branch local

- [ ] Cambiar del branch **main** al **branch personal**
- [ ] Verificar branch activo correcto

---

## 4️⃣ Desarrollo y Commit

- [ ] Realizar los cambios necesarios
- [ ] Seleccionar archivos a subir
- [ ] Ingresar título del commit
- [ ] Agregar descripción clara
- [ ] Ejecutar **Commit**
- [ ] Ejecutar **Push**

---

## 5️⃣ Pull Request – Branch personal a Develop

- [ ] Ingresar a **DevOps**
- [ ] Ir a **Pull Requests**
- [ ] Crear PR **Branch personal → Develop**
- [ ] Crear Pull Request
- [ ] Compartir URL con compañero para aprobación

---

## 6️⃣ Pull Request – Develop a MAIN

- [ ] Crear PR **Develop → MAIN**
- [ ] Solicitar aprobación del subgerente
- [ ] Confirmar PR aprobado

---

## 7️⃣ Creación del Pase a Producción (Power Apps)

- [ ] Ingresar a **Pases a Producción – Power Apps**
- [ ] Crear **Nuevo Pase**
- [ ] Completar campos sin candado
- [ ] Indicar tipo de pase:
  - [ ] Pase normal
  - [ ] CDH Operativa
- [ ] Guardar para habilitar campos automáticos

---

## 8️⃣ Información principal del pase

- [ ] Guardar y cerrar **Punto 2**
- [ ] Completar **ID de Origen** (link a tarea dashboard)
- [ ] Agregar **Contenido del Pase**:
  - [ ] Aplicación: **CDH:1\CDH**
  - [ ] Proyecto: **9999**
- [ ] Agregar enlace de tarea de **Azure Boards**

---

## 9️⃣ Detalle del pase

- [ ] Sección 4 – Descripción breve de la tarea
- [ ] Sección 5 – Plan de montaje:
  - [ ] Indicar si requiere plan
  - [ ] Definir horario
  - [ ] Seleccionar medio de comunicación

---

## 🔟 Vistos buenos adicionales

- [ ] Evidencia de pruebas:  
  > “Se adjunta en la sección 7”
- [ ] Revisión:
  - [ ] Ticket DBA (si aplica)
  - [ ] PR Develop → MAIN aprobado

---

## 1️⃣1️⃣ Adjuntar documentación (Sección 7)

- [ ] F‑CORP – Guía Ejecución Casos de Prueba (PN‑0018512 v15)
- [ ] Plan de Montaje
- [ ] Análisis de Impacto BI v1.0
- [ ] Subir archivos **uno por uno**
- [ ] Guardar y cerrar tras cada carga

---

## 1️⃣2️⃣ Carga de archivos en SVN

- [ ] Crear ZIP con archivos del pase
- [ ] Clic derecho → **TortoiseSVN**
- [ ] Abrir **Repo‑Browser**
- [ ] Seleccionar carpeta **CDH**
- [ ] **Add File** → seleccionar ZIP
- [ ] Confirmar carga

> ⚠️ **Nota:** Este paso debe hacerse antes de enviar el pase a aprobación.

---

## 1️⃣3️⃣ Envío a aprobación

- [ ] Completar punto 10 del pase
- [ ] Enviar a pase a aprobar
- [ ] Agregar comentario:  
  _“Por favor su apoyo con el pase”_
- [ ] Guardar y cerrar
- [ ] Enviar a **PO (Marco Mata)**
- [ ] Enviar a **Jesús Porras**
- [ ] Confirmar ambas aprobaciones

---

## 1️⃣4️⃣ Comunicación en TEAMS

- [ ] Crear tarea en **Summary – Overview**
- [ ] Enviar mensaje en **CST‑CAB Asíncrono DWH y Provisiones**
- [ ] Utilizar machote oficial de pase a producción

---

✅ **Checklist completo cuando todas las casillas estén marcadas**
