# Hybrid Book Design

This repsoitory contains templates for two hybrid book designs released under a [»Creative Commons CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) International« license. The files can be used as is or addapted to your needs. Commissioned by the Hybrid Publishing Lab at Leuphana University of Lüneburg these designs were created by [Torsten Köchlin](http://www.torstenkoechlin.de/).

##GENERAL DESCRIPTION

The book designs were created for the purposes of scholarly book publishing in the humanities and adjacent disciplines. They are hybid since they provide a strong and coherent visual identity for both fixed/page based layouts traditionally used in print design as well as reflowable layouts employed in HTML and EBooks.

The aesthetics of both designs is quite similar, but they differ in complexity. We provide: 

1. A book design for smaller, less complex publications. The page size for print layouts is 127mm x 178mm.
2. A book design for longer, more complex publications. The page size for print layouts is 156mm x 234mm.

The design makes use of the open font "Open Sans" that can be downloaded for free from [Fontsquirrel](http://www.fontsquirrel.com/fonts/open-sans) and multiple other locations on the internet.

Examples of the book designs in use can be found at: [www.meson-press.com](http://www.meson-press.com).

In addition to the IDML-Files for the two book designs mentioned above this repository contains additional resources that allow for a quick and easy import of manuscripts written in Microsoft Word or Open/Libre Office.

The follwoing manual applies to the import of word files that are based on the template:

01 Word and Open Office Template and Style Guide/Microsoft_Word_Book_Template.dotx

Alternatively the Open Office template can be used for wirting the manuscript. However, you might need to safe the final manuscript as .docx before importing. Please refer to the style guide for further information on how to use the template and setting up the document. 

##Preparing InDesign for Importing Manuscripts into InDesign

Adobe Indesign allows it's users to place files within a document (Menu: File/Place, Mac Shotcut: cmd +D). Usually this is used to insert  image files in a design. However text files can be placed as well. When doing this Indesign offers it's users to define their import preferences. Here is where the magic happens because paragraph and character styles used in the Word file can be mapped onto predefined paragraph and character styles of Indesign. Even though this mapping does not work properly in every instance it's a powerful tool to produce a book based on a word document. Some common error can be removed using Indesign Scripts automating the removal of these import errors.

In order to make use of these capabilities you need to install the Word Import Preferences we created for our book designs as well as the scripts provides. Both were created an tested with Adobe InDesign CS6.

### Installing the Import Preferences
Copy the file "hybrid-book-design-word-import-presets.smp" that is contained in the folder "02 Helpful Indesign Tools" to the folder "Word Import Presets" (in case you use a German language Version the folder is called "Word-Importvorgaben")of Adobe Indesign. You can find the folder in the following locations (If it does not exist, just create it or import a word file and store any preferences. The folder will be created automatically then):

* Mac: Library/Preferences/Adobe Indesign/Version/Language/Word Import Presets
* Win 7/8: Users\UserName\AppData\Roaming\Adobe\Indesign\Version\Language\Word Import Presets
* Win XP: Docs and Setting\UserName\Application Data\Adobe\Indesign\Version\Language\Word Import Presets

### Installing the InDesign Java Scripts
The additional scripts provided in the folder "02 Helpful Indesign Tools" can be copied to the "Scripts/Scripts Panel" subfolder in one of the above mentioned locations. The following scripts are provided

1. By default Adobe Indesign includes the powerful script "FindChangeByList.jsx" that allows users to define lists of automatic Search&Replace queries. Those are deinfed in the file "FindChangeSupport/FindChangeList.txt. We created a set of customized Search&Replace queries for both designs. Just rename one of the Search&Replace textfiles to "FindChangeList.txt" and pace it in the folder "FindChangeSupport/". It is highly recommended to use this script directly after placing the imported text on the page. Please make sure to use the predefined query list for the correct book template. 
2. Change Styles Language 2 American English.jsx - This script changes the language settings of all styles to American English.
3. Change Styles Language 2 German (2006).jsx - This script changes the language settings of all styles to German (Rechtschreibreform 2006).


## Importing your Manuscript into Adobe Indesign 

Once you installed the word import presets you can easily import Microsoft Word documents by choosing "Place" ("Platzieren") in your menu. A general description of how to import Word file into Indesign can be found in the documentation provided by Adobe for the desktop publishing software: [https://helpx.adobe.com/indesign/using/adding-text-frames.html#place_import_text](https://helpx.adobe.com/indesign/using/adding-text-frames.html#place_import_text)

1. You are promted to select the file.
2. After selecting the file please check the box "Show Import Options" before proceeding.
3. On the options screens please use the hybrid-book-design-word-import-presets and click OK.
4. Place the text on the page. 


##Creating you Book Cover

In addition to the InDesign IDML files for the book layout this repository contains cover templated for both book sizes. The design is based upon the idea that book covers do not have to convey the author and title information in the digital realm. Rather they commonly serve as thumbnails. Instead of printing the full title or full author name on the cover the design template is set up for printing including just keywords on the front cover. 

##License
The design templates and the accompanying materials are licensed under [»Creative Commons CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) International«.