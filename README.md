Vendor Management System
Description 
The Vendor Management System is a web application developed using Django and Django REST Framework. It facilitates the management of vendor profiles, purchase order tracking, and the calculation of vendor performance metrics such as on-time delivery rate, quality rating average, response time, and fulfillment rate.

Features
1. Vendor Profile Management:
* Create, update, retrieve, and delete vendor profiles.
* Store vendor information including name, contact details, address, and unique vendor code.
2. Purchase Order Tracking:
* Track purchase orders with details like PO number, vendor reference, order date, items, quantity, and status.
* Filter purchase orders by vendor.
3. Vendor Performance Evaluation:
* Calculate performance metrics including on-time delivery rate, quality rating average, response time, and fulfillment rate.
* Historical performance data storage for trend analysis.
* 
Dependencies
* Python 3.12
* Django(latest version )
* Django REST Framework(lastest version)
Installing
1. Clone the repository:
git clone https://github.com/your/repository.git
2. Install dependencies:
pip install -r requirements.txt

Executing program
1. Apply migrations:
python manage.py makemigrations
python manage.py migrate
2. Create a superuser for admin access:
python manage.py createsuperuser
3. Run the development server:
python manage.py runserver
4. Access the application at http://127.0.0.1:8000/ and the admin interface at http://127.0.0.1:8000/admin/. Add details in Vendor and purchase order in the admin.
5. Access vendor details at http://127.0.0.1:8000/api/vendors/ 
6. Access Purchase order at http://127.0.0.1:8000/purchase_orders/

Help
For any common problems or issues, contact to abhishekeg9947@gmail.com

Authors
Abhishek E G
MAIL: abhishekeg9947@gmail.com

Acknowledgements
* Code snippets and reference:Stackoverflow,Chatgpt,w3schools.
