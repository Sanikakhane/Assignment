# Assignment
Modify the docker-compose.yml File
Before running the application, you must update the path to the matrix.txt file in the docker-compose.yml file. This path should point to where the matrix.txt file is located on your machine.

Find this section in the docker-compose.yml file:

yaml
Copy
Edit
volumes:
  - [Path of txt file]:/app/matrix.txt
Update the [Path of txt file] with the absolute path to the matrix.txt file on your local machine. For example, if the matrix.txt file is located in C:/sample/matrix.txt, modify it as follows:

yaml
Copy
Edit
volumes:
  - C:/sample/matrix.txt:/app/matrix.txt
Make sure to use the correct path based on your operating system:

Windows: Use the C:/path/to/your/matrix.txt format.
Linux/macOS: Use the /path/to/your/matrix.txt format.
