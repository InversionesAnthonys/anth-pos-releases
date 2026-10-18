# anth-pos-releases

Instaladores para Windows de la caja de Inversiones Anthony's.

- Este repositorio no contiene código. Solo guarda las versiones publicadas (*Releases*): el instalador, su firma (`.sig`) y el `latest.json` que consulta el actualizador de la caja.
- Cada instalador está firmado. La caja solo instala una actualización si su firma coincide con la llave pública que trae consigo, así que un archivo alterado no se instala.
- Las versiones en prueba se publican como *prerelease* y el actualizador no las ofrece. Solo la versión marcada como *latest* llega a las cajas.
