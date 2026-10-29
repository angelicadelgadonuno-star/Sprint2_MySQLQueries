# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 13 correctas de 41 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.39 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nom del producte | euros | dòlars
+nombre | euros | dólares
 Disco duro SATA3 1TB | 86.99 | 95.69
 Memoria RAM DDR4 8GB | 120.00 | 132.00
 Disco SSD 1 TB | 150.99 | 166.09
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-DISCO DURO SATA3 1TB | 86.99
-MEMORIA RAM DDR4 8GB | 120.00
-DISCO SSD 1 TB | 150.99
-GEFORCE GTX 1050TI | 185.00
-GEFORCE GTX 1080 XTREME | 755.00
-MONITOR 24 LED FULL HD | 202.00
-MONITOR 27 LED FULL HD | 245.99
-PORTÁTIL YOGA 520 | 559.00
-PORTÁTIL IDEAPD 320 | 444.00
-IMPRESORA HP DESKJET 3720 | 59.99
-IMPRESORA HP LASERJET PRO M26NW | 180.00
+nombre | nombre | precio
+Disco duro SATA3 1TB | DISCO DURO SATA3 1TB | 86.99
+Memoria RAM DDR4 8GB | MEMORIA RAM DDR4 8GB | 120.00
+Disco SSD 1 TB | DISCO SSD 1 TB | 150.99
+GeForce GTX 1050Ti | GEFORCE GTX 1050TI | 185.00
+GeForce GTX 1080 Xtreme | GEFORCE GTX 1080 XTREME | 755.00
+Monitor 24 LED Full HD | MONITOR 24 LED FULL HD | 202.00
+Monitor 27 LED Full HD | MONITOR 27 LED FULL HD | 245.99
+Portátil Yoga 520 | PORTÁTIL YOGA 520 | 559.00
+Portátil Ideapd 320 | PORTÁTIL IDEAPD 320 | 444.00
+Impresora HP Deskjet 3720 | IMPRESORA HP DESKJET 3720 | 59.99
+Impresora HP Laserjet Pro M26nw | IMPRESORA HP LASERJET PRO M26NW | 180.00
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-disco duro sata3 1tb | 86.99
-memoria ram ddr4 8gb | 120.00
-disco ssd 1 tb | 150.99
-geforce gtx 1050ti | 185.00
-geforce gtx 1080 xtreme | 755.00
-monitor 24 led full hd | 202.00
-monitor 27 led full hd | 245.99
-portátil yoga 520 | 559.00
-portátil ideapd 320 | 444.00
-impresora hp deskjet 3720 | 59.99
-impresora hp laserjet pro m26nw | 180.00
+nombre | nombre | precio
+Disco duro SATA3 1TB | disco duro sata3 1tb | 86.99
+Memoria RAM DDR4 8GB | memoria ram ddr4 8gb | 120.00
+Disco SSD 1 TB | disco ssd 1 tb | 150.99
+GeForce GTX 1050Ti | geforce gtx 1050ti | 185.00
+GeForce GTX 1080 Xtreme | geforce gtx 1080 xtreme | 755.00
+Monitor 24 LED Full HD | monitor 24 led full hd | 202.00
+Monitor 27 LED Full HD | monitor 27 led full hd | 245.99
+Portátil Yoga 520 | portátil yoga 520 | 559.00
+Portátil Ideapd 320 | portátil ideapd 320 | 444.00
+Impresora HP Deskjet 3720 | impresora hp deskjet 3720 | 59.99
+Impresora HP Laserjet Pro M26nw | impresora hp laserjet pro m26nw | 180.00
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+nombre | ROUND(precio)
 Disco duro SATA3 1TB | 87.00
 Memoria RAM DDR4 8GB | 120.00
 Disco SSD 1 TB | 151.00
