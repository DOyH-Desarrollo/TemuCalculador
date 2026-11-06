# 📦 Calculadora TEMU - Sistema de Cálculo de Cobros

Aplicación web progresiva (PWA) para calcular cobros de pedidos TEMU con conversión automática de moneda, impuestos y fletes.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

## ✨ Características

- 🔄 **Conversión automática** de moneda (USD a CRC)
- 📊 **Cálculo inteligente** del % de recargo/conversión comparando Temu vs Wink
- 💰 **Cálculo de IVA** del 13% sobre el monto base
- 🚚 **Ganancia por flete** configurable
- 📱 **Instalable en Android** como app nativa (PWA)
- 🎨 **Interfaz moderna** con diseño responsive
- 📋 **Copiar al portapapeles** con un clic
- 🎯 **Indicadores visuales** de recargo (verde/naranja/rojo)
- 💾 **Funcionamiento offline** una vez instalada

## 🚀 Cómo usar

### 1. Datos de la Compra (Pedido General)
- **Monto cobrado por Temu**: Ingresa el monto total del pedido (generalmente en USD)
- **Monto cobrado por Wink**: Ingresa el monto en colones que te cobró Wink
- **Tipo de Cambio de Referencia**: Deja en `1` si ambos montos ya están en colones, o ingresa el tipo de cambio del día

El sistema calculará automáticamente:
- Tasa de conversión efectiva
- % de recargo/conversión aplicado

### 2. Datos del Cliente
- **Total de compra de productos del cliente**: Ingresa el monto que compró el cliente
- **Sumar 13% de Impuesto**: Activa/desactiva el cálculo de IVA
- **Ganancia o costo por Flete**: Ingresa tu margen de ganancia o costo de envío

### 3. Total a Cobrar
El sistema mostrará desglosado:
- 💱 Monto Base + Conversión
- 📋 Impuesto (13%)
- 🚚 Ganancia por Flete
- **TOTAL A COBRAR**

## 📱 Instalación en Android

### Método 1: Automático
1. Abre la app en Chrome para Android
2. Espera 3 segundos
3. Toca el banner naranja "📱 ¡Instala esta app!"
4. Confirma la instalación
5. ¡Listo! El ícono aparecerá en tu pantalla de inicio

### Método 2: Manual
1. Abre la app en Chrome para Android
2. Toca el menú (⋮ tres puntos)
3. Selecciona "Agregar a la pantalla principal" o "Instalar aplicación"
4. Confirma

## 🛠️ Tecnologías

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con variables CSS
- **JavaScript (ES6+)** - Lógica de cálculo
- **Progressive Web App (PWA)** - Instalable y offline
- **Service Worker** - Cache para funcionamiento offline
- **Web App Manifest** - Configuración de instalación

## 📁 Estructura del proyecto
