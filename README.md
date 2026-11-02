# Install Autopsy and Analyze the Disk File and Folder Configuration
### NAME - M.GAJALAKSHMI 
### REGNO - 212224100016
## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/15349b76-3b54-49b8-ab4c-8ed98c00d9f0" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/4371b019-6af8-485a-bf48-e3b5623f80bb" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/bf84b3fa-a6fc-4063-a114-57ddd4b110f7" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/4160e907-cb00-4b9b-86c3-9ccfbdc40c3e" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/b8f4ff8b-4a59-4897-a78c-ad2083e1f661" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/9059f113-b563-40f2-808a-159285a337e5" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/6660c8bb-dccd-44b4-b86c-d4dd04f33d90" />


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
