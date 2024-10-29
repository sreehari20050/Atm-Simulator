<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>
    <h1 align="center">ATM Simulator System</h1>
    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#i">Introduction</a></li>
        <li><a href="#p">Problem Discription</a></li>
        <li><a href="#k">Key Features</a></li>
        <li><a href="#s"></a>SetUp Information</li>
        <li><a href="#d">Demonstration</a></li>
        <li><a href="#contributing">Contributing</a></li>
      <!--   <li><a href="#license">License</a></li> -->
      </ul>
    
<h2 id="i">Introduction</h2>

<p>Capstone project focuses on the development of an ATM simulator using modern web
        technologies, including HTML, CSS, and JavaScript, with Google Firebase as the
        backend database. The primary goal is to build a web-based application that accurately
        replicates the core functionalities of a real-world ATM, enabling users to carry out
        essential banking transactions in a secure and simulated environment.
        The simulator will feature a user-friendly interface designed with HTML and CSS,
        offering a smooth, intuitive experience that mirrors the interface of physical ATMs.
        JavaScript will handle the core transaction logic, such as user authentication, processing
        withdrawals, deposits, balance inquiries, and fund transfers, ensuring a responsive and
        dynamic user experience.</p>

<p> Google Firebase will serve as the database backend, securely managing user account
        information, including login credentials, transaction histories, and account balances.
        Firebase's real-time data synchronization and authentication capabilities provide a
        robust and scalable backend solution, ensuring the seamless handling of multiple user
        accounts and transactions.</p>

<p>In conclusion, this ATM simulator combines the strengths of HTML, CSS, JavaScript,
        and Google Firebase to offer a comprehensive, realistic to understand and practice
        banking transactions in a secure, simulated environment</p>

<h2 id="p">Problem Discription</h2>
 <p>Automated Teller Machines (ATMs) are a crucial part of everyday banking, offering
            convenient access to financial services like balance inquiries, withdrawals, deposits,
            and fund transfers. However, many users, particularly those less familiar with
            technology, struggle to use ATMs efficiently and securely. This lack of familiarity can
            lead to errors, delays, or discomfort when handling transactions.
            Another issue is that most existing ATM simulators tend to focus only on one aspect of
            the system. They either emphasize the design of the user interface or the backend
            processes that manage data and transactions, but rarely both. This leaves users without
            a clear understanding of how these systems work together, missing out on a
            comprehensive experience that shows the complete ATM functionality from start to
            finish.</p>

<p>Additionally, with the increase in digital banking, security has become a critical
            concern. Many people are apprehensive about handling financial transactions online
            due to risks like fraud or data breaches. Simulators often overlook the importance of
            building secure environments, where users can practice these transactions without realworld consequences or exposure to vulnerabilities.
            This project aims to address these problems by creating a full-stack ATM simulator that
            provides a realistic user interface along with secure backend management.</p>
            
<p>The simulator will allow users to practice common banking tasks such as checking account
            balances, making deposits, withdrawals, and transferring funds in a controlled
            environment. By integrating both the front-end and backend components, the project
            gives users a complete experience, demonstrating how the entire ATM system functions,
            from user input to secure data handling.</p>
            <p>Furthermore, the project incorporates security features to ensure safe handling of
            sensitive information. With user authentication and secure data management practices,
            the system provides a reliable platform for simulating real ATM operations without the
            risks associated with real banking.</p>

<h2 id="k">Key Features</h2>

<ul>
  <li><strong>Account Signup:</strong> Seamlessly create new accounts by inputting personal and contact information.</li>
  <li><strong>Comprehensive Details:</strong> Capture additional account details, including religion, category, income, and education.</li>
  <li><strong>Account Information:</strong> Display vital account information, such as type, card number, and PIN.</li>
  <li><strong>Transaction Variety:</strong> Enable various transactions, including deposit, withdrawal, fast cash, and balance inquiries.</li>
  <li><strong>New Section:</strong> Enable new Bills Section various transactions, including TAX, Eclectricity Bill, Water TAX.</li>
  <li><strong>PIN Management:</strong> Facilitate PIN changes for enhanced security.</li>
  <li><strong>Graceful Exit:</strong> Offer a clean exit option for users to leave the application.</li>
</ul>

<h2 id="s">SetUp Information</h2>

<p>To run the ATM Simulator System locally, follow these steps:</p>

<ol>
  <li>Make sure you have the Visual Studio Code installed.</li>
  <li>Make sure you have the proper stable internet connection.</li>
  <li>Clone this repository to your local machine or download it as a ZIP file.</li>
  <li>Navigate to the project directory in your terminal.</li>
  <li>create a firebase account and a project in it</li>
  <li>copy and paste the api part in the code</li>
</ol>

<ol start="6">
  <li>Run the application using the following command:</li>
  <video width="320" height="240" controls>
    <source src="./Assets/ApiSetup.mp4" type="video/mp4">
  </video>
  <li>Run the project using vscode:</li>
</ol>

<h2 id="d">Demonstration</h2>
<h3>Register</h3>
<video width="320" height="240" controls>
    <source src="www.github.com/sreehari20050/Atm-Simulator/Assets/Register.mp4" type="video/mp4">
  </video>
  <h3>Login</h3>
<video width="320" height="240" controls>
    <source src=".//Assets/Login.mp4" type="video/mp4">
  </video>
  <h3>Deposit</h3>
<video width="320" height="240" controls>
    <source src="./Assets/Deposit.mp4" type="video/mp4">
  </video>
  <h3>Withdrawl</h3>
<video width="320" height="240" controls>
    <source src="./Assets/Withdraw.mp4" type="video/mp4">
  </video>
  <h3>Transfer</h3>
<video width="320" height="240" controls>
    <source src="./Assets/Transfer.mp4" type="video/mp4">
  </video>
  <h3>Bill</h3>
<video width="320" height="240" controls>
    <source src="./Assets/Bill.mp4" type="video/mp4">
  </video>
</body>
</html>

