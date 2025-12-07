RemindMe/
│
├── index.php                # Login Page
├── register.php             # Registration Page
├── dashboard.php            # Dashboard
├── add_document.php         # Add Document Form
├── insert_document.php      # Backend insert logic
├── view_document.php        # View selected document
├── edit_document.php        # Edit document form
├── update_document.php      # Backend update logic
├── delete_document.php      # Delete document
├── documents.php            # All Documents list
├── settings.php             # Settings page
├── logout.php               # Logout script
│
├── config/
│   └── db_connect.php       # Database connection file
│
├── uploads/
│   └── (All uploaded user files stored here)
│
├── assets/
│   ├── css/
│   │   └── style.css        # Main CSS file
│   │
│   ├── js/
│   │   └── script.js        # Validation + interactions
│   │
│   └── img/
│       └── logo.png         # App logo or icons
│
├── includes/
│   ├── header.php           # Top bar layout
│   ├── sidebar.php          # Optional if needed   //not needed
│   └── footer.php           # Footer layout
│
└── README.md                # Project summary





1) Login → index.html

Login UI

Calls login.php for backend

Validation from script.js

2) Registration → register.html

New user signup

Calls register.php

Validation from script.js

3) Dashboard → dashboard.html

Shows all reminders

Buttons: Add, View, Edit, Delete

4) Add New Document → add-document.html

Form to upload document

JS: file validation

PHP: add-document.php

5) View Document Details → view-document.html

Shows all info

Buttons: Edit / Delete

6) Edit Document → edit-document.html

Edit the same form

PHP: edit-document.php

7) Settings → settings.html

Profile

Security

About RemindMe

Logout

8) JS Logic → js/script.js

Contains:

All form validations

File size check

UI interactions