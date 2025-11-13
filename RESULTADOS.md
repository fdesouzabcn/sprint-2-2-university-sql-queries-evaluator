# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 22 correctas de 26 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.47 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,nif, PRIMARY,id_asignatura,id_curso_escolar

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor,id_grado, PRIMARY,id_departamento

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 12: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre
+departamento
 Filología
 Derecho
 Biología y Geología
```

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: id_profesor

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre
+departamento
 Informática
 Matemáticas
 Economía y Empresa
```

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_departamento, id_profesor, id_asignatura

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Error
- **Descripción**: 1055 (42000): Expression #2 of ORDER BY clause is not in GROUP BY clause and contains nonaggregated column 'universidad.p.nombre' which is not functionally dependent on columns in GROUP BY clause; this is incompatible with sql_mode=only_full_group_by


## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
 departamento | total
+Educación | 3.00
+Química y Física | 2.00
+Matemáticas | 2.00
 Informática | 2.00
-Matemáticas | 2.00
 Economía y Empresa | 2.00
-Educación | 3.00
 Agronomía | 1.00
-Química y Física | 2.00
 Filología | 0.00
 Derecho | 0.00
 Biología y Geología | 0.00
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 22: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_grado

---

## ✅ Query 23: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 24: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 26: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---
