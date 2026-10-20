# Paneles de audiencia

Paneles de exposición para vistas de la causa e informes orales. Cada panel es **un solo archivo HTML**: se abre con doble clic y **funciona sin conexión a internet**, porque no carga nada de afuera (las imágenes van dentro del propio archivo).

El repositorio está publicado con GitHub Pages para poder abrir un panel desde cualquier equipo, con el enlace a la mano. Lleva `robots.txt` y la etiqueta `noindex`, de modo que los buscadores no lo indexan: se llega solo por enlace directo.

> Material de trabajo con piezas de expedientes. Compartir el enlace únicamente con quien deba verlo.

## Paneles

| Ruta | Para |
|---|---|
| `00338/` | Vista de la causa ante una Sala Civil — desnaturalización de contrato |

## Cómo se usa en la audiencia

Doble clic en el archivo `.html`, o el enlace. Con **F** pasa a pantalla completa.

| Tecla | Qué hace |
|---|---|
| `→` `←` | Avanzar y retroceder |
| `Esc` | Índice de todas las diapositivas |
| `N` | **Notas del expositor — son privadas, no proyectarlas** |
| `T` / `R` | Cronómetro: iniciar o pausar / volver a cero |
| `5` | Ruta breve (lo esencial) o ruta completa |
| `D` | Tema claro u oscuro |
| `G` | Enderezar los gráficos 3D |

Los gráficos en tres dimensiones se giran arrastrando con el ratón. En la diapositiva 2, cada punto del índice es un botón que lleva a su parte de la exposición.

## Cómo se edita

Todo el panel vive en ese archivo `.html`. Los datos de los gráficos están al comienzo del `<script>`, en arreglos con nombre (`HITOS`, `ADENDAS`, `METAS`, `FLUJO`, `SALAS`, `AGENDA`): para corregir una cifra o un texto se edita ahí, sin tocar el dibujo.

Cada diapositiva se identifica por su atributo `data-k` y cada gráfico por `data-build`, no por su número: se puede insertar o mover una diapositiva sin romper las notas ni los gráficos.
