# Smart Cat Litter Box

Welcome to the Smart Cat Litter Box repository!

## Project Description

This project aims to provide an innovative and practical solution for managing data from a smart litter box for cats. The system consists of two main components:

1. **Server**: The server receives data from the smart litter box, processes it, and stores it in a database. It is developed in Node.js and communicates with the litter box through a REST API.

2. **Control Web Page**: The web page provides an intuitive and user-friendly interface for visualizing and managing the data collected by the smart litter box. It utilizes modern web technologies like HTML, CSS, and JavaScript.

## Prerequisites

Before using the web page, ensure that XAMPP is installed on your computer. You can download and install it from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html).

## Setup and Deployment

Follow these steps to start using the web page:

1. Download the **proyecto_arenero.zip** file and extract it to a location of your choice.

2. Place the resulting folder inside the **htdocs** folder of your XAMPP installation. This folder is located in the location where you installed XAMPP on your local disk.

3. Make sure you have Node.js installed on your computer. If not, you can download it from [https://nodejs.org](https://nodejs.org) and install it.

4. Open Visual Studio Code (or any other preferred editor) and open the **servidor_iot** folder you extracted earlier.

5. Open a terminal in Visual Studio Code and execute the following command to start the server:

   ```bash
   node src/indexrest.js
   ```

6. Great! Now you can access the smart litter box web page from your favorite browser using the following URL:

   [http://localhost/proyecto_arenero/index.php](http://localhost/proyecto_arenero/index.php)

## Web Page Features

The control web page of the smart litter box offers various functionalities for efficient interaction with the system:

- Real-time data visualization: See real-time information collected by the litter box, such as your cat's weight and usage frequency.

- Litter box configuration: Adjust certain litter box parameters, like litter level or automatic cleaning frequency, through the web page.

- Data history: Explore the stored data history to analyze your cat's behavior over time.

- Notifications: The system can send notifications to your email or mobile phone to alert you about important events or situations.

## Contributions

We are excited to receive contributions from the community! If you wish to collaborate with the project, feel free to submit pull requests. You can also report issues or suggest improvements in the "Issues" section of the repository.

We hope this project proves helpful and appealing to all cat and technology enthusiasts. Have fun exploring and enhancing the lives of our beloved felines! 🐱🚀
