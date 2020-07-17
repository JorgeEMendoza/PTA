# PTA

In this repository you will find (3) programs written by Jorge E. Mendoza for Property Tax Associates.

noticesorter.jar
	This program takes as an argument, a directory where all the received notices have been scanned into. The program then separates the scanned notices file (in pdf format), separates each notice into it's own pdf file, and sorts it according to the file system structure defined by PTA.

	In order to run this program you will need to open up a command line utility, based on your operating system this might vary, navigate to the location in the file system of the jar file, and execute the command: 
	java -cp noticesorter.jar Main

	Once the program UI is displayed, the argument fields will need to be filled out appropriately in order for the program to operate correctly.

reportmaker.jar
	This program takes as an argument a directory where all the client information is stored, to include a directory named '6. Reports' where a document named '[current year] Notices Report.pdf' will be found. To this document, the program will append any found notices in the corresponding file system structure defined by PTA, based on a list, provided by PTA, in which individual PIDs are listed for each client.

	In order to run this program you will need to open up a command line utility, based on your operating system this might vary, navigate to the location in the file system of the jar file, and execute the command:
	java -cp reportmaker.jar

	Once the program UI is displayed, the argument fields will need to be filled out accordingly, in order for the program to operate correctly.

BoardOrderSorter.jar
	This program takes as an argument a directory where all the client board order documents are stored. The program will then scan each file for a property id, and store each file into its' corresponding folder in the specified folder in the file system.
	
	In order to run this program you will need to open up a command line utility, based on your operating system this might vary, navigate to the location in the file system of the jar file, and execute the command: 
	java -cp BoardOrderSorter.jar Main

	Once the program UI is displayed, the argument fields will need to be filled out appropriately in order for the program to operate correctly.

Additionally, you will find some necessary programs/libraries needed to run the above programs in the Windows 10 environment.

While this repository is listed as public, use of any of its programs is strictly prohibited, unless express written consent is acquired from both, the client (Property Tax Associates) AND the developer (Jorge E. Mendoza, email: jorge.edu.mendoza@gmail.com)

The above programs CANNOT BE GUARANTEED to work under any circumstances other than the ones discussed between the developer and the client.

Proceed with caution, as unlicensed and unapproved use can result in irreversible damage to file systems which have not been configured properly.

The developer takes no responsibilty for such results.

Proceed with caution!



2020-07-17
