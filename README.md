# 🛡️ Operación Kali – Primer Escaneo de Red Ético

**Fecha:** 2025 
**Objetivo:** Primer reconocimiento de red en un entorno seguro y controlado  
**Entorno:** Laboratorio casero – red local

---

## 🧪 Escenario Operacional

- **Atacante:** Kali Linux en VirtualBox  
- **Objetivo:** Notebook personal con Linux Mint  
- **Propósito:** Aprender técnicas básicas de reconocimiento de red  
- **Ámbito:** 100% ético, dentro de mi infraestructura

---

## 🔍 Comandos Utilizados

### 1. Descubrimiento de red
```bash
nmap -sn 192.168.1.0/24
Escaneo del host
nmap -A 192.168.1.7
Detección de servicios
nmap -sV 192.168.1.7

