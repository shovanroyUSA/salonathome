# salonathomes

## Requirements
- npm = 9.5.0
- node = 19.7.0

## Installation Guide
1. **Clone repository:**
```bash
git clone https://github.com/sigmasolutionsbd/salonathomes.git
```
2. **Go to project directory:**
```bash
cd salonathomes
```
3. **Setup .env file:**
```bash
cp .env.example .env
```
4. **Install dependencies:**
```bash
npm install
```
5. **Running the app:**
```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```
**Database Configuration**
- Install MySQL in your local PC.
- Create a database named `salonathomes`.
- Set your local `DB_USERNAME` and `DB_PASSWORD` in the .env file.
- Configure other database settings if necessary.

**Access Panels**
- Access client panel from: http://localhost:3000
- Access admin panel from: http://localhost:3000/admin

**Default Admin Account**
- Email: admin@demo.com
- Password: aaaaaa
