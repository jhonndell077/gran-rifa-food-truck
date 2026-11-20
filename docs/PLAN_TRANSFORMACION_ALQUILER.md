# Transformación a catálogo de alquiler — auditoría y plan

Estado: preparación en rama aislada; SIN despliegue.

## Fuente pública revisada
https://granrifa.web.app/ (20-11-2026)

## Contenido a retirar de la experiencia pública
- «GRAN RIFA», «RD$2,500 por boleto», «Sé tu propio jefe por 2,500 pesos».
- «Participa», «¿Cómo participar?», «Quiero un boleto», «Quiero hacer un pago».
- Formularios para solicitar boletos, pago y datos personales asociados al sorteo.
- Referencias a ganadores, sorteos, premios y boletos, si existen en componentes adicionales.

## Contenido que se conserva
- Galería de 12 vistas originales (incluye visualización lateral de carrocería blanca simulada).
- Cocina 7,40 × 2,30 m; pasillo 1,015 m; prueba operativa de cinco personas.
- Parrilla 122 × 71,5 cm; plancha 96 × 69 cm; freidora doble 51 × 46 cm; estufa 140 × 56 cm; campana 417,5 × 72 cm.
- Fregadero 71,5 × 50 cm; mesa 163 × 51 cm; ventanilla 202 × 54 cm.
- Plano y descripción de distribución interior.

## Nuevo enfoque editorial
Título: «Food Truck disponible para alquiler en eventos».
Subtítulo: «Una cocina móvil equipada para llevar experiencias gastronómicas a tus celebraciones».
Secciones: Inicio / Galería real / Equipamiento / Distribución / Eventos / Contacto.
Eventos sugeridos: bodas, cumpleaños, ferias gastronómicas, actividades corporativas y celebraciones privadas.
Sin precios, tarifas, boletos ni referencias a rifas.

## Precauciones de implementación
1. Identificar el archivo de entrada real, rutas de assets y configuración de Firebase antes de sustituir componentes.
2. El archivo index.html consultado por el conector devolvió contenido vacío; no se asume que represente el sitio publicado.
3. No reemplazar las imágenes con imágenes genéricas; verificar las 12 rutas y la maqueta en el repositorio/Hosting.
4. No eliminar datos históricos ni colecciones Firebase; desactivar solo interfaces de rifa tras revisar dependencias.
5. Probar galería, accesibilidad, navegación móvil, formulario de contacto y ausencia de precios.
6. No modificar main, no fusionar y no desplegar sin aprobación.

## Pendiente para implementación
Localizar los archivos de frontend y assets originales, confirmar la relación entre el repositorio y el Hosting público, preparar cambios verificables y pruebas.