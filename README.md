# ExcelToPLCXMLCode
 First, extract the folders from the ZIP file you were given into a workspace.
 Then, add all the files to Eclipse by going to ‘File’ -> ‘import project ’.
 As a third step, in the ‘PLC’ model, use the ‘Generate All’ option in the ‘plc.genmodel’ file to
 automatically produce Java codes.
 Do the same process for the ‘Second Model’.
 Add build path for poi-getExcelDataAdd plc
Next, run the ‘ExcelRead.java’ class in the ‘poi-getexceldata’ project. With this process, you will
 have created your first model. This is located in “inputModel” called Output.plc.
Then, you need to create a new run configuration for the ‘secondModel’, which is the target
 model, and execute it.
 After this step, you will have created a new ‘MainTransformation.secondModel’ model.
Following this model, you need to create a new run configuration on ‘Acceleo’ for the M2T
 transformation. 
After running this newly created run configuration, you can see the PLC XML codes in the
‘inputToPLC3.xml’ file:
This file inputToPLC3.xml can now be imported into CoDeSys.
 
