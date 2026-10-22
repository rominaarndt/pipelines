# Pipeline ETL de Ventas: Integración de Datos y Optimización en Parquet

Este proyecto simula un escenario real de ingeniería de datos donde se integran y normalizan registros de transacciones provenientes de un archivo CSV con el catálogo maestro de productos almacenado en un archivo Excel. El flujo de datos asegura la integridad tipológica (utilizando enteros de 64 bits para las llaves), realiza limpieza de nulos y genera un archivo optimizado en formato Parquet.

---

## 🛠️ Requisitos Técnicos y Librerías

Para ejecutar este proyecto correctamente, asegúrate de tener instalado Python 3.8 o superior junto con las siguientes librerías:

```bash
pip install -r requirements.txt
