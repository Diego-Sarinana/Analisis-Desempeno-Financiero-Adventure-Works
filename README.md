# Analisis-Desempeno-Financiero-Adventure-Works
Análisis para medir los ingresos y rentabilidad para el Director Financiero de Adventure Works (Trabajado con SQL y Google Sheets)

## 🗃️ Datos: 
- Un subconjunto del dataset de AdventureWorks. Incluye las tablas;

ventas_2017 → transacciones de líneas de pedido del año 2017 (numero_pedido, fecha_pedido, fecha_inventario, clave_producto,	clave_cliente, clave_territorio, cantidad_pedido).

productos → catálogo con atributos, costo y precio unitario (clave_producto, clave_subcategoria, sku_producto, nombre_producto, nombre_modelo, descripcion_producto, color_producto, talla_producto, estilo_producto, costo_producto, precio_producto).

productos_categorias → jerarquía categoría/subcategoría para enriquecer productos (clave_subcategoria, subcategoria_descripcion, clave_categoria, categoria_descripcion).

clientes → incluye información relevante de los clientes (clave_cliente, nombre, apellido, fecha_nacimiento, estado_civil, ingreso_anual, total_hijos, nivel_educativo, ocupacion).

territorios → tabla con los países y continentes con sus respectivas claves para identificarlos más fácilmente (clave_territorio, pais, continente).

campanas → tabla que nos permite identificar el costo de las campañas en cada territorio (clave_territorio, costo_campana).

## 📂 Contenido del repositorio

Diego-Sarinana/Analisis-Desempeno-Financiero-Adventure-Works - Se hizo una exploración, limpieza y análisis en un proceso dividido en las siguientes etapas: 
1. Carga y exploración
2. Extracción y Limpieza de Datos con SQL
3. Cálculo de KPIs
4. Validación de resultados
5. Quality Assurance
6. Preparación de outputs
7. Redacción de Resumen ejecutivo

## ▶ Cómo abrir el archivo en Google Sheets/Excel

1. Descarga el archivo dando clic al botón de 'Download raw file' tras haber abierto la sección del proyecto (Diego-Sarinana/Analisis-Desempeno-Financiero-Adventure-Works)
2. En la herramienta de su elección (Excel/Sheets) abra el archivo

O: Abre el siguiente enlace;
https://docs.google.com/spreadsheets/d/17iHJEa_nTdo7tpCsg9aV4Tee67nAoYR6kUT3YFXiUrc/edit?usp=sharing
  
## 📘 Cómo reproducir el análisis:
El archivo incluye el resumen ejecutivo del análisis con los resultados de los cálculos de ingresos, costos, margen de ganancia, etc. el cual no requiere de alguna interacción.
   
## 🧠 Objetivo del análisis:
Responder;
1. ¿Cuánto estamos ganando por país? 
2. ¿Qué tan rentable es cada mercado considerando los gastos de marketing?

## 🗣️ Recomendación de negocio:
- Considerando que Estados Unidos resulta en tener el mejor mercado por su rentabilidad sobresaliente en contraste con Australia que tiene el menor margen de ganancia y que Francia y Canadá tienen la menor efectividad en cuanto a campañas, la recomendación es dirigir la inversión principal a Estados Unidos y revisar las campañas de Francia y Canadá e identificar los fallos pricnpales para mejorar los resultados.
