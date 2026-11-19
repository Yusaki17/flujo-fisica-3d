# FLUJO 3D

Laboratorio educativo de electricidad y magnetismo, con tema oscuro, cámara orbital y demostraciones guiadas.

## Ejecutar

Descarga `index.html` y ábrelo directamente en un navegador. Puedes editarlo en Visual Studio Code. No requiere servidor, paquetes ni conexión a Internet.

## Cuatro unidades

- **Cargas:** fuentes arrastrables, campo y potencial, superposición y partículas de prueba.
- **Capacitores:** geometría, dieléctrico, carga y descarga RC, aislamiento y conservación de Q.
- **Corriente:** batería ideal, resistor óhmico, interruptor, deriva electrónica y potencia.
- **Magnetismo:** protón, electrón o alfa, fuerza de Lorentz, órbitas y hélices.

## Controles

Arrastra el fondo para girar la cámara y usa la rueda para acercar. En Cargas, arrastra una esfera para cambiar su posición. `Iniciar demostración` reproduce una secuencia explicada. Espacio pausa, R reinicia y Esc cierra la teoría y detiene la demostración.

## Documentación

- [Informe técnico (PDF, 7 páginas)](docs/FLUJO_3D_Informe_Tecnico.pdf)
- [Manual de usuario (PDF, 6 páginas)](docs/FLUJO_3D_Manual_Usuario.pdf)

## Modelos y límites

Los cálculos utilizan unidades SI. La geometría 3D se proyecta en un Canvas 2D con un motor propio; no usa WebGL ni bibliotecas externas. Escala y tiempo se adaptan en algunas escenas. La integración de partículas eléctricas es aproximada. No sustituye una medición experimental. Consulta el informe para conocer modelos y limitaciones.

Repositorio privado. El código no está publicado como una web en GitHub Pages.
