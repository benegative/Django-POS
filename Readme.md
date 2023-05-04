<h1>POS and Invoice</h1>
<p>Here, the system allows users to either start the billing process or generate invoices for past sales. In order to start billings, the user must enter the customer’s identification number which displays information about customers such as his/her name, photo, number, and total available balance. Under the billing section, the user can simply view all available products and choose any of them to add to the list. While adding the products, the application automatically calculates the total amount and displays them to the users. After all, the user can bill the products and confirm the order. After a successful order, the user can now move towards the invoice section and enter the customer’s identification number in order to generate his/her invoice. The customer’s invoice consists of his/her name, application’s name, customer’s photo, order number, and total bill amount.</p>

<h2>Available Features:</h2>
<li>Admin Panel</li>
<li>Make Billings</li>
<li>Generate Invoice</li>
<li>Customer Management</li>
<li>Product Management</li>

<h2>Instruction</h2>
<li>git clone</li>
<li>After you finish downloading the project, unzip the project file and head over to the project root folder.</li>
<li>You can also create a Virtual Environment and Activate it.</li>
<li>Open your Terminal/Command Prompt on the project’s root folder.</li>
<li>Install the Requirements: pip install -r requirements.txt.</li>
<li>Then, make database migrations: python manage.py makemigrations</li>
python manage.py migrate
<li>And finally, after a successful migration run the application: python manage.py runserver</li>
At last, open up your favorite web browser
<li>Go to URL “http://127.0.0.1/[ PORT_NUMBER ]/“</li>
<li>For the Admin Panel, you have to create one with a superuser.</li>