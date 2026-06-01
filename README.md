# MXT_FTP
MXT_FTP – FTP Utility Module for Mendix 

Overview 

MXT_FTP is a lightweight and performance-focused FTP utility module built for Mendix applications.  

The module provides reusable Java Actions for handling common FTP operations such as fetching files,  

counting files, renaming files, deleting files, moving files, recursive folder creation, and  

extension-based filtering. 

The module is designed to simplify FTP integration inside Mendix projects while maintaining good  

performance for large directory handling and bulk file processing scenarios. 

 

Features: 

• Fetch files from FTP server 

• Fetch files using extension filters 

• Count files in FTP directory 

• Count files by extension 

• Rename FTP files 

• Delete FTP files 

• Move FTP files between folders 

• Create recursive FTP folders automatically 

• Excel filename extraction support 

• File existence validation 

• Batch processing optimization 

• Streaming-based retrieval logic 

• Passive FTP mode support 

• Mendix FileDocument integration 

 

Dependencies: 

- Mendix 10.24.0 or above 


 
Performance Notes: 

The module uses streaming-based FTP parsing and batch commit handling to reduce memory usage and  

improve runtime efficiency while processing large FTP directories. 

Error Handling 

The module includes runtime validation and exception handling for: 

- invalid login credentials 

- missing files 

- connection failures 

- permission issues 

- invalid paths 

- timeout issues 

 

Security Recommendations 

• Store FTP credentials using Mendix Constants 

• Avoid hardcoding credentials inside microflows 

• Restrict FTP access permissions where possible 

 

Author: Deepak Kannan 

 

 
