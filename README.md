Instructions to setup:
1) Unzip attached zip file
2) Copy source code and directories to local
3) The BASE_Dir is THProject
4) Call .\thproject\Scripts\activate.bat to activate the venv
5) Run python manage.py runserver
6) On the browser, navigate to http://127.0.0.1:8000/admin/
7) Use the following creds to login:
Username: admin, password: thproject
8) You will see 3 models there (Categories, Products and Tags) with 5, 20 and 10 entries respectively
9) Navigate to http://127.0.0.1:8000/thproject/ to see the list of products
10) Table search by product description and filtering by category and tag is now supported. (I'm using Django Filters for this functionality)

Assumptions
1) One assumption I made in the modeling is that a product can only belong within a single category i.e., tshirt goes under Clothing. If there were to be sub categories such as Men's, Women's under clothing this is not necessarily true. So I'm assuming there are no subcategories here. 
