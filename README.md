# .NET-projects

(All the 4 rar files work together to first scrap the websie, then parse it to create xml files, and finally I have provided desktop and web applications todisplay the meaningful data in a sorted way. Description of each file is gven as follows:)


DESCRIPTION OF WEB SCRAPPING.rar:
It consists a C-sharp Console Application which whenever executed will download a Web Page (for a given link) into
the folder specified. The application will take the URL as input as well as the directory to store the file.
Sample Input: C:\> myQuestion1.exe https://www.psx.com.pk/market-summary D:\Assignment1
Param 1: Your Executable File
Param 2: URL
Param 3: Output Folder
Sample Output:  will contain a file named Summary17Sept22.html

DESCRIPTION OF "Parsing html and creating .xml":
Csharp console app to read data generated from web parsing and based on the folder provided in the app.config,
generate folders against each Category. Once the folders are generated, save the scripts which belongs to
that category as an xml file. If the application is re-executed after few minutes, the same procedure will be
repeated but previously generated files will persist.

DESCRIPTION OF "DESKTOP APP":
It is a Windows Form Application which will read .xml files data generated from parsing html as an input. The
application would have the following functionalities:
• User can see a list of All Scripts and Current Price
• User has a dropdown to Filter by Category and see current prices of all scripts which belong to
that category.
• User can click on refresh to reload the data

DESCRIPTION OF "WEB APP":
An ASP.NET web page which will read .xml files data generated from parsing html as an input. The
application would have the following functionalities:
• User can see a list of All Scripts and Current Price
• User has a dropdown to Filter by Category and see current prices of all scripts which belong to
that category.
• User can click on refresh to reload the data
