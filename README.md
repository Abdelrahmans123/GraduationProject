# Data Structure Visualization Tool
## Overview
This Graduation Project is an interactive Data Structure Visualization Tool built using Laravel. It aims to simplify the learning of complex algorithms and data structures by offering a visually intuitive and interactive platform, perfect for students and educators.
## Key Features
- **Interactive Visualizations:** Brings data structures like arrays, stacks, queues, trees, and graphs to life.
- **Dynamic Rendering:** Real-time updates and transitions as users manipulate data.
- **User-Friendly Interface:** Simple, accessible design for learners at all levels.
- **Educational Focus:** Designed to improve understanding through visual engagement.
## Technologies Used
- **Backend:** Laravel PHP Framework
- **Frontend:** HTML, CSS, JavaScript,Blade, Bootstrap
- **Database:** MySQL
- **Visualization:** JavaScript-based libraries (e.g., D3.js)
## Installation
1. Clone the repository
```bash
git clone https://github.com/Abdelrahmans123/GraduationProject.git
```
2. Navigate to the directory
```bash
cd GraduationProject
```
3. Install dependencies
```bash
composer install
```
```bash
npm install
```
4. Set up your .env file. You can copy the .env.example to .env
```bash
copy .env.example .env
```
5. Set up your database connection in the .env file by updating the database settings
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=graduation_project_db
DB_USERNAME=root
DB_PASSWORD=
```
6. Generate the application key
```bash
php artisan key:generate
```
7. Run database migrations to create the necessary tables
```bash
php artisan migrate
```
8. Start the Laravel development server
```bash
php artisan serve
```
This will start the server at http://127.0.0.1:8000.
## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
## License
This project is licensed under the MIT License.
## Support
For support or inquiries, please contact [sabdelrahman110@gmail.com](mailto:sabdelrahman110@gmail.com).
