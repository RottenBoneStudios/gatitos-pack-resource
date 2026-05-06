# 🐱 GatitosMC — Texture Pack SHA-1 Guide

Guía técnica para obtener el hash `SHA-1` del resource pack oficial de **GatitosMC** en Windows.

Este hash es requerido por Minecraft para validar la integridad del texture pack al descargarse desde el servidor mediante:
- Velocity
- Paper
- Plugins personalizados
- ResourcePack APIs

---

# 📦 ¿Qué es el SHA-1 Hash?

Minecraft utiliza un hash `SHA-1` para verificar que el archivo `.zip` descargado por el cliente no haya sido modificado o corrompido.

Ejemplo de hash válido:

```txt
8f3c2d7b0b6f5a8d4f0f2f4d1a6b9e7c3d2a1b0c
```

---

# 🖥️ Requisitos

- Windows 10 / 11
- PowerShell instalado (incluido por defecto)
- Archivo `.zip` del texture pack

Ejemplo:

```txt
GatitosMC.zip
```

---

# ⚡ Obtener SHA-1 desde CMD

## 1. Abrir CMD

Dirígete a la carpeta donde está el texture pack.

Ejemplo:

```txt
C:\Users\Angel\Desktop\Texture Pack
```

Luego abre CMD en esa ubicación.

---

## 2. Ejecutar el comando

```cmd
powershell Get-FileHash .\GatitosMC.zip -Algorithm SHA1
```

---

# ✅ Resultado esperado

```txt
Algorithm : SHA1
Hash      : 8F3C2D7B0B6F5A8D4F0F2F4D1A6B9E7C3D2A1B0C
Path      : C:\Users\Angel\Desktop\Texture Pack\GatitosMC.zip
```

---

# 🎯 Hash final

El valor importante es únicamente:

```txt
8F3C2D7B0B6F5A8D4F0F2F4D1A6B9E7C3D2A1B0C
```

Ese hash debe colocarse en:
- plugins
- proxies
- configuraciones de resource packs
- APIs de Minecraft

---

# 📋 Ejemplo de implementación

## JSON

```json
{
  "url": "https://cdn.gatitosmc.net/GatitosMC.zip",
  "hash": "8f3c2d7b0b6f5a8d4f0f2f4d1a6b9e7c3d2a1b0c"
}
```

---

# ⚠️ Recomendaciones

- El archivo debe estar comprimido en `.zip`
- Nunca modifiques el `.zip` después de generar el hash
- Si cambias cualquier archivo del texture pack debes generar un nuevo SHA-1
- Minecraft no utiliza SHA-256 ni MD5 para resource packs
- Mantén el nombre del archivo consistente con la URL pública

---

# 🔧 Compatibilidad

Compatible con:
- Minecraft Java Edition
- Velocity
- Paper
- Purpur
- Waterfall
- Plugins de Resource Packs
- Sistemas de distribución CDN

---

# 🐾 GatitosMC

Resource Pack Oficial de GatitosMC Network.
