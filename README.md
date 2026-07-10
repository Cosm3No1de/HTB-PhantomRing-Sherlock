![PhantomRing Banner](PhantomRing!.png) # PhantomRing | Threat Intelligence & Static Analysis Walkthrough [Hack The Box](#) [Nivel](#) [OS](#) [Categoría](#) *Documentación de análisis estático avanzado de un artefacto malicioso tipo ELF.*
--- > [!WARNING] > **Protocolo de Integridad de HTB (OPSEC):** > Este documento contiene spoilers (flags/IoCs) de un escenario activo. Para preservar la integridad del reto y fomentar el aprendizaje, las respuestas directas están encapsuladas en bloques desplegables. Úsalo como referencia metodológica. ## 📋 Resumen Ejecutivo **PhantomRing** es un ejercicio de la plataforma Hack The Box (Sherlocks) centrado en la ingeniería inversa y el análisis estático de un backdoor en sistemas Linux. Este *walkthrough* documenta la metodología utilizada para extraer Indicadores de Compromiso (IoCs), identificar la infraestructura de Comando y Control (C2), y comprender las capacidades de evasión de defensas (Anti-Forensics y manipulación del Kernel) del implante. --- ## 🛠️ Herramientas Utilizadas (GNU Binutils) El análisis se realizó de forma puramente estática sin detonar el artefacto, utilizando herramientas estándar de sistemas UNIX: * `sha256sum`: Para la generación de huellas criptográficas. * `strings`: Para la extracción de cadenas ASCII legibles. * `objdump`: Para el desensamblado y análisis del código máquina. * `nm`: Para la enumeración de la tabla de símbolos. * `grep`: Para el filtrado de expresiones regulares. --- ## 🔍 Desglose de Tareas & Metodología












---
Hecho con ☕ y `bash` por **cosmenoide dev** *Happy Hacking!*
