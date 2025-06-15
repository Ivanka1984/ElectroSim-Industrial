# ElectroSim-Industrial
Máquina virtual educativa que simula los sistemas usados por una empresa eléctrica: control de consumo, monitoreo industrial y ciberseguridad básica.
# ElectroSim Industrial ⚙️⚡

**ElectroSim Industrial** es una máquina virtual educativa diseñada para simular cómo funciona una empresa eléctrica moderna en términos de monitoreo, gestión de consumo, automatización y seguridad de infraestructuras críticas.

Este entorno está pensado para estudiantes, docentes y profesionales que deseen explorar cómo se integran tecnologías como PLCs, bases de datos, protocolos de comunicación, dashboards y ciberseguridad básica en una red eléctrica simulada.

---

## 🧩 Componentes principales

| Componente         | Descripción                                                             |
|--------------------|--------------------------------------------------------------------------|
| **OpenPLC**         | Simulación de lógica de control industrial (PLCs)                       |
| **Node-RED**        | Flujos automatizados para datos de sensores simulados                   |
| **InfluxDB**        | Almacenamiento de series temporales (consumo eléctrico simulado)        |
| **Grafana**         | Visualización de datos en dashboards dinámicos                          |
| **Mosquitto (MQTT)**| Comunicación IoT entre sensores/medidores y backend                     |
| **MariaDB**         | Gestión de datos de clientes, contratos o registros                     |
| **Suricata**        | Monitorización básica de red (IDS)                                      |
| **UFW + Fail2Ban**  | Seguridad de red y protección ante accesos no autorizados               |

---

## 🚀 Cómo usar

1. Clona este repositorio o descarga el script principal:
   - [`electrosim-industrial.sh`](./electrosim-industrial.sh)

2. Ejecuta el script en una máquina Ubuntu Server 22.04 limpia:
   ```bash
   chmod +x electrosim-industrial.sh
   ./electrosim-industrial.sh
