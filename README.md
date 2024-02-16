# GN_Jars
For Windows users, just click on the .bat file to run. If Windows give an error message, open the .bat file in a text editor like Notepad++ or Sublime text editor (not Notepad) and save the file. (You may have to edit the file - hit space bar, then backspace, to enable Save in Notepad++). For Mac copy the command in the .bat file and run it in the directory containing vn020821.jar (single sample projects) or vn_052722.jar (tumor-normal projects).

To add another project, copy the tumor and normal folders into this directory and modify the command in the .bat file to:
java -jar vn020821.jar <folder_name> (for single sample projects)
java -jar vn_052722.jar <tumor_folder_name> (for tumor-normal projects).

Variant_Navigator_Tutorial1_110323.docx and Variant_Navigator_Tutorial2-110323.docx are for 608_chr1_022321.zip (single sample project). Tumor-normal tutorials are in preparation.
