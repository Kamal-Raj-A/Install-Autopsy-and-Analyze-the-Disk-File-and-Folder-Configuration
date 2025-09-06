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
<img width="1913" height="964" alt="Screenshot 2025-09-06 133156" src="https://github.com/user-attachments/assets/a7bcfa6f-13eb-4bf5-bdd9-61d124d1b090" />
<img width="1919" height="992" alt="Screenshot 2025-09-06 133307" src="https://github.com/user-attachments/assets/85dc2ed7-eb34-4941-9b59-25c26d32f088" />

### Step 2:
Launch Autopsy and create a new case.
<img width="1919" height="994" alt="Screenshot 2025-09-06 133349" src="https://github.com/user-attachments/assets/cb87591f-1432-451d-b690-55bb2433594b" />
<img width="1919" height="1000" alt="Screenshot 2025-09-06 133643" src="https://github.com/user-attachments/assets/55e48aec-c96a-4960-b6c1-4a9dcd476a86" />


### Step 3:
Add your disk image or physical drive as the data source.
<img width="1919" height="1066" alt="Screenshot 2025-09-06 134340" src="https://github.com/user-attachments/assets/a1031078-d1ec-403e-8931-70c987a4e78c" />



### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).
<img width="1475" height="826" alt="Screenshot 2025-09-06 134429" src="https://github.com/user-attachments/assets/12dfbb72-d79a-40be-9ae0-0adb28073487" />
<img width="1918" height="1010" alt="Screenshot 2025-09-06 134505" src="https://github.com/user-attachments/assets/729b5d5c-d9e1-40b4-b5fa-53c6d99d4505" />

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.
<img width="1919" height="1016" alt="Screenshot 2025-09-06 134538" src="https://github.com/user-attachments/assets/673af7e4-767c-431e-b2b5-32ae04147511" />

### Step 6:
Export or recover files if required for the investigation.
<img width="1919" height="1018" alt="Screenshot 2025-09-06 134740" src="https://github.com/user-attachments/assets/cb3d7b3b-b009-4a2b-8073-4fb215c2dece" />
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
file:///C:/Users/admin/Desktop/Desktop/Digital%20forensics/EXP%2003/Reports/EXP%2003%20HTML%20Report%2009-06-2025-13-45-48/report.html
<img width="1919" height="1018" alt="Screenshot 2025-09-06 134740" src="https://github.com/user-attachments/assets/72537caf-6206-4e14-99f3-80402eb4f411" />


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
