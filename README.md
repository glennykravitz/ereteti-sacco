Ereteti Dairy Sacco — Lab 4: The Site, Served by PHP
Unit: DBT 1305 Web Application Development
Student: Glenn (ID 227601)

What this lab does

My six site pages now run as PHP on my own XAMPP server. The top and bottom of every page each live in one shared file, and the membership form is answered by PHP.

Pages

index.php, about.php, routes.php, contact.php, register.php, deliveries.php

Shared files (includes/)
header.php — the top of every page: head, title, heading and navigation. Each page sets its own $page_title.
footer.php — the notices and footer at the bottom of every page. The year comes from date('Y').
Form handling
register.php sends the form to process-register.php using method="post".
process-register.php shows the member's name, phone number and route name.
If the page is opened directly, it shows "No application".
How to run it
Start Apache in the XAMPP control panel.
Put this folder in htdocs/ereteti-sacco/.
Open http://localhost/ereteti-sacco/index.php in a browser.

Pages must be opened through localhost, not by double-clicking the files.
