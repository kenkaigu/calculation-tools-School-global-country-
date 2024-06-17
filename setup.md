# Setup

*   **Download project :**

    ```bash
    Download link : 
    ```
* **Docker Setup:**
  *   Start Docker from the Docker Windows UI or use the command line:

      ```bash
      docker-compose up
      ```
* **PHP API Server Setup:**
  1.  Navigate to the server directory:

      ```bash
      cd server-directory
      ```
  2.  Install required packages:

      ```bash
      php composer.phar install
      ```
  3.  Start local server:

      ```bash
      php composer.phar start
      ```
* **Client Application Setup:**
  1.  Navigate to the project root:

      ```bash
      cd project-root
      ```
  2.  Install required packages:

      ```bash
      npm install && bower install
      ```
  3.  Start application server:

      ```bash
      gulp serve
      ```
