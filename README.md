# Install Autopsy and Analyze the Disk File and Folder Configuration

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
<img width="1913" height="964" alt="image" src="https://github.com/user-attachments/assets/5f4d3cfb-0613-4d0f-bbe2-c3ff5da812e2" />
Launch the installed Autopsy software.
<img width="1919" height="992" alt="image" src="https://github.com/user-attachments/assets/2adb4ffd-60f4-4087-8aec-dbc493acbe99" />
User interface of autopsy.
<img width="1919" height="994" alt="image" src="https://github.com/user-attachments/assets/67c1d8dd-f059-493e-8019-3cffe347cd7b" />

### Step 2:
Launch Autopsy and create a new case.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f42c9bfd-c35e-4ba1-b0c5-93cf56a8fb66" />
<img width="1919" height="1000" alt="image" src="https://github.com/user-attachments/assets/32d9201c-84d0-4ff4-ac05-c3faaf3d1b72" />

### Step 3:
Add your disk image or physical drive as the data source.
<img width="1916" height="1077" alt="image" src="https://github.com/user-attachments/assets/b4e43217-a307-4fe7-bf86-f08f0b37d835" />
<img width="1919" height="989" alt="image" src="https://github.com/user-attachments/assets/f3d6f75d-2b95-4a6c-b4e5-adb0eb71a733" />
<img width="1919" height="1066" alt="image" src="https://github.com/user-attachments/assets/4131e417-512d-412f-b233-d1f1307588a3" />

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).
<img width="1475" height="826" alt="image" src="https://github.com/user-attachments/assets/02c86d98-40a4-4474-a6f1-26e5d32eb465" />

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.
<img width="1918" height="1010" alt="image" src="https://github.com/user-attachments/assets/4ab4ca54-37d6-4fdd-9caf-b19af3cd667f" />

### Step 6:
Export or recover files if required for the investigation.
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/33e300d7-8a75-461d-915f-02eb8a7bc4f3" />
HTML Report link : file:///C:/Users/admin/Desktop/Desktop/Digital%20forensics/EXP%2003/Reports/EXP%2003%20HTML%20Report%2009-06-2025-13-45-48/report.html

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
<img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/0b3459ef-4071-48fc-9ef1-f825d8241dde" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
