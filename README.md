# Mmm OmeTV Uncover

**Mmm OmeTV Uncover** is a JavaScript userscript that detects the remote peer's public IP address via WebRTC and enriches it with geolocation data using the IPGeolocation API. It also captures a snapshot of the remote video stream and presents all information in a modern draggable UI.

> **Disclaimer**
>
> This project displays approximate IP-based geolocation using publicly available network information. The reported location is an estimate and should not be considered the user's exact physical location.

---

## Features

- 🔥 IP-based geolocation
- 🌍 Country, region, and city information
- 📡 ISP detection
- 🕒 Timezone details
- 🖼️ Automatic remote video snapshot
- 🖱️ Draggable interface
- ➖ Minimize and close controls
- ⚡ Lightweight and fast

---

## Requirements

- A modern Chromium-based browser
- An IPGeolocation API key ([ipgeolocation.io](https://ipgeolocation.io/))
- An OmeTV account ([ome.tv](https://ome.tv/))

---

## Setup Guide

### 1. Create an IPGeolocation account

Visit [ipgeolocation.io](https://ipgeolocation.io/) and create a free account.

### 2. Copy your API key

After signing in, open your dashboard and copy your API key.

### 3. Configure the script

Replace:

```js
let apiKey = "";
