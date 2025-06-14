# **Sarvam SDK Setup & WiFi Connection Guide**

## **Step 1: Connecting to WiFi**
Before proceeding with the SDK setup, connect to the designated WiFi network. You MUST be on the event wifi to access the Sarvam model.
1. Open **WiFi settings** on your device.
2. Locate the network named **"Workshop[number]_5G"**.
3. Enter the provided credentials.
4. Ensure **internet access** is available.


## **Step 2: Installing Sarvam SDK**
Create a virtual environment and install the provided **wheel file** to set up the SDK:
```bash
python -m venv venv
.\venv\Scripts\activate  # On Windows
# On macOS/Linux, use: source venv/bin/activate
pip install imagine_sdk-0.4.2-py3-none-any.whl
```
