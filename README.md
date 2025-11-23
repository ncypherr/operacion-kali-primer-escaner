# 🛡️ Operación Kali – Reconocimiento de Red (Lab 01)

**Fecha:** 2024  
**Tipo de ejercicio:** Reconocimiento activo y pasivo  
**Entorno:** Laboratorio personal – red local controlada  
**Objetivo principal:** Documentar el primer escaneo de red ético utilizando Kali Linux

---

## 🔧 Configuración del Entorno
- **Equipo atacante:** Kali Linux (VirtualBox, red NAT/Bridge)  
- **Equipo objetivo:** Notebook personal con Linux Mint  
- **Red utilizada:** 192.168.1.0/24  
- **Motivación:** Fortalecer fundamentos de reconocimiento y enumeración antes de avanzar a vulnerabilidades

---

## 🔍 Reconocimiento y Escaneo
Se realizaron tres fases esenciales de reconocimiento con **Nmap**:

### 🔸 Descubrimiento de hosts
`nmap -sn 192.168.1.0/24`

### 🔸 Escaneo detallado del host objetivo
`nmap -A 192.168.1.7`

### 🔸 Enumeración de servicios y versiones
`nmap -sV 192.168.1.7`

Los resultados permitieron identificar servicios activos, puertos abiertos y detalles del sistema, estableciendo la base para futuras fases de análisis.

---

## 📸 Evidencias del Laboratorio
Archivos incluidos:

- `photo_5168239876946725767_y.jpg`
- `photo_5168239876946725768_y.jpg`

Las imágenes muestran el entorno operativo, ejecución del escaneo y la interfaz utilizada durante la práctica.

---

## ⚠️ Declaración Ética
Este laboratorio se realizó **únicamente** dentro de mi infraestructura personal.  
Ningún sistema externo, tercero, corporativo o ajeno fue escaneado o comprometido.  
El propósito de este repositorio es **formación, documentación y desarrollo profesional ético**.

---

## 🚀 Próximas Fases (Roadmap de Aprendizaje)
- Reconocimiento avanzado con herramientas complementarias  
- Escaneo de vulnerabilidades (Lab 02)  
- Introducción a Metasploitable y explotación controlada (Lab 03)  
- Automatización de procesos de recon  
- Reportería profesional estilo OSINT/Red Team  
- Consolidación de portafolio de seguridad ofensiva

---

## 🧭 Propósito de este Repositorio
Este repositorio documenta mi ruta de aprendizaje práctico en ciberseguridad.  
Cada laboratorio refleja experiencia real en entornos controlados, siguiendo estándares éticos y buenas prácticas.  
Mi objetivo es construir un portafolio técnico profesional, transparente y en constante evolución.
