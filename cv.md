#Alexandr Holubev
===
##Contacts
* **Location:** Minsk, Belarus
* **Email:** holubev@gmail.com
* **GitHub:** wert1999
===

##About Me
I'm 50 years old. I work in a print shop, in the prepress department.
===

##Skills
* Python
* JavaSript(basic)
* Adobe Create Suits
* Corel
* ArtPro+
* Esko Software
===

##Code Examples
```
function importXML(xmlPath)
{
	if (app.documents.length != 0){
        var myDocument = app.documents.item(0);  
         
        //import the entire XML structure in the document.
        var myXMLImportPreferences = myDocument.xmlImportPreferences;
        myXMLImportPreferences.allowTransform = false;
        myXMLImportPreferences.ignoreWhitespace = true;
        myXMLImportPreferences.removeUnmatchedExisting = false;
        myXMLImportPreferences.importStyle = XMLImportStyles.MERGE_IMPORT;
        myXMLImportPreferences.repeatTextElements = true;
        
        var path = new File(xmlPath);
        var file = path.openDlg("Importer XML", "XML:*.xml", false);
        if (file != null) {
            myDocument.importXML(file);                   
        }
	}
}
```
===

##Education
Belarusian National Technical University

Software for computer engineering
===

##Courses:
* **ml-intro-2022Q1** [https://app.rs.school/certificate/gf4kastf]
===

##Languages
* **Russian** - native speaker.
* **English** - A1. I'm ashamed (\*^^*)
