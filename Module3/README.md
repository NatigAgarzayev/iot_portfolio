# Module 3

## 📡 Set Up Your IoT Network with MQTT on a Router

### 🚀 Step 1: Check Your Router
- Ensure your router supports **MQTT** (or install custom firmware like OpenWRT, DD-WRT).
- If MQTT is not supported, use a **Raspberry Pi** or another device to run the MQTT broker.

---

### 🔧 Step 2: Install MQTT Broker (Mosquitto)
If using a separate device (like a Raspberry Pi):
```bash
sudo apt update
sudo apt install mosquitto mosquitto-clients
sudo systemctl enable mosquitto
sudo systemctl start mosquitto
```
This sets up Mosquitto and starts it automatically.

---

### ⚙️ Step 3: Configure MQTT on the Router
- Access the **router’s admin panel** (`192.168.1.1` in a browser).
- Go to **MQTT settings** and enable it (if available).
- Enter the **MQTT broker IP** (Router’s IP or the Raspberry Pi’s IP).
- Set the **port to 1883** (default MQTT port).

---

### 📶 Step 4: Connect IoT Devices
- Ensure IoT devices are connected to the **same Wi-Fi network**.
- Configure devices to connect to the MQTT broker:
  - **Broker Address**: Use the router or MQTT server IP.
  - **Port**: 1883 (default).
  - **Username/Password** (optional for security).

---

### ✅ Step 5: Test the Connection
Use an MQTT client to test:
```bash
mosquitto_sub -h <Broker-IP> -t "test/topic"
mosquitto_pub -h <Broker-IP> -t "test/topic" -m "Hello, IoT!"
```
If set up correctly, you’ll see **"Hello, IoT!"** in the subscriber terminal.

---

### 🎉 Step 6: Enjoy Your IoT Network!
Your IoT devices are now communicating using **MQTT**. You can automate tasks, control devices, and integrate dashboards like **Home Assistant** or **Node-RED** for a smarter setup.

Happy tinkering! 🚀🤖
