# Proyecto Final — Ecosistema de Automatización IA para Dark Imports

Bot de Telegram con verificación de stock en tiempo real y aprobación humana (HITL), 
construido con Make, Airtable y OpenAI GPT-4o-mini.

## Caso de uso
El bot recibe consultas de clientes sobre productos vía Telegram, identifica el producto 
con IA, verifica stock disponible en Airtable, y espera aprobación humana antes de 
confirmarle la disponibilidad al cliente.

## Entregables

| Criterio | Archivo |
|---|---|
| Mapa de Arquitectura | `01_Mapa_Arquitectura.drawio.pdf` |
| Estructura de Datos | `02_Estructura_de_Datos.pdf` |
| Matriz de Costos | `03_Matriz_de_Costos.pdf` |
| Seguridad y Resiliencia | `04_Seguridad_y_Resiliencia.pdf` |
| Dashboard de Control | [Ver dashboard en vivo](https://airtable.com/appNvL50avnuGS5Hv/pag2F6Wb6QZ4H9Caa) |

## Archivos técnicos
- Blueprints de Make: carpeta `blueprints/`
- Base de datos (modo lectura): [https://airtable.com/appNvL50avnuGS5Hv/shrE11TeZ8RFJHcPr]
- Screenshots de evidencia:

- ## Stack utilizado
- **Orquestador:** Make
- **Base de datos:** Airtable (tablas Catálogo y Consultas)
- **IA:** OpenAI GPT-4o-mini
- **Canal de salida:** Telegram

## Video demo
[https://drive.google.com/file/d/1vp46U_TU6ediAtbCt4g9CUyiVkftGg4N/view?usp=sharing]
