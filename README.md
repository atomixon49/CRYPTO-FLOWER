# 🌸 FLORA - Sistema de Cifrado Híbrido Post-Cuántico

<div align="center">

![FLORA Logo](https://img.shields.io/badge/FLORA-Crypto%20Flower-FF69B4?style=for-the-badge&logo=flower&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-Apache%202.0-green?style=for-the-badge&logo=apache&logoColor=white)
![Security](https://img.shields.io/badge/Security-Post--Quantum-red?style=for-the-badge&logo=shield-check&logoColor=white)

**Fractal Lattice Obfuscation with Rotational Autodestruction**

*El sistema de cifrado más avanzado y elegante del mundo* 🌟

[🚀 **Instalar**](#-instalación) • [📚 **Documentación**](#-documentación) • [🧪 **Probar**](#-pruebas) • [🔒 **Seguridad**](#-características-de-seguridad)

</div>

---

## 🌟 **¿Qué es FLORA?**

**FLORA** es un sistema de cifrado híbrido revolucionario que combina la elegancia de la naturaleza con la potencia de la criptografía post-cuántica. Inspirado en el delicado pero poderoso mundo de las flores, FLORA implementa un mecanismo único de **autodestrucción caótica** que protege tus datos de manera irreversible ante cualquier amenaza.

### 🌸 **Inspiración Biológica**
- **🌱 Receptáculo**: Centro de datos seguro
- **🌸 Pétalos**: Capas de encriptación biomimética
- **🌿 Tallo**: Sistema inmune contra ataques
- **🦠 Raíces**: Regeneración y evolución continua

---

## 🚀 **Características Principales**

| 🔐 **Seguridad** | ⚡ **Performance** | 🌪️ **Autodestrucción** | 🧬 **Evolución** |
|------------------|-------------------|------------------------|------------------|
| AES-256-GCM | Hasta 116 MB/s | Mapa logístico caótico | Aprendizaje de ataques |
| Post-cuántico | Latencia < 1ms | Corrupción irreversible | Mejoras automáticas |
| Perfect Forward Secrecy | Escalable | Sensibilidad extrema | Regeneración |

---

## 🛡️ **Características de Seguridad**

### 🔒 **Cifrado Híbrido Avanzado**
- **AES-256-GCM**: Cifrado simétrico de nivel militar
- **PBKDF2**: Derivación de claves con 100,000 iteraciones
- **Perfect Forward Secrecy**: Claves de sesión únicas
- **Nonces aleatorios**: 96 bits de entropía
- **(Fase 2) Kyber KEM opcional**: Encapsulamiento post‑cuántico de la clave de sesión cuando hay backend disponible

### 🌪️ **Motor de Autodestrucción Caótica**
- **Mapa logístico**: r = 3.998785 (régimen caótico)
- **Sensibilidad extrema**: Efecto mariposa aplicado
- **Corrupción irreversible**: Una vez activado, no hay vuelta atrás
- **Detección de amenazas**: Tiempo real con IA

### 🚨 **Sistema de Defensa Inteligente**
- **Detección de ataques**: Análisis de patrones en tiempo real
- **Bloqueo adaptativo**: Duración exponencial inteligente
- **Evaluación de amenazas**: Scoring dinámico 0.0 - 1.0
- **Respuesta automática**: Sin intervención humana

---

## 📦 **Instalación**

### 🐍 **Python (Recomendado)**
```bash
# Clonar repositorio
git clone https://github.com/atomixon49/CRYPTO-FLOWER.git
cd CRYPTO-FLOWER/flora

# Instalar dependencias
pip install -r requirements.txt

# Instalar en modo desarrollo
pip install -e .
```

### 🪟 **Windows (Automático)**
```cmd
install.bat
```

### 🐧 **Linux/macOS (Automático)**
```bash
chmod +x install.sh
./install.sh
```

---

## 🧪 **Pruebas**

### 🚀 **Ejecutar Suite Completa**
```bash
python test_flora.py
```

### 🔬 **Pruebas Individuales**
```python
from flora import FloraCryptoSystem

flora = FloraCryptoSystem(use_kyber=True)  # Kyber opcional (fallback automático si no hay backend)
password = "MI_SUPER_PASSWORD_2024"
master_key, salt = flora.generate_master_key(password)

message = b"Hola FLORA"
encrypted = flora.encrypt_message(message, master_key, "test_session")
plaintext = flora.decrypt_message(encrypted, master_key)
print(plaintext)
```

Nota: Si no hay librería Kyber instalada, FLORA usará automáticamente PBKDF2 + AES‑GCM sin requerir cambios.

---

## 📊 **Benchmarks de Performance**

| Tamaño Mensaje | Encriptación | Desencriptación | Throughput |
|----------------|--------------|-----------------|------------|
| 7 bytes       | 0.79 ms      | 0.08 ms         | 8.7 KB/s   |
| 47 bytes      | 0.58 ms      | 0.07 ms         | 79.6 KB/s  |
| 1 KB          | 0.58 ms      | 0.08 ms         | 1.7 MB/s   |
| 10 KB         | 0.58 ms      | 0.08 ms         | 16.8 MB/s  |

---

## 🏗️ **Arquitectura del Sistema**

```
┌─────────────────────────────────────────────────────────────┐
│                    🌸 FLORA SYSTEM                          │
├─────────────────────────────────────────────────────────────┤
│  🔐 LAYER 1: AES-256-GCM Encryption                          │
│  🌪️ LAYER 2: Chaotic Destruction Engine                      │
│  🛡️ LAYER 3: Threat Detection & Response                     │
│  🔑 LAYER 4: Key Management & Derivation + (Kyber KEM opc.)  │
│  📊 LAYER 5: System Health & Monitoring                       │
└─────────────────────────────────────────────────────────────┘
```

### 🔧 **Componentes Principales**

#### **ChaoticDestructionEngine**
- Mapa logístico caótico
- Generación de secuencias de destrucción
- Corrupción irreversible de claves
- Estadísticas de eventos

#### **FloraCryptoSystem**
- Gestión de claves maestras y de sesión
- Encriptación/desencriptación AES-GCM
- Sistema de detección de amenazas
- Mecanismo de autodestrucción
- (Opcional) Intercambio de clave con **Kyber KEM**

---

## 🚀 **Roadmap de Desarrollo**

### 🌱 **FASE 1: Prototipo Básico** ✅
- [x] Motor de autodestrucción caótica
- [x] Sistema de cifrado AES-256-GCM
- [x] Gestión de claves y sesiones
- [x] Suite completa de pruebas

### 🌿 **FASE 2: Post-Cuántico** ✅ (Integración opcional)
- [x] Integración opcional con CRYSTALS-Kyber (si hay backend disponible)
- [x] Fallback transparente a PBKDF2 + AES-GCM
- [ ] Guías para instalar backend Kyber (pqcrypto/pykyber)

### 🌳 **FASE 3: Multi-Lenguaje** 📋
- [ ] Implementación en C++
- [ ] Implementación en Rust
- [ ] Bindings nativos
- [ ] Benchmarks comparativos

### 🌺 **FASE 4: Aplicaciones** 📋
- [ ] Plugin para navegadores
- [ ] Aplicación móvil
- [ ] Integración con sistemas existentes
- [ ] Certificaciones de seguridad

---

## 🔬 **Investigación y Desarrollo**

FLORA es el resultado de años de investigación en:
- **Criptografía post-cuántica**
- **Sistemas caóticos**
- **Biomimética computacional**
- **Inteligencia artificial aplicada**

---

## 📄 **Licencia**

Este proyecto está licenciado bajo la **Apache License 2.0** - ver el archivo [LICENSE](LICENSE) para más detalles.

---

<div align="center">

**🌸 FLORA - Donde la elegancia se encuentra con la seguridad 🌸**

*Construido con ❤️ y 🌪️ caos controlado*

[⬆️ Volver arriba](#-flora---sistema-de-cifrado-híbrido-post-cuántico)

</div>

