# Personal Expense Tracker

A personal, offline-first Progressive Web App for recording income and expenses, organizing financial movements, and monitoring overall cash flow.

This project was created to solve a real personal need and is currently used and improved through everyday use.

## Features

* Record income and expenses
* Add date, amount, description, wallet and category
* Organize movements by:

  * income or expense type;
  * wallet or account;
  * category;
* Create and customize classes and options
* Search and filter movements
* View total income, expenses and balance
* Visualize cumulative monthly cash-flow trends
* Analyze expenses by category
* Analyze expenses by wallet
* Analyze income by category
* Export data to CSV
* Create and restore complete JSON backups
* Install the app on a smartphone home screen
* Use the app offline after the first load
* No account or login required

## Privacy by Design

The application works without a backend.

* Data is stored exclusively on the user's device.
* Browser storage is handled through IndexedDB.
* The application does not send financial data to external servers.
* No user account or authentication is required.
* Automatic synchronization between devices is not available.
* Clearing browser data may permanently remove stored movements.

Regular JSON backups are strongly recommended.

## Installation

The application can be deployed on GitHub Pages or any static HTTPS hosting service.

To install it on an iPhone:

1. Open the application in Safari.
2. Tap the Share button.
3. Select **Add to Home Screen**.

## Local Development

To properly test the Progressive Web App and service worker, do not open `index.html` directly.

Start a local static server from the project folder:

```bash
python3 -m http.server 8080
```

Then open the following address in your browser:

```text
http://localhost:8080
```

## Project Structure

* `index.html` - application interface, logic and analytics
* `manifest.webmanifest` - Progressive Web App configuration
* `sw.js` - service worker for offline support
* `icons/` - application icons

## Project Status

Functional personal project, publicly available for demonstration and continuous improvement.

The application is developed starting from real-world problems and tested through everyday use.

## Author

**Anna Benamati**

[GitHub profile](https://github.com/AnnaBenamati)

## License

This repository is public for demonstration and knowledge-sharing purposes.

No specific open-source license has been added yet. All rights are reserved unless otherwise stated.
