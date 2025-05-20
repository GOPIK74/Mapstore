
**"Installation and Configuration Guide for MapStore and GeoServer Using Apache Tomcat (v9)"**

---

### 📄 **Preparation/Understanding Document**

This document outlines the prerequisites, installation steps, and configuration procedures for setting up MapStore and GeoServer using Apache Tomcat 9 on a local system.

---

####  **1. Prerequisites**

* Basic understanding of Java web applications.
* Administrator privileges on the local machine.
* Internet access to download dependencies.


####  **2. Required Components**

| Component              | Description                                | Link                                                   |
| ---------------------- | ------------------------------------------ | ------------------------------------------------------ |
| **Apache Tomcat (v9)** | Java-based web server to host `.war` files | [https://tomcat.apache.org](https://tomcat.apache.org) |
| **MapStore**           | Web-based geospatial viewer                | \[Download WAR file from MapStore website]             |
| **GeoServer**          | Web map server for spatial data            | \[Download WAR file from GeoServer website]            |



####  **3. Environment Setup**

1. **Download and Install Tomcat 9**

   * Visit the official Tomcat website and download version 9.
   * Follow the setup process.
   * During setup:

     * Set a **connector port** (e.g., `8080`).
     * Create a **username** and **password** for access.

2. **Access Installation Directory**

   * Navigate to:

     ```
     C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps
     ```

3. **Deploy WAR Files**

   * Copy `mapstore.war` and `geoserver.war` to the `webapps` directory.
   * Tomcat will auto-deploy the applications.

4. **Start Tomcat Server**

   * Use the **system tray icon** or search “Tomcat” in the Start menu.
   * Start the Tomcat service.

5. **Verify Application Access**

   * Open a browser:

     * Tomcat interface:
       `http://localhost:8080`
     * MapStore:
       `http://localhost:8080/mapstore/`
     * GeoServer:
       `http://localhost:8080/geoserver/`

6. **Authentication**

   * Use the **username/password** created during the Tomcat setup to log into MapStore and GeoServer.

---

### 🧾 **README File Format**

Below is a suitable README format for including in your repository or documentation folder:

---

```markdown
# MapStore and GeoServer Installation Guide using Apache Tomcat 9

##  Prerequisites
- Windows OS (tested)
- Java installed
- Internet connection
- Admin rights

##  Required Software
- [Apache Tomcat v9](https://tomcat.apache.org)
- MapStore WAR file (from official site)
- GeoServer WAR file (from official site)

## 🛠 Setup Steps

### Step 1: Install Tomcat
1. Download Apache Tomcat 9.
2. Install it on your system.
3. Set:
   - Connector Port (e.g., 8080)
   - Admin Username and Password

### Step 2: Deploy MapStore and GeoServer
1. Navigate to:
```

C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps

```
2. Copy:
- `mapstore.war`
- `geoserver.war`
3. Paste them into the `webapps` folder.

### Step 3: Start Tomcat Server
- Use system tray icon or search "Tomcat".
- Start the service.

### Step 4: Access Applications
- Tomcat: `http://localhost:8080`
- MapStore: `http://localhost:8080/mapstore/`
- GeoServer: `http://localhost:8080/geoserver/`

### Step 5: Login
- Use credentials created during Tomcat installation.

##  Notes
- Wait a few seconds after deployment for auto-extraction.
- Ensure no port conflict on your system.
```

---
