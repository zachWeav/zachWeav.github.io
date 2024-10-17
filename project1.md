[Back to Portfolio](./)

UDP Fileshare
===============

-   **Class: Applied Networking** 
-   **Grade: B+** 
-   **Language(s): C++** 
-   **Source Code Repository:**[Click Here](https://github.com/zachWeav/CSCI332_Applied_Networking/blob/main/UDP_client/client.cpp) 
    (Please [email me](mailto:ZDWeaver@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The UDP Fileshare project is a lightweight client-server application built using C++ and UDP protocol.  This project allows users to transfer text files from a client to a server over a network.
The project is designed to facilitate basic file-sharing capabilities and only supports plain text files (.txt).

**Features:**
-    **Client-Server Model:** The project allows the user to select a text file from the client directory to be sent and saved to a corresponding server directory.
-    **File Transfer via UDP:** The project uses the User Datagram Protocol for file transfer, implementing simplicity and efficiency for sending small text files.
-    **Dynamic File Size Handling:** The project dynamically adjusts to handle varying file sizes by sending the size information to the server before transmitting the actual file contents.
-    **File Storage:** The server receives the file and stores it as 'recieved_file.txt' in the server directory.  

## How to compile and run the program

**NOTE:**  This project must be run in a Linux or other Unix-based environment
**Prerequisites:** Make sure you have a C++ compiler installed

**Step 1:** Open Two Terminal Windows/Tabs
To compile the separate client and server, begin by opening two terminals one for the server and one for the client.

**Step 2:** Compile the Server Program
In one terminal, navigate to the 'UDP_server' directory where the source file is located and compile using g++
```bash
g++ server.cpp -o server
```
This generates the executable 'server'

**Step 3:** Compile the Client Program
In the second terminal, navigate to the 'UDP_client' directory and compile the source file using g++
```bash
g++ client.cpp -o client
```
This generates the executable 'client'

**Step 4:** Run the Program Executables
In each terminal, run both server and client executables respectively
NOTE: The server must be run first to receive files from the client
```bash
./server
./client
``` 
## UI Design

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Lorem ipsum dolor sit amet (see Fig 1), consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat (see Fig 2). Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum (see Fig 3).

![screenshot](images/dummy_thumbnail.jpg)  
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
