# 🌿 Plantas C₃

**Fotosíntesis y fijación del carbono.** Infografía interactiva en un único archivo
HTML, sin recursos externos: se abre haciendo doble clic y funciona sin conexión.

## Qué explica

- **¿Qué es una planta C₃?** Realiza la fotosíntesis mediante el ciclo de Calvin y
  fija el CO₂ formando primero un compuesto de 3 carbonos.
- **¿Cómo funciona?** Cuatro pasos: captura de luz, entrada de CO₂ por los estomas,
  ciclo de Calvin en el cloroplasto y formación de azúcares para crecer.
- **¿Por qué se llaman "C₃"?** Porque el primer producto estable de la fijación del
  CO₂ tiene **3 átomos de carbono**: `CO₂ → 3-PGA → azúcares`.
- **¿Qué las caracteriza?** Funcionan bien con temperaturas moderadas y suficiente
  agua; con mucho calor o sequía bajan su entrada de CO₂ y su eficiencia.
- **Ejemplo de cultivo:** el trigo. También son C₃ el arroz, la soya, el frijol y la papa.
- **Dato curioso:** las plantas C₃ son el tipo de planta fotosintética más común.

## Cómo usarla

Ábrela en cualquier navegador. Se navega deslizando, con la rueda, con las flechas
del teclado (`↑` `↓`, `Inicio`, `Fin`) o con los puntos del índice lateral.

Respeta la preferencia del sistema «reducir movimiento» y se puede imprimir o
exportar a PDF (Ctrl/Cmd + P).

## Detalles técnicos

- Un solo archivo `index.html`, ~73 KB, sin dependencias ni fuentes externas.
- Una sola escena de animación en `<canvas>` con un único bucle `requestAnimationFrame`,
  con los lienzos activados por sección para no dibujar lo que no se ve.
- Accesoibilidad: cada diagrama tiene su `aria-label`, la navegación por teclado
  funciona y el enlace de salto lleva al contenido.
- Los lienzos se desactivan solos en la impresión, y el resultado es legible en PDF.
