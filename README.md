# ExcelToPLCXMLCode
1. First, extract the folders from the ZIP file you were given into a workspace.
2. Then, add all the files to Eclipse by going to ‘File’ -> ‘import project ’.
3.As a third step, in the ‘PLC’ model, use the ‘Generate All’ option in the ‘plc.genmodel’ file to
 automatically produce Java codes.
4. Do the same process for the ‘Second Model’.
5. Add build path for poi-getExcelDataAdd plc
6.Next, run the ‘ExcelRead.java’ class in the ‘poi-getexceldata’ project. With this process, you will
 have created your first model. This is located in “inputModel” called Output.plc.
7.Then, you need to create a new run configuration for the ‘secondModel’, which is the target
 model, and execute it.
8. After this step, you will have created a new ‘MainTransformation.secondModel’ model.
9.Following this model, you need to create a new run configuration on ‘Acceleo’ for the M2T
 transformation. 
10.After running this newly created run configuration, you can see the PLC XML codes in the
‘inputToPLC3.xml’ file:
11. This file inputToPLC3.xml can now be imported into CoDeSys.
 
