# Respaldo cifrado de proyecto de IA

`respaldo-proyecto-ia-cl` · v2.1.0 · B2B · cualquier sector

> Te llevas tu proyecto entero cifrado, con el guion para rehacerlo y la lista de lo que no cabía. Probado en frío antes de que borres nada.

**Precio:** 49 € · PACK CONTEXTO 89 € con el compilador

## Qué hace

Convierte **el contenido de un Proyecto de Claude —instrucciones, base de conocimiento,
descargas y adjuntos, skills asociadas y el historial de chats del export oficial—** en **un
paquete cifrado AES-256 con archivo maestro `RESTAURAR-TODO.md`, resumen de chats, checksums
SHA-256 y guion de reconstrucción**, para **quien administra el proyecto**, en **30 a 60 minutos
por proyecto de hasta 100 documentos**, una vez recibido el export.

Lo primero, y no es opcional: **Anthropic no soporta migrar datos entre cuentas personales.**
Cita literal del Centro de Ayuda: *"Exported data can't be imported into another personal Claude
account, and we don't support migrating data between personal accounts."* Consecuencia operativa:
**no existe un botón de migración y esta skill no lo inventa.** Lo que produce es un paquete de
reconstrucción **manual**, con el contenido ordenado y el guion para rehacerlo a mano.

## Para quién es

Quien administra un Proyecto de Claude con **contenido que le costaría rehacer**: consultor, despacho, agencia o equipo pequeño con base de conocimiento propia, adjuntos de cliente y meses de conversación. Decide y paga quien administra el proyecto.

**Para quién NO es:** Quien espere una **migración automática entre cuentas**: no existe, Anthropic no la soporta, y esta skill no la inventa. Vender esto como "mover tu cuenta" es vender humo. Tampoco quien necesite un archivo con validez legal o de cumplimiento normativo: esto es un respaldo operativo.

## Qué NO hace

- **No migra nada.** Anthropic no soporta migrar datos entre cuentas personales, y esta skill no
  inventa un botón que no existe: produce un paquete de **reconstrucción manual**.
- **No respalda secretos.** Las credenciales son C3 y **se rotan, no se respaldan**.
- El borrador automático de chats **cita y cuenta, no interpreta**. Sin la lectura humana es un
  índice, y venderlo como resumen es prometer lo que el producto no hace.
- Sin el export oficial no hay historial de chats, y esa capa entera va a `HUECOS.md`. El resto
  del respaldo sí se hace.
- Sin `pyzipper` el paquete se entrega **sin cifrar**, y así se declara. No se disimula.
- No sustituye una política de retención ni un cumplimiento normativo: es un respaldo operativo,
  no un archivo legal.

## Cómo se compra

**Pago único, descarga inmediata:** <https://cabina.gumroad.com/l/respaldo-proyecto-ia-cl>. Si el enlace aún no responde, la tienda está en alta: abre un *issue* en este repositorio con el nombre del producto.

## Licencia

Uso comercial permitido en la actividad del comprador, sin límite de ejecuciones. Prohibida la
redistribución, reventa o publicación. Copyright 2026 Sergio Berriozábal Serrano.
