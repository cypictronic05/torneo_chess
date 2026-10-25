# Gran Torneo Familiar de Ajedrez ♟️

Web React + Vite lista para desplegar gratuitamente en **Vercel**.

## Características
- Inscripción de 2, 4, 8, 16 o 32 participantes con nombre y foto opcional.
- Cruces aleatorios y eliminación directa.
- Selección de ganador en cada partida y pase automático a siguiente ronda.
- Corrección de resultados y recálculo de las rondas posteriores.
- Campeón final con nombre, imagen, corona y confeti animado.
- Guardado automático en `localStorage` del navegador.
- Respaldo descargable en JSON e importación de respaldo.
- Diseño responsive para celulares y pantallas grandes.

## Ejecución local
```bash
npm install
npm run dev
```

## Publicar en Vercel
1. Sube **todo el contenido de esta carpeta** a un repositorio GitHub.
2. Ve a [vercel.com/new](https://vercel.com/new) e importa el repositorio.
3. Vercel detectará **Vite**. Usa comando de build `npm run build` y directorio `dist`.
4. Haz clic en **Deploy**.

## Importante: persistencia y múltiples dispositivos
Los datos se guardan **solo en el navegador del dispositivo que administra el torneo**. Si abres la misma URL en otro celular no verás automáticamente los mismos resultados. Puedes exportar e importar respaldos JSON. Para que todos vean el torneo sincronizado en tiempo real, es necesario integrar una base de datos y autenticación (por ejemplo, Supabase). **Esta versión no incluye sincronización en vivo ni acceso administrativo protegido.**

Las imágenes se comprimen a máximo 480 píxeles y se guardan localmente junto con los datos; usa fotos pequeñas para evitar los límites de almacenamiento del navegador.
