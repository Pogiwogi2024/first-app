

## 🚀 Getting Started

Follow the steps below to set up and run the application on your local development environment.


### 📦 Prerequisites

Make sure you have the following installed:

- PHP (8.1 or higher recommended)
- Composer
- Node.js and npm
- MySQL or other supported database
- Git (optional but recommended)


### 🔧 Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Pogiwogi2024/first-app.git
   cd first-app
   ````

2. **Copy Environment File**

   ```bash
   cp .env.example .env
   ```

3. **Install PHP Dependencies**

   ```bash
   composer install
   ```

4. **Install JavaScript Dependencies**

   ```bash
   npm install
   ```

5. **Run Database Migrations and Seeders**

   ```bash
   php artisan migrate --seed
   ```

6. **Generate Application Key**

   ```bash
   php artisan key:generate
   ```

7. **Run the Application (Dev Mode)**

   ```bash
   composer run dev
   ```

---

### ✅ You're all set!

The application should now be running locally. Visit [http://localhost:8000](http://localhost:8000) (or the port defined in your `.env`).
