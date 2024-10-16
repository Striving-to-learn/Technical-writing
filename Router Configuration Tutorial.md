# Unpacking a Router and Setting It Up

Today, we will unpack the settings and security terms of a Wi-Fi router and go over how to set it up.

## Setting It Up

1. **Power the Router**: Plug in the router to give it power.
2. **Connect to the Modem**: Use an Ethernet cable to connect the router (via the WAN port) to your modem, typically provided by your Internet Service Provider (ISP). The WAN port on our router is labeled in blue and stands for "Wide Area Network" — this is your connection to the internet.
3. **Connect Your Device**: 
   - Plug an Ethernet cable into your device or connect via Wi-Fi.
   - You can find the default Wi-Fi network name and password on the box. **Be sure to change these later**.
4. **Identify the Router's IP Address**: 
   - Look for the default access URL or IP address on the router or its packaging.
   - If there is no label, use your computer’s network tools to find the IP address:
     - Open **Command Prompt** and run the command `ipconfig`.
     - Look for the **Default Gateway** under "Wireless LAN adapter." For example:
       ```
       Default Gateway . . . . . . . . .: 192.168.0.1
       ```
     - The **Default Gateway** is the IP address of your router, which you use to access router settings.
5. **Access Router Settings**:
   - Enter the router's IP address or URL (e.g., `http://tplinkwifi.net`) in a web browser.
   - You will be prompted for a **username** and **password**. These are usually provided in the manual or printed on the router. If not, you can search online for default login credentials (e.g., for TP-Link, it's often `admin` for both username and password). **Make sure to change these later**.

---

## Wi-Fi Router Terms

- **SSID (Service Set Identifier)**: The name of a wireless network.
- **LAN (Local Area Network)**: A network limited to a small geographic area, like a home or office.
- **WAN (Wide Area Network)**: A network covering a broad area, often connecting multiple LANs.
- **DHCP (Dynamic Host Configuration Protocol)**: Automatically assigns IP addresses to devices on a network.
- **IP Address**: A numerical label assigned to each device on a network.
- **Gateway**: A device that connects different networks and acts as an entry/exit point for data traffic.
- **Frequency Band**: The range of radio frequencies used for wireless communication (e.g., 2.4 GHz and 5 GHz).
- **Channel**: A specific frequency within a frequency band used for wireless communication.
- **SSID Broadcast**: The process of a router announcing its presence by broadcasting its SSID.
- **Dual-Band**: A router that operates on both 2.4 GHz and 5 GHz frequency bands.
- **Guest Network**: A separate network for guests to access the internet without access to the main network.
- **Firmware**: Software embedded in the router that controls its functionality.
- **Port Forwarding**: Directing data traffic from one network port to another.

## Security Features

- **WPA/WPA2/WPA3 (Wi-Fi Protected Access)**: Encryption standards for securing wireless networks.
- **WEP (Wired Equivalent Privacy)**: An older encryption protocol, less secure than WPA.
- **AES (Advanced Encryption Standard)**: A widely used encryption algorithm for securing data.
- **Firewall**: Monitors and controls incoming and outgoing network traffic for security.
- **MAC Address Filtering**: Restricts network access based on a device's MAC address.
- **VPN (Virtual Private Network)**: Encrypts internet traffic, enhancing security and privacy.
- **Intrusion Detection System (IDS)**: Monitors network traffic for suspicious activity.
- **WPS (Wi-Fi Protected Setup)**: Simplifies connecting devices to a secure network.
- **Two-Factor Authentication (2FA)**: Adds an extra layer of security by requiring a second verification step, like a prompt on your phone.

---

## Firmware Updates

- **Keep Your Router Updated**: Regularly update your router's firmware to patch security vulnerabilities.
