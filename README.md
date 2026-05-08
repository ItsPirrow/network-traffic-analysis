# Network Traffic Analysis Project

## 🛡️ Descripción
Este repositorio contiene análisis detallados de capturas de tráfico de red (archivos .pcap) para identificar comportamientos maliciosos, exfiltración de datos y compromiso de hosts en entornos corporativos.

## 📁 Análisis Realizados

### 1. Infección por NetSupport Manager RAT
- **Escenario:** Identificación de un Troyano de Acceso Remoto (RAT) detectado por alertas de SIEM hacia la IP `45.131.214.85`.
- **Protocolos analizados:** HTTP, TCP, Kerberos, NBNS y SMB.
- **Hallazgos clave:** Identificación del host `DESKTOP-TEYQ2NR` y la cuenta de usuario `brolf` (Becka Rolf) como activos comprometidos.
- **Documento:** [Ver PDF Completo](./analysis-01-netsupport-rat/Análisis-NetSupport-RAT-BeckaRolf.pdf)

### 2. Infección por Lumma Stealer (Infostealer)
* **Escenario:** Detección de actividad de *fingerprinting* y exfiltración hacia el dominio C2 `whitepepper.su`.
* **Protocolos:** HTTP, Kerberos, SMB2, NBNS, TCP.
* **Hallazgos Clave:** Identificación del host `DESKTOP-ES9F3ML` y el usuario `gwyatt` (Gabriel Wyatt).
* **Documento:** [Ver PDF Completo](./analysis-02-lumma-stealer/Análisis-LummaStealer-WIN11OFFICE.pdf)

---

## 🛠️ Herramientas Utilizadas
* **Wireshark:** Análisis profundo de paquetes y filtrado de protocolos.
* **Virustotal & UrlScan:** Análisis de dominios y URLs.
* **AbuseIPDB:** Análisis de IPs.