```

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio truncado
+nombre | precio
 Disco duro SATA3 1TB | 86.00
 Memoria RAM DDR4 8GB | 120.00
 Disco SSD 1 TB | 150.00
```

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,12 @@
-nombre
-Asus
-Crucial
-Gigabyte
-Hewlett-Packard
-Huawei
-Lenovo
-Samsung
-Seagate
-Xiaomi
+codigo | nombre | precio | codigo_fabricante
+1.00 | Disco duro SATA3 1TB | 86.99 | 5.00
+3.00 | Disco SSD 1 TB | 150.99 | 4.00
+4.00 | GeForce GTX 1050Ti | 185.00 | 7.00
+5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
+10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
+11.00 | Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
+2.00 | Memoria RAM DDR4 8GB | 120.00 | 6.00
+6.00 | Monitor 24 LED Full HD | 202.00 | 1.00
+7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
```

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 14: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,12 @@
-nombre
-Xiaomi
-Seagate
-Samsung
-Lenovo
-Huawei
-Hewlett-Packard
-Gigabyte
-Crucial
-Asus
+codigo | nombre | precio | codigo_fabricante
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+6.00 | Monitor 24 LED Full HD | 202.00 | 1.00
+2.00 | Memoria RAM DDR4 8GB | 120.00 | 6.00
+11.00 | Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
+10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
+5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
+4.00 | GeForce GTX 1050Ti | 185.00 | 7.00
+3.00 | Disco SSD 1 TB | 150.99 | 4.00
+1.00 | Disco duro SATA3 1TB | 86.99 | 5.00
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio
-Impresora HP Deskjet 3720 | 59.99
+nombre
+Impresora HP Deskjet 3720
```

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio
-GeForce GTX 1080 Xtreme | 755.00
+nombre
+GeForce GTX 1080 Xtreme
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre
-Portátil Yoga 520
-Portátil Ideapd 320
+codigo | nombre | precio | codigo_fabricante
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
```

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio | nombre del fabricante
-Disco duro SATA3 1TB | 86.99 | Seagate
-Memoria RAM DDR4 8GB | 120.00 | Crucial
-Disco SSD 1 TB | 150.99 | Samsung
-GeForce GTX 1050Ti | 185.00 | Gigabyte
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-Monitor 24 LED Full HD | 202.00 | Asus
-Monitor 27 LED Full HD | 245.99 | Asus
-Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+producto | precio | fabricante | codigo_fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate | 5.00
+Memoria RAM DDR4 8GB | 120.00 | Crucial | 6.00
+Disco SSD 1 TB | 150.99 | Samsung | 4.00
+GeForce GTX 1050Ti | 185.00 | Gigabyte | 7.00
+GeForce GTX 1080 Xtreme | 755.00 | Crucial | 6.00
+Monitor 24 LED Full HD | 202.00 | Asus | 1.00
+Monitor 27 LED Full HD | 245.99 | Asus | 1.00
+Portátil Yoga 520 | 559.00 | Lenovo | 2.00
+Portátil Ideapd 320 | 444.00 | Lenovo | 2.00
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | 3.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
```

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 22: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio | nombre del fabricante
-Monitor 24 LED Full HD | 202.00 | Asus
-Monitor 27 LED Full HD | 245.99 | Asus
-Memoria RAM DDR4 8GB | 120.00 | Crucial
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-GeForce GTX 1050Ti | 185.00 | Gigabyte
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
-Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Disco SSD 1 TB | 150.99 | Samsung
-Disco duro SATA3 1TB | 86.99 | Seagate
+producto | precio | fabricante | codigo_fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate | 5.00
+Disco SSD 1 TB | 150.99 | Samsung | 4.00
+GeForce GTX 1050Ti | 185.00 | Gigabyte | 7.00
+GeForce GTX 1080 Xtreme | 755.00 | Crucial | 6.00
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | 3.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
+Memoria RAM DDR4 8GB | 120.00 | Crucial | 6.00
+Monitor 24 LED Full HD | 202.00 | Asus | 1.00
+Monitor 27 LED Full HD | 245.99 | Asus | 1.00
+Portátil Ideapd 320 | 444.00 | Lenovo | 2.00
+Portátil Yoga 520 | 559.00 | Lenovo | 2.00
```

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-codigo | nombre | codigo fabricante | nombre fabricante
-1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
-2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
-3.00 | Disco SSD 1 TB | 4.00 | Samsung
-4.00 | GeForce GTX 1050Ti | 7.00 | Gigabyte
-5.00 | GeForce GTX 1080 Xtreme | 6.00 | Crucial
-6.00 | Monitor 24 LED Full HD | 1.00 | Asus
-7.00 | Monitor 27 LED Full HD | 1.00 | Asus
-8.00 | Portátil Yoga 520 | 2.00 | Lenovo
-9.00 | Portátil Ideapd 320 | 2.00 | Lenovo
-10.00 | Impresora HP Deskjet 3720 | 3.00 | Hewlett-Packard
-11.00 | Impresora HP Laserjet Pro M26nw | 3.00 | Hewlett-Packard
+producto | precio | fabricante | codigo_fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate | 5.00
+Memoria RAM DDR4 8GB | 120.00 | Crucial | 6.00
+Disco SSD 1 TB | 150.99 | Samsung | 4.00
+GeForce GTX 1050Ti | 185.00 | Gigabyte | 7.00
+GeForce GTX 1080 Xtreme | 755.00 | Crucial | 6.00
+Monitor 24 LED Full HD | 202.00 | Asus | 1.00
+Monitor 27 LED Full HD | 245.99 | Asus | 1.00
+Portátil Yoga 520 | 559.00 | Lenovo | 2.00
+Portátil Ideapd 320 | 444.00 | Lenovo | 2.00
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | 3.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
```

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,12 @@
-nombre | precio | fabricant
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
+producto | precio | fabricante | codigo_fabricante
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | 3.00
+Disco duro SATA3 1TB | 86.99 | Seagate | 5.00
+Memoria RAM DDR4 8GB | 120.00 | Crucial | 6.00
+Disco SSD 1 TB | 150.99 | Samsung | 4.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
+GeForce GTX 1050Ti | 185.00 | Gigabyte | 7.00
+Monitor 24 LED Full HD | 202.00 | Asus | 1.00
+Monitor 27 LED Full HD | 245.99 | Asus | 1.00
+Portátil Ideapd 320 | 444.00 | Lenovo | 2.00
+Portátil Yoga 520 | 559.00 | Lenovo | 2.00
+GeForce GTX 1080 Xtreme | 755.00 | Crucial | 6.00
```

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 25: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,12 @@
-nombre | precio | fabricante
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
+producto | precio | fabricante | codigo_fabricante
+GeForce GTX 1080 Xtreme | 755.00 | Crucial | 6.00
+Portátil Yoga 520 | 559.00 | Lenovo | 2.00
+Portátil Ideapd 320 | 444.00 | Lenovo | 2.00
+Monitor 27 LED Full HD | 245.99 | Asus | 1.00
+Monitor 24 LED Full HD | 202.00 | Asus | 1.00
+GeForce GTX 1050Ti | 185.00 | Gigabyte | 7.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
+Disco SSD 1 TB | 150.99 | Samsung | 4.00
+Memoria RAM DDR4 8GB | 120.00 | Crucial | 6.00
+Disco duro SATA3 1TB | 86.99 | Seagate | 5.00
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | 3.00
```

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 26: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | precio
-Portátil Yoga 520 | 559.00
-Portátil Ideapd 320 | 444.00
+producto | precio | fabricante | codigo_fabricante
+Portátil Yoga 520 | 559.00 | Lenovo | 2.00
+Portátil Ideapd 320 | 444.00 | Lenovo | 2.00
```

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 27: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio
-GeForce GTX 1080 Xtreme | 755.00
+producto | precio | fabricante | codigo_fabricante
+GeForce GTX 1080 Xtreme | 755.00 | Crucial | 6.00
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 28: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,6 @@
-nombre | precio | fabricante
-Disco duro SATA3 1TB | 86.99 | Seagate
-Monitor 24 LED Full HD | 202.00 | Asus
-Monitor 27 LED Full HD | 245.99 | Asus
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+producto | precio | fabricante | codigo_fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate | 5.00
+Monitor 24 LED Full HD | 202.00 | Asus | 1.00
+Monitor 27 LED Full HD | 245.99 | Asus | 1.00
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | 3.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
```

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 29: Incorrecto
```diff
--- 
+++ 
@@ -1,6 +1,6 @@
-nombre | precio | fabricante
-Disco duro SATA3 1TB | 86.99 | Seagate
-Monitor 24 LED Full HD | 202.00 | Asus
-Monitor 27 LED Full HD | 245.99 | Asus
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+producto | precio | fabricante | codigo_fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate | 5.00
+Monitor 24 LED Full HD | 202.00 | Asus | 1.00
+Monitor 27 LED Full HD | 245.99 | Asus | 1.00
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | 3.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
```

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Considerar `EXISTS` en lugar de `IN` para eficiencia.

