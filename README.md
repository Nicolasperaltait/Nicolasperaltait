<h1 align="center">Hola, soy Nicolas Peralta</h1>
<h3 align="center">Infrastructure & Security Operations · SecOps · Linux · SIEM / Wazuh</h3>

<p align="center">
  <img src="https://img.shields.io/badge/SecOps-B91C1C?style=for-the-badge&logo=wazuh&logoColor=white" />
  <img src="https://img.shields.io/badge/Infrastructure-1F2937?style=for-the-badge&logo=proxmox&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=FCC624" />
  <img src="https://img.shields.io/badge/Observability-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Zero_Trust-242424?style=for-the-badge&logo=tailscale&logoColor=white" />
  <img src="https://img.shields.io/badge/Backup_%26_DR-0F766E?style=for-the-badge" />
</p>

<p align="center"><b>Opero una infraestructura productiva propia, 24/7, con criterio de empresa:<br/>segmentada, monitoreada, respaldada y sin un solo puerto abierto a internet.</b></p>

---

## Lo que opero hoy

No es un laboratorio de prueba. Es **infraestructura productiva**: chica en escala, completa en piezas, y de ella dependen todos los dias el DNS, los backups, la seguridad y aplicaciones en uso real.

| Indicador | Resultado |
|---|---|
| Puertos entrantes abiertos | **0** |
| Intentos no autorizados frenados por la politica de acceso en un solo incidente | **13.017** |
| Exporters y sondas de disponibilidad monitoreados | **13** y **25**, alertas al telefono |
| Agentes del SIEM activos | **8**, cero desconectados |
| Verificaciones automaticas que mentian, detectadas y corregidas | **7** |
| Recuperacion medida en pruebas de restauracion | **segundos** a **menos de 2 minutos** |

<p align="center">
  <img src="https://raw.githubusercontent.com/Nicolasperaltait/homelab/main/docs/img/homepage-noc.png" width="90%" alt="Tablero de operaciones" />
</p>

**En lo laboral:** operacion de infraestructura y seguridad en entornos con gestion bajo **ISO 27001**.

## Proyectos

| Repo | De que trata |
|---|---|
| **[Homelab Prod](https://github.com/Nicolasperaltait/homelab)** | **La vista completa**: arquitectura, operacion y 8 casos reales |
| [Zero Trust Remote Access](https://github.com/Nicolasperaltait/zero-trust-remote-access) | acceso remoto sin puertos abiertos y agentes de IA con minimo privilegio |
| [Network Segmentation Playbook](https://github.com/Nicolasperaltait/network-segmentation-playbook) | segmentacion, DNS interno y que se filtro, que no y que se previno |
| [Alerts That Matter](https://github.com/Nicolasperaltait/alerts-that-matter) | alertas, SIEM y controles que se verifican por su efecto |
| [Backups That Don't Lie](https://github.com/Nicolasperaltait/backups-that-dont-lie) | backups medidos por su contenido y restauracion probada |
| [Hypervisor as Control Plane](https://github.com/Nicolasperaltait/hypervisor-as-control-plane) | el hipervisor operado como plataforma productiva |
| [SecOps Governance Blueprint](https://github.com/Nicolasperaltait/secops-governance-blueprint) | SOC, SIEM, endurecimiento medido y lo que se decidio no hacer |

Cada repo responde lo mismo: **cual era el problema, por que importaba, que se decidio, que salio mal y como se resolvio.**

<p align="center">
  <img src="https://raw.githubusercontent.com/Nicolasperaltait/homelab/main/docs/img/grafana-salud.png" width="90%" alt="Salud de la infraestructura en Grafana" />
</p>

## Stack

| Area | Herramientas |
|---|---|
| Virtualizacion y sistemas | Proxmox VE, Debian, Ubuntu Server, OpenMediaVault |
| Seguridad y SecOps | Wazuh (SIEM), auditd, firewall por host, minimo privilegio, hardening |
| Red y acceso | segmentacion por zonas, Tailscale con tailnet lock, Pi-hole, Nginx Proxy Manager |
| Observabilidad | Prometheus, Grafana, Node Exporter, cAdvisor, blackbox, alertas por Telegram |
| Contenedores | Docker, Portainer |
| Codigo y automatizacion | Forgejo con CI, Bash, PowerShell, Python, agentes de IA con acceso acotado |
| Backup y continuidad | backups por dominio, copia cifrada externa, pruebas de restauracion con RTO y RPO |

## Como trabajo

1. **Entender el problema real** antes de tocar nada.
2. **Cambios con plan y rollback**, y evidencia de que funcionaron.
3. **Probar lo que tiene que fallar**, no solo lo que tiene que andar.
4. **Documentar** para no depender de la memoria de nadie.
5. **Contar lo que salio mal.** Los errores documentados son la mitad del aprendizaje.

## Contacto

- LinkedIn: [nicolas-peralta6](https://www.linkedin.com/in/nicolas-peralta6/)
- GitHub: [@Nicolasperaltait](https://github.com/Nicolasperaltait)
