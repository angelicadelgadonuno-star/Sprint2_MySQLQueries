# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 39 correctas de 41 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.12 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.21 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.18 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.17 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.15 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.18 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.14 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.17 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.13 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.14 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 22: Correcto

⏱ Tiempo: 0.17 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 23: Correcto

⏱ Tiempo: 0.15 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 24: Correcto

⏱ Tiempo: 0.17 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.15 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.15 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 27: Correcto

⏱ Tiempo: 0.17 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 28: Correcto

⏱ Tiempo: 0.17 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 29: Correcto

⏱ Tiempo: 0.19 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ✅ Query 30: Correcto

⏱ Tiempo: 0.16 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 31: Correcto

⏱ Tiempo: 0.15 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 32: Correcto

⏱ Tiempo: 0.19 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 33: Correcto

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 34: Correcto

⏱ Tiempo: 0.19 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 35: Correcto

⏱ Tiempo: 0.16 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 36: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-codigo | nombre | precio | codigo_fabricante
-8.00 | Portátil Yoga 520 | 559.00 | 2.00
-9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+producto | precio | codigo_fabricante
+Portátil Yoga 520 | 559.00 | 2.00
+Portátil Ideapd 320 | 444.00 | 2.00
```

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 37: Correcto

⏱ Tiempo: 0.20 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 38: Error
- **Descripción**: 1054 (42S22): Unknown column 'p.nombre' in 'field list'


## ✅ Query 39: Correcto

⏱ Tiempo: 0.18 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 40: Correcto

⏱ Tiempo: 0.19 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 41: Correcto

⏱ Tiempo: 0.22 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
