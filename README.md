BizCardX-Extracting-Business-Card-Data-with-OCR

PROJECT :

  BizCardX is a user-friendly tool for extracting information from business cards. The tool uses OCR technology to recognize text on business cards and extracts the data into a SQL database after classification using regular expressions. Users can access the extracted information using a GUI built using streamlit. The BizCardX application is a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information. The extracted information would be displayed in a clean and organized manner, and users would be able to easily add it to the database with the click of a button. Further the data stored in database can be easily Read, updated and deleted by user as per the requirement.


  Explanation :
     1. Execute the “BizCardX_main.py” using the streamlit run command.  
     2. A webpage is displayed in browser, the app created has few options where user can upload the respective Business Card
         whose information has to be extracted, stored, modified or deleted if needed.
     3. Once user uploads a business card, the text present in the card is extracted by easyocr library.
     4. On selecting the save the data gets stored in the MySQL Database.
     5. With the help of MODIFY menu the uploaded data’s in SQL Database can be accessed to View and Update Operations.
     6. Further with the help of DELETE menu the uploaded data’s in SQL Database can be deleted.

Libraries used:
  
  --- Pandas 
  
  --- mysql.connector
  
  --- EasyOCR (To extract text from images)
  
  --- Streamlit
