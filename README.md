- 👋 gginterested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Meghana-1205/Meghana-1205 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html> 

<html> 

      

<head> 

    <title> 

        How to create drag and drop 

        features for images reorder 

        using HTML CSS and jQueryUI? 

    </title> 

      

    <link href =  
"https://code.jquery.com/ui/1.10.4/themes/ui-lightness/jquery-ui.css"

            rel = "stylesheet"> 

      

    <script src =  

"https://code.jquery.com/jquery-1.10.2.js"> 

    </script> 

      

    <script src =  

"https://code.jquery.com/ui/1.10.4/jquery-ui.js"> 

    </script> 

          

    <style> 

  

        /* text align for the body */ 

        body { 

            text-align: center; 

        } 

  

        /* image dimension */ 

        img{ 

            height: 200px; 

            width: 350px; 

        } 

  

        /* imagelistId styling */ 

        #imageListId 

        {  

        margin: 0;  

        padding: 0; 

        list-style-type: none; 

        } 

        #imageListId div 

        {  

            margin: 0 4px 4px 4px; 

            padding: 0.4em;              

            display: inline-block; 

        } 

  

        /* Output order styling */ 

        #outputvalues{ 

        margin: 0 2px 2px 2px; 

        padding: 0.4em;  

        padding-left: 1.5em; 

        width: 250px; 

        border: 2px solid dark-green;  

        background : gray; 

        } 

        .listitemClass  

        { 

            border: 1px solid #006400;  

            width: 350px;      

        } 

        .height{  

            height: 10px; 

        } 

    </style> 

          

    <script> 

        $(function() { 

            $( "#imageListId" ).sortable({ 

            update: function(event, ui) { 

                getIdsOfImages(); 

            }//end update          

            }); 

        }); 
