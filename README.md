# Mobile Shopee

Personal project by **Thevin2002**, built on top of an open-source project.

## How to run

1. Install [XAMPP](https://www.apachefriends.org/) (or PHP 8.x with Apache).
2. Copy this folder into `xampp/htdocs/`.
3. Start Apache and open `http://localhost/<folder-name>/`.
4. Create a MySQL database and import `database/shopee.sql` (for example with phpMyAdmin).
5. Set your database password in `database/DBController.php` (it is `CHANGE_ME` in this repo).

The static HTML version is in `HTML Template/` and can be opened directly in a browser.

Tested: all PHP files pass a PHP 8.2 syntax check.

## Credits

Based on **Mobile Shopee e-commerce template (ISC)**. All credit for the original work goes to its authors. The original licence is kept in this repository and still applies to their code.

## Tech stack

PHP, SCSS, HTML, CSS, Node.js / npm, MySQL

## Configuration

Passwords and keys have been replaced with `CHANGE_ME`. Set your own values before running.

The original project's README is in [README.original.md](README.original.md).

