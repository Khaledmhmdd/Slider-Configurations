Ethernet Laptop Network Setup - README

---

## 1. IP Configuration

**Control Panel → Network and Internet → Network and Sharing Center → Change adapter settings → Ethernet → Properties → TCP/IPv4 → Properties**

### Lap 1:

* IP address: 192.168.100.1
* Subnet mask: 255.255.255.0
* Default gateway: 192.168.0.1
* DNS: 8.8.8.8 / 8.8.4.4

### Lap 2:

* IP address: 192.168.100.3
* Subnet mask: 255.255.255.0
* Default gateway: 192.168.0.1
* DNS: 8.8.8.8 / 8.8.4.4

---

## 2. Network Discovery & File Sharing

**Control Panel → Network and Internet → Network and Sharing Center → Change advanced sharing settings**

* Private → Network discovery: On
* Public → Network discovery: On
* All Networks → Network discovery: On
* Password Protected Sharing: Off

---

## 3. Media Streaming Options

**Control Panel → Network and Internet → Network and Sharing Center → Media streaming options → Turn on media streaming**

---

## 4. Required Windows Services

Ensure the following services are set to **Automatic & Running**:

1. Function Discovery Resource Publication
2. Function Discovery Provider Host
3. UPnP Device Host (optional)
4. SSDP Discovery

---

## 5. Folder Sharing

**Folder → Right Click → Properties → Sharing**

1. Share → Everyone: Read/Write → Share
2. Advanced Sharing → Share this folder → Permissions → Full Control

---

## 6. AnyDesk Remote Access

* Password: Admin@1234
* 192.168.100.1 → Podium
* 192.168.100.3 → me

---

## 7. Access Shared Folder from Another Laptop

* Press **Windows+R** → `\\192.168.100.1`
* Access the shared folder and transfer files.
