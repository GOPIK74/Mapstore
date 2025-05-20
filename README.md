
**"Installation and Configuration Guide for MapStore and GeoServer Using Apache Tomcat (v9)"**

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
     * 
    ![image](https://github.com/user-attachments/assets/afd7254c-ed59-4e71-abf0-18c080220c9e)

       

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

```
# MapStore and GeoServer Installation Guide using Apache Tomcat 9

##  Required Software
- [Apache Tomcat v9]([https://tomcat.apache.org](https://tomcat.apache.org/download-90.cgi))
- MapStore WAR file ([from official site](https://github.com/geosolutions-it/MapStore2/releases/tag/v2024.02.02))
- GeoServer WAR file ([from official site](https://geoserver.org/release/stable/))

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


##MapStore 

![image](https://github.com/user-attachments/assets/3cebf472-ad1a-453a-a5b7-079632b867f8)

#GeoServer

![image](https://github.com/user-attachments/assets/e9e3aa70-a4a3-4962-a7cc-4fc6cf85d912)

---
