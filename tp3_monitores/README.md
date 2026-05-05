# 📘 TP - Monitores

## 📌 Descripción

Este trabajo práctico aborda el concepto de **sincronización mediante monitores** en programación concurrente.

Un monitor es una construcción que permite encapsular datos compartidos y garantizar **exclusión mutua automática**, además de proveer mecanismos de sincronización mediante variables de condición.

---

## 🎯 Objetivo

- Comprender el funcionamiento de los monitores.
- Aplicar sincronización entre procesos concurrentes.
- Resolver problemas clásicos de concurrencia.
- Modelar comunicación entre procesos de forma segura.

---

## 🧠 Conceptos trabajados

- Monitores como mecanismo de sincronización  
- Exclusión mutua implícita  
- Variables de condición  
- `wait`, `signal`, `signal_all`  
- Problemas clásicos de concurrencia  
- Coordinación entre múltiples procesos  

---

## ⚠️ Estado del trabajo

Este trabajo práctico se encuentra en desarrollo.

---

## 🔔 Operaciones de sincronización

- `wait(condición)`: bloquea el proceso hasta que la condición sea verdadera  
- `signal(condición)`: despierta a un proceso bloqueado en la condición  
- `signal_all(condición)`: despierta a todos los procesos bloqueados en la condición  