# OCR Test V1

Aplicación independiente para probar OCR sobre nombres y placas de máquinas de gimnasio.

## Funciones
- Cámara de Android y carga desde galería.
- Reducción automática para evitar problemas de memoria.
- Cinco variantes: original, grises, contraste, blanco y negro e invertida.
- OCR Tesseract.js en español e inglés con PSM 7.
- Mejor resultado, confianza, copia e informe JSON.
- Historial local de las últimas 50 pruebas.
- PWA compatible con GitHub Pages.

## Publicación
1. Sube todos los archivos a la raíz de un repositorio.
2. En GitHub: Settings > Pages.
3. En Source, selecciona Deploy from a branch.
4. Selecciona la rama principal y la carpeta raíz.
5. La primera ejecución requiere conexión para descargar Tesseract y los idiomas. El navegador puede reutilizar después esos recursos desde caché.
