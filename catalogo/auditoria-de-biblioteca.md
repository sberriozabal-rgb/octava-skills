# Auditoría de biblioteca

`auditoria-de-biblioteca` · v1.1.0 · CABINA · DJ

> Te digo qué tracks te van a fallar en el próximo bolo, y en qué orden arreglarlos.

**Precio:** 49 € · en CABINA CORE 149 € · en CABINA COMPLETA 249 €

## Qué hace

Convierte **un `collection.xml` exportado de rekordbox** en **un parte de estado con los
hallazgos agrupados por categoría, un índice de salud de 0 a 100 y un plan de reparación
ordenado por riesgo real en cabina**, para **un DJ de club, móvil o residente que prepara un
bolo o migra de equipo**, en **menos de 10 minutos de atención**.

No es un limpiador de bibliotecas. Es el técnico que revisa el material antes de que salgas
de casa y te dice qué se arregla primero, qué puede esperar y qué no vas a poder arreglar a
tiempo. La aportación no es contar defectos —eso lo hace cualquier script— sino traducir
cada cifra a la consecuencia concreta de la noche del sábado, y ordenar el trabajo por
proximidad al bolo en lugar de por volumen.

## Para quién es

DJ de club, móvil o residente con biblioteca de más de ~3.000 tracks acumulada en varios años y al menos un bolo de pago al mes. Decide y paga el propio DJ.

**Para quién NO es:** El DJ que quiere **reparación automática en lote**: eso es Lexicon (199 USD vitalicio) y esta skill no lo hace ni lo promete.

## Qué NO hace

- **Diagnostica, no repara.** Es decisión deliberada: reparar exige escribir en la base de
  datos propietaria (rekordbox `master.db` es SQLite cifrada con SQLCipher4; los `.crate` de
  Serato son binarios documentados solo por ingeniería inversa comunitaria) y hacerlo mal
  rompe playlists, cue points y beatgrids.
- No detecta clave ni BPM que falten: eso exige decodificar el audio. Lo hace el análisis del
  propio software o Mixed In Key.
- No sabe si un MP3 está corrupto. Ve metadatos, no decodifica.
- No transporta My Tags ni playlists inteligentes: el XML de rekordbox no los incluye, está
  documentado por AlphaTheta (<https://rekordbox.com/>), y si el DJ organiza así le falta
  información en el parte.
- Con Serato, Engine o Traktor solo funciona tras convertir a XML o CSV
  (<https://serato.com/>).
- El índice de salud mide higiene de metadatos. No es una nota de calidad musical ni predice
  cómo saldrá la noche.

## Cómo se compra

**Pago único, descarga inmediata:** <https://cabina.gumroad.com/l/auditoria-de-biblioteca>. Si el enlace aún no responde, la tienda está en alta: abre un *issue* en este repositorio con el nombre del producto.

## Licencia

Uso comercial permitido en la actividad del comprador, sin límite de ejecuciones. Prohibida la
redistribución, reventa o publicación. Copyright 2026 Sergio Berriozábal Serrano.
