# 🛠️ Uipath-toolkits 🛠️
Welcome to the Uipath-toolkits repository! This repository is designed to make it easier for developers to utilize these sub-processes in their automation tasks.

## 🎯 Purpose 🎯
The purpose of this repository is to provide a collection of reusable UiPath workflows. These workflows are designed to help automate common, often repeated tasks in Excel such as converting column numbers to letters, copying worksheets to another workbook, inserting objects into specified fields, and waiting for file downloads to complete.

## 📚 Contents 📚
All contents are in English for easy integration into your projects. The toolkit includes:

1. Excel Column Number To Letter: 
Converts input numbers to corresponding Excel column names. For example, 1 => A, 3 => C, 28 => AB.

2. Excel Copy Worksheet: 
Takes source Excel path and worksheet name, target Excel path as inputs. It copies the worksheet to the target 3.Excel. If a worksheet with the same name already exists in the target Excel, no action is taken.

3. Excel Insert Object In Specified Field: 
Takes the file path of the object to be inserted, the icon path of the object, the text content of the object, the target Excel path, the worksheet name, and the specified field (e.g., "A1") as inputs. It inserts the object at the specified field in the worksheet.

4. Wait For File Download: 
Takes a file path as input. The process checks whether the file exists every 2 seconds, for a total of 10 seconds. If the file does not exist after this period, an error message is displayed.

## 💬 Discussion 💬
If you have any questions or issues related to UiPath, feel free to discuss them here. We're all here to learn and grow together!