# 📊 PPR Retirement Calculator (Excel)

Herramienta en Excel para simular tu **Plan Personal de Retiro (PPR)** con interés compuesto y proyección anual automática.

---

## 🚀 Features
- Inputs editables (edad, retiro, ahorro, rendimiento).  
- Cálculo automático con **FV()**.  
- Tabla anual con interés compuesto.  
- Fórmulas financieras listas para usar.

---

## 🧮 Fórmulas clave

**Valor futuro (FV):**
=FV(rendimiento/12, años*12, -ahorro_mensual)

markdown
Copiar código

**Total acumulado anual:**
=D8*(1+$B$5/12)^12 + $B$4*((1+$B$5/12)^12 -1)/($B$5/12)

yaml
Copiar código

---

## 📂 Contenido
📄 PPR.xlsx
📄 README.md

yaml
Copiar código

---

## ⭐ Notas
- Rendimiento usado: **7% anual** (promedio PPR en México).  
- No borres celdas con fórmulas.  
- Compatible con Excel 2016+.

---

## 👨‍💻 Autor
Proyecto creado para simulación y educación financiera.
