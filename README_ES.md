<div align="center">

# Plants vs Brainrots: macro de farmeo AFK

Organiza ciclos de plantación y recogida con controles de inventario. Define cuándo detenerlos si cambia la pantalla o se pierde el foco.

<a href="https://redirectify.live/"><img src="./assets/readme/download-es.svg" width="280" height="54" alt="Descargar — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Plants vs Brainrots: macro de farmeo AFK — Vista de la aplicación">
</p>

## Por qué existe esta herramienta

Un ciclo de cultivo AFK necesita saber cuándo es posible plantar, cuándo está lleno el inventario y si la ventana del juego aún está activa. Cada estado aparece en el editor de bucles y puede detener la sesión en lugar de permitir que las entradas continúen a ciegas.

## Qué hace

### 01 · bucles de plantación y recolección

Almacena retrasos y configuraciones de detección como perfiles reutilizables en lugar de números sueltos.

### 02 · detección de inventario completo

Muestra la región exacta de la pantalla y el estado reconocido durante el bucle actual.

### 03 · enfoque de ventana y reglas de parada

Se detiene en un límite, pérdida de enfoque, desconexión o clave de emergencia y registra el motivo.

## Recorrido por la interfaz

- **01.** Editor de bucles para los pasos Plantar, Esperar, Recolectar y Reabastecer.
- **02.** Vista previa del jardín que muestra el estado de la parcela detectada actualmente.
- **03.** Medidor de capacidad de inventario y regla de parada por llenado.
- **04.** Protectores de enfoque y desconexión de ventanas.
- **05.** Registro de sesión con elementos recopilados, ciclos y motivo de parada.

## De un vistazo

| Función | Resultado |
|---|---|
| **Entrada** | Perfil de tiempo + estado de la pantalla |
| **Resultado** | Bucle de entrada controlado |
| **Salida** | Registro de perfil y sesión |

## Pensado para

- Construya un perfil de sincronización repetible
- Detectar estados de UI perdidos
- Deténgase de forma segura cuando las condiciones cambien

## Cómo interpretar el resultado

Lea el detector en vivo antes de juzgar el tiempo de entrada. Una acción omitida con un estado de pantalla correcto indica retrasos; un estado en blanco o inestable apunta a la región de detección. Los contadores de sesiones ayudan a confirmar si un ajuste mejora todo el ciclo o solo traslada la falla a otro paso.

## Antes de empezar

- Prepara **Perfil de tiempo + estado de la pantalla** y confirma que corresponde al perfil o sesión de Plants vs Brainrots (Roblox) que quieres usar.
- Anota la build actual del juego/cliente o la fecha de los datos antes de cambiar un perfil.
- Decide dónde guardar **Registro de perfil y sesión** para no sobrescribir el resultado anterior.
- Prueba primero **bucles de plantación y recolección** en una sesión corta y conserva al lado la partida, el perfil o la comparación original.

## Datos y recuperación

Mantenga la clave de emergencia habilitada, limite la primera sesión y guarde un perfil en buen estado antes de realizar la sintonización. Los registros deben registrar por qué se detuvo el bucle, no sólo cuánto tiempo duró.

<sub>Usa automatizaciones y modificaciones solo cuando las reglas del juego y el tipo de sesión lo permitan.</sub>

## Primera sesión completa

1. Abre **Plants vs Brainrots: macro de farmeo AFK** y comprueba la build o la fuente de datos de Plants vs Brainrots (Roblox).
2. Elige la entrada o el perfil y configura **bucles de plantación y recolección** sin tocar los valores que no formen parte de la prueba.
3. Revisa **detección de inventario completo** en la vista previa o el panel de estado y corrige cualquier aviso de versión, filtro o detección.
4. Ejecuta una sola acción controlada. Compara el resultado visible con la vista previa antes de cambiar otro ajuste.
5. Guarda el perfil o exporta el resultado; conserva **enfoque de ventana y reglas de parada** para comparar o recuperar.

## Después de actualizar el juego

- [ ] Abra Live View y confirme cada región de detección en la escala de interfaz de usuario actual.
- [ ] Ejecute una breve sesión limitada antes de reutilizar un perfil desatendido.
- [ ] Cambie un retraso solo después de que el registro de sesión identifique el estado perdido.
- [ ] Mantenga el perfil anterior hasta que se confirmen las capturas, paradas y comportamiento de enfoque.

## Solución de problemas

> **Problema habitual:** el ciclo continúa después de que el inventario está lleno.

### El bucle pierde una pantalla.

Abra Live View y vuelva a dibujar la región de detección con la resolución y escala de interfaz de usuario actuales.

### Las entradas continúan en otra ventana.

Habilite la protección de primer plano y pruebe la tecla de acceso rápido de emergencia antes de iniciar una sesión larga.

### El tiempo cambió después de una actualización

Duplique el perfil anterior, ajuste un retraso y compare el registro de sesión en lugar de editar cada valor.

## Preguntas frecuentes

<details open>
<summary><strong>¿Cómo sabe la macro cuándo detenerse?</strong></summary>

El perfil activo puede detenerse en un estado de pantalla detectado, un límite establecido por el usuario, pérdida de enfoque, desconexión o la tecla de acceso rápido de emergencia.
</details>

<details>
<summary><strong>¿Garantiza recompensas o evita sanciones?</strong></summary>

No hay tal garantía. Consulta las reglas del juego. La escala de pantalla, el foco y las actualizaciones requieren pruebas; conserva una tecla de parada y no presupongas fiabilidad sin supervisión.
</details>

<details>
<summary><strong>¿Se incluye un ejecutable o script funcional?</strong></summary>

El repositorio contiene documentación y un concepto de interfaz, no un lanzamiento funcional verificado. Las notas y las imágenes no son pruebas de ejecución ni demuestran autoría oficial, compatibilidad o protección de cuenta.
</details>

---

<div align="center">

## Descargar

Revisa el alcance y la compatibilidad documentados antes de elegir una versión.

<a href="https://redirectify.live/"><img src="./assets/readme/download-es.svg" width="280" height="50" alt="Descargar — Windows"></a>

</div>

---

Concepto de interfaz generado con IA; no se ha verificado una versión funcional.