---

## ❌ Query 30: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | precio | fabricante
-Disco duro SATA3 1TB | 86.99 | Seagate
-GeForce GTX 1050Ti | 185.00 | Gigabyte
+producto | precio | fabricante | codigo_fabricante
+Disco duro SATA3 1TB | 86.99 | Seagate | 5.00
+GeForce GTX 1050Ti | 185.00 | Gigabyte | 7.00
```

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 31: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | precio | fabricante
-Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+producto | precio | fabricante | codigo_fabricante
+Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard | 3.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
```

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 32: Incorrecto
```diff
--- 
+++ 
@@ -1,8 +1,8 @@
-nombre | precio | fabricante
-GeForce GTX 1080 Xtreme | 755.00 | Crucial
-Portátil Yoga 520 | 559.00 | Lenovo
-Portátil Ideapd 320 | 444.00 | Lenovo
-Monitor 27 LED Full HD | 245.99 | Asus
-Monitor 24 LED Full HD | 202.00 | Asus
-GeForce GTX 1050Ti | 185.00 | Gigabyte
-Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard
+producto | precio | fabricante | codigo_fabricante
+GeForce GTX 1080 Xtreme | 755.00 | Crucial | 6.00
+Portátil Yoga 520 | 559.00 | Lenovo | 2.00
+Portátil Ideapd 320 | 444.00 | Lenovo | 2.00
+Monitor 27 LED Full HD | 245.99 | Asus | 1.00
+Monitor 24 LED Full HD | 202.00 | Asus | 1.00
+GeForce GTX 1050Ti | 185.00 | Gigabyte | 7.00
+Impresora HP Laserjet Pro M26nw | 180.00 | Hewlett-Packard | 3.00
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 33: Incorrecto
```diff
--- 
+++ 
@@ -1,8 +1,8 @@
-codigo | nombre
-1.00 | Asus
-2.00 | Lenovo
-3.00 | Hewlett-Packard
-4.00 | Samsung
-5.00 | Seagate
-6.00 | Crucial
-7.00 | Gigabyte
+fabricante | codigo_fabricante
+Asus | 1.00
+Lenovo | 2.00
+Hewlett-Packard | 3.00
+Samsung | 4.00
+Seagate | 5.00
+Crucial | 6.00
+Gigabyte | 7.00
```

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ❌ Query 34: Incorrecto
```diff
--- 
+++ 
@@ -1,14 +1,10 @@
-fabricante | producto
-Asus | Monitor 27 LED Full HD
-Asus | Monitor 24 LED Full HD
-Lenovo | Portátil Ideapd 320
-Lenovo | Portátil Yoga 520
-Hewlett-Packard | Impresora HP Laserjet Pro M26nw
-Hewlett-Packard | Impresora HP Deskjet 3720
-Samsung | Disco SSD 1 TB
-Seagate | Disco duro SATA3 1TB
-Crucial | GeForce GTX 1080 Xtreme
-Crucial | Memoria RAM DDR4 8GB
-Gigabyte | GeForce GTX 1050Ti
-Huawei | NULL
-Xiaomi | NULL
+fabricante | codigo_fabricante
+Asus | 1.00
+Lenovo | 2.00
+Hewlett-Packard | 3.00
+Samsung | 4.00
+Seagate | 5.00
+Crucial | 6.00
+Gigabyte | 7.00
+Huawei | 8.00
+Xiaomi | 9.00
```

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 35: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-fabricante
-Huawei
-Xiaomi
+fabricante | codigo_fabricante
+Huawei | 8.00
+Xiaomi | 9.00
```

⏱ Tiempo: 0.27 ms
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
+producto | precio
+Portátil Yoga 520 | 559.00
+Portátil Ideapd 320 | 444.00
```

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 37: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 38: Error
- **Descripción**: 1054 (42S22): Unknown column 'p.nombre' in 'field list'


## ❌ Query 39: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre
+producto
 Impresora HP Deskjet 3720
```

⏱ Tiempo: 0.26 ms
✅ Se usó índice(s) en la consulta: PRIMARY, codigo_fabricante

---

## ✅ Query 40: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 41: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---
