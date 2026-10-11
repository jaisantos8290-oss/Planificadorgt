# PlanificaCNB GT v1.0
## Incluye
- Grados de 1.º a 6.º primaria y áreas por ciclo según DIGECUR.
- Enlaces directos a los documentos oficiales del CNB por grado.
- Generador básico local, edición, copiar e imprimir/guardar PDF.
- Endpoint opcional para conectar Gemini API desde el servidor.
- Campos para que el docente incorpore el texto curricular exacto desde la fuente oficial.

## Ejecutar
1. Instala Node.js 18 o superior.
2. Descomprime el proyecto y abre una terminal en la carpeta.
3. Ejecuta `npm install`.
4. Copia `.env.example` como `.env` y coloca tu clave en `GEMINI_API_KEY`.
5. Ejecuta `npm start`.
6. Abre `http://localhost:3000`.
Sin clave, usa **Generar básico**. Para IA, configura la clave del servidor; nunca la incluyas en el HTML.

## Fuentes oficiales
- DIGECUR Primaria: https://digecur.mineduc.gob.gt/departamentos/nivel-primaria/
- Portal CNB: https://digecur.mineduc.gob.gt/curriculo-nacional-base-cnb/
- Mallas curriculares: https://cnb.mineduc.gob.gt/mediawiki/index.php?title=Mallas_Curriculares_por_%C3%81rea_y_Grado_-_Primaria

El catálogo incluye metadatos y enlaces, no copia el texto completo de los CNB. Los documentos oficiales incluyen restricciones de reproducción para usos comerciales. Antes de incorporar textos extensos a un producto comercial, solicita permiso a MINEDUC/DIGECUR o asesoría sobre los permisos aplicables. Verifica siempre que la competencia, indicador y contenido correspondan al grado y área.

## Antes de vender o publicar
No incluye alojamiento público, cuentas, pagos, límites por usuario ni base de datos. Antes de vender añade HTTPS, control de uso/costos, autenticación si procede, política de privacidad, términos, soporte y pruebas docentes. No introduzcas datos personales identificables de estudiantes. Revisa los términos, disponibilidad y precios vigentes de la API de IA.
La app es independiente y no está afiliada ni avalada por MINEDUC.
