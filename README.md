# Faro de Ecos 2D

Juego de plataformas 2D hecho en **Unity 6 (6000.3.29f1)** para el módulo *Programación de videojuegos v2* (UVEG).

**Jugar en el navegador:** https://missin03.github.io/faro-de-ecos-2d/

## Cómo se juega
- **Flechas o A/D:** mover a Nara
- **Espacio:** saltar
- **F:** lanzar un destello (elimina a la sombra de niebla)
- **Botón «Abrir compuerta»:** abre la compuerta del faro (Animator + Animation Event)

Recoge los cinco fragmentos de luz (10 puntos cada uno) para recuperar la luz del faro.

## Descargas
- [Proyecto Unity completo (.zip)](descargas/FaroDeEcos2D_Proyecto_Unity.zip): Scripts, Prefabs, Animator Controllers, clips, escenas, UI y audio.
- [Versión para Windows (.zip)](descargas/FaroDeEcos2D_Windows.zip)

## Estructura del proyecto
- `Assets/Scripts`: `Entidad` (clase base abstracta) e `IDaniable`; `Personaje`, `Enemigo`, `Proyectil`, `Interactuable`, `Puerta`, `Coleccionable`, `GestorJuego`, `GestorUI` y `ControladorJugador` (R2).
- `Assets/Prefabs`: Nara, SombraNiebla, Destello, CompuertaFaro, FragmentoLuz, Plataforma, VFX_Destellos.
- `Assets/Animations`: controladores Player, Enemy, Door (con el evento `AlTerminarApertura`), Shard y Luz.
- `Assets/Scenes`: R1_EscenaVacia, R2_Importacion, R3_Faro, Nivel_01.

Los sprites y sonidos son originales, generados por código para este proyecto.

Autor: Emmanuel Missin Garcia Vargas
