# 🚀 SSH Brute-force Detection with Splunk
### (Detección de Fuerza Bruta SSH con Splunk)

## 🧠 Overview / Descripción

**EN**:
This project demonstrates how to detect SSH brute-force attempts using Splunk Enterprise.
It ingests Linux authentication logs (/var/log/auth.log) and provides dashboards and alerts for failed login activity.

**ES**:
Este proyecto demuestra cómo detectar intentos de fuerza bruta SSH utilizando Splunk Enterprise.
Ingiere logs de autenticación de Linux (/var/log/auth.log) y genera dashboards y alertas para actividad de inicios de sesión fallidos.

## 📊 Dashboard / Panel de Monitoreo

**EN** — Includes:

Raw Failed SSH Attempts

Top Attacking IPs

Top Targeted Users

Failed Logins Over Time (timeline)

**ES** — Incluye:

Intentos fallidos de SSH (crudos)

IPs con más intentos

Usuarios más atacados

Inicios de sesión fallidos a lo largo del tiempo (línea temporal)

## 📸 Screenshots / Capturas

🖥️ Dashboard Overview / Vista General del Dashboard
<p align="center"> <img src="./images/dashboard.png" width="600"> </p>

## ⚡ Alerting / Alertas

**EN**:
An alert is triggered when ≥5 failed login attempts occur within 1 minute — simulating a brute-force attack and providing early warning.

**ES**:
Se activa una alerta cuando se detectan 5 o más intentos fallidos en 1 minuto — simulando un ataque de fuerza bruta y entregando una advertencia temprana.

## 🔑 Use Cases / Casos de Uso

**EN**:

SOC / SIEM practice labs

Security monitoring in Linux environments

Learning SPL (Splunk Search Processing Language)

**ES**:

Laboratorios de práctica SOC / SIEM

Monitoreo de seguridad en entornos Linux

Aprender SPL (Search Processing Language de Splunk)

👨‍💻 Developed by / Desarrollado por

Matías Andrés Lagos Barra — Cloud Security & DevSecOps Engineer
