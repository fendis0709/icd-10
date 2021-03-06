# Master Data ICD-10

Master Data ICD-10 version from WHO (https://icd.who.int/browse10/2019/en). Data provided in Code Disease, Name of Disease (English), and Name of Disease (Indonesia). You could use this data for building Medical Information System Project.

## How to use?

### SQL Version

1. Clone or download this project
2. Go to your sql management and create new database called `master_icd_x`.
    - If you're using PhpMyAdmin :
      - Make sure enable PhpMyAdmin service
      - Go to 'http://localhost/phpmyadmin' on your web browser
      - Login with your credentials (If exists)
      - Create new database named `master_icd_x`
3. Import file "**master_icd_x.sql**" to your database

### JSON Version

1. Clone or download this project
2. Create your own database
3. Create new table with anything name you want. But, make sure you create these columns:
    - `code`: VARCHAR(255) NOT NULL PRIMARY KEY
    - `name_en`: TEXT NOT NULL
    - `name_id`: TEXT NOT NULL

## How to contribute?

We're open to any contributions. Please create pull request if you want to make this repository better.

### Happy Coding
