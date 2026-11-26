
EX-1 Developing a Simple Webserver

Date:

AIM:

To develop a simple webserver to serve html pages and display the Windows Specifications of your Laptop.

DESIGN STEPS:

Step 1:
HTML content creation.

Step 2:
Design of webserver workflow.

Step 3:
Implementation using Python code.

Step 4:
Import the necessary modules.

Step 5:
Define a custom request handler.

Step 6:
Start an HTTP server on a specific port.

Step 7:
Run the Python script to serve web pages.

Step 8:
Serve the HTML pages.

Step 9:
Start the server script and check for errors.

Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TCP/IP Protocol Suite - 25007799</title>
    <style>
        body {
            font-family: "Times New Roman", Times, serif;
            text-align: center;
            margin-top: 30px;
        }
        h1 {
            margin-bottom: 5px;
        }
        h3 {
            margin-top: 5px;
            font-weight: normal;
        }
        table {
            margin: 20px auto;
            border-collapse: separate;
            border-spacing: 2px;
            border: 1px solid black;
            width: 60%;
        }
        th, td {
            border: 1px solid black;
            padding: 8px 12px;
            text-align: left;
        }
        th {
            text-align: center;
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <h1>List of Protocols in TCP/IP Protocol Suite</h1>
    <h3>Name: HARSANTH V | Register Number: 26018677</h3>

    <table>
        <thead>
            <tr>
                <th>S.NO.</th>
                <th>TCP/IP Layer</th>
                <th>Protocols</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Application Layer</td>
                <td>HTTP, HTTPS, FTP, SMTP, DNS, DHCP, Telnet, SSH</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Transport Layer</td>
                <td>TCP, UDP, SCTP</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Internet Layer</td>
                <td>IP (IPv4, IPv6), ICMP, IGMP, ARP, RARP</td>
            </tr>
            <tr>
                <td>4</td>
                <td>Network Access Layer</td>
                <td>Ethernet, Wi-Fi (IEEE 802.11), PPP, Frame Relay</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
```
OUTPUT:
<img width="1585" height="637" alt="Screenshot 2026-11-26 190946" src="https://github.com/user-attachments/assets/a8574446-0397-497a-9823-ab883dc98c14" />


RESULT:

The program for implementing simple webserver is executed successfully.
