https://drive.google.com/file/d/1DuqwKD-Zg_Dfbg-vVJuGlboUskwWS0qK/view?usp=drivesdk  = Gen AI Question paper and DATA
https://drive.google.com/drive/folders/1M8CKMT550RnKIi7gEpdZhEl2F2W2acfp  = Gen AI Deta Sets


1) https://repo.anaconda.com/archive/Anaconda3-2025.12-2-Windows-x86_64.exe= Anaconda


2) https://github.com/texstudio-org/texstudio/releases/download/4.9.4/texstudio-4.9.4-win-qt6-signed.exe =Textstudio

3) https://miktex.org/download/ctan/systems/win32/miktex/setup/windows-x64/basic-miktex-25.12-x64.exe= Miktex



4) Extract data from the uploaded PDF and organize it into a structured Excel sheet.
Instructions:
* Consider every **2 consecutive pages as one student's complete record**.
  * Pages 1–2 = Student 1
  * Pages 3–4 = Student 2
  * Continue the same pattern throughout the PDF.
For each student, extract the informat as per the excel sheet provided & fill the data accurately/
Rules for pdf:
* Combine information from both pages into one single row per student.
* Do not create separate rows for each page.
* Maintain original spelling exactly as in the PDF.
* Keep empty cells blank if data is missing.
* Avoid duplicate entries.
* Preserve numeric values correctly without changing formats.
* If tables are present, extract them accurately.
* Ignore decorative text, headers, footers, page numbers, and watermarks unless they contain student information.
* Maintain the same student order as in the PDF.
Output format:
* Create a clean Excel (.xlsx) sheet.
* One row = one student.
* One column = one field.
* Auto-adjust column widths for readability.
Additionally:
* Add a “Student_ID” serial number column starting from 1.
* If uncertain about any extracted value, keep the closest readable text instead of guessing.
* Ensure proper alignment and formatting in the Excel file.


5)  
Mongodb installation



sudo apt-get install gnupg curl
curl -fsSL https://pgp.mongodb.com/server-8.0.asc | \
   sudo gpg -o /usr/share/keyrings/mongodb-server-8.0.gpg \
   --dearmor



echo "deb [ arch=amd64,arm64 signed-by=/usr/share/keyrings/mongodb-server-8.0.gpg ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/8.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-8.0.list




sudo apt-get update
sudo apt-get install -y mongodb-org


sudo systemctl start mongod
sudo systemctl status mongod



6) delete files in  texstudio  = del *.tex                        OR del /s *.tex
delete files in  ML  = del *.ipynb                                  OR del /s /q *.ipynb  OR  dir /s *.ipynb



7) rm *.c                                              = All .c files deleted                  
find . -name "*.c" -type f -delete     = All .c files and subfloders deleted


sudo systemctl enable mongod
