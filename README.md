# Clúster de alta disponibilidad de seis nodos con Windows Server 2022

Proyecto del curso **Sistemas Operativos I** — Universidad Privada de Tacna, Escuela Profesional de Ingeniería de Sistemas (II Unidad, 2026).
Docente: Ing. Renzo Taco Coayla.

**Sitio del proyecto:** https://adriansalasepis.github.io/Clustering---6-Nodos/

## Descripción

Diseño de un clúster de conmutación por error (Windows Server Failover Clustering) de seis nodos para una municipalidad distrital de Tacna. Cada nodo aloja un servicio (archivos, trámite documentario, base de datos, intranet, DHCP e impresión) y otro nodo actúa como respaldo. El diseño incluye controlador de dominio, almacenamiento compartido iSCSI con disco testigo, red segmentada en seis VLAN con pfSense, controles alineados con ISO/IEC 27001:2022 y NIST CSF 2.0, y una política de respaldo 3-2-1.

## Descargas

| Archivo | Formato |
|---|---|
| Documento técnico | [Word](descargas/Documento_Tecnico_Cluster_6_Nodos_II_Unidad.docx) · [PDF](descargas/Documento_Tecnico_Cluster_6_Nodos_II_Unidad.pdf) |
| Presentación | [PowerPoint](descargas/Presentacion_Cluster_6_Nodos_II_Unidad.pptx) · [PDF](descargas/Presentacion_Cluster_6_Nodos_II_Unidad.pdf) |

## Integrantes

| Integrante | Código | Responsabilidad en la validación |
|---|---|---|
| Salas Acuña, Adrian Fabricio | 2021069829 | NODO1 y SRV-DC |
| Hualpa Flores, Cesar Fernando | 2024079783 | NODO2 |
| Jiménez Romero, Josué Andre | 2022074259 | NODO3 |
| Lazaro Cruz, Michael Enrique | 2024016776 | NODO4 |
| Carretero Hualpa, Victor Cesar | 2023078687 | NODO5 y SRV-STORAGE |
| Meneses Inquilla, Edison | 2022075741 | NODO6 y pfSense |
