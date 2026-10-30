# furexo-datos

Datos públicos que descarga la Box de Furexo (repositorio público a propósito).

- `pesca/index.json` — índice de paquetes que consulta la Box.
- `pesca/pesca-fotos-<versión>/` — fotos de peces para identificar especies, con su `manifest.json`
  (tamaño, SHA-256 y especie de cada foto). La Box baja solo las especies que elige el armador.

Las fotos proceden de Wikimedia Commons con licencias libres (CC0, dominio público, CC BY, CC BY-SA).
El autor, la licencia y el origen de cada una están en `furexo-os/content/pesca/fotos.json` y se muestran
al pie de cada foto en la app. Se generan con `furexo-os/tools/fotos_pesca.py`; no se editan a mano.
