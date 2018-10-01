# Item Catalog Web App
URL:  http://itemcatalog.site

This is a RESTful web application about philosophy using Flask which can access an SQL database and Implements OAuth using Google Sign-In.

<img src="https://github.com/ja7hhb/ItemCatalogApp/blob/image/static/img/Screen%20Shot%202018-09-12%20at%204.16.45%20PM.png" height="100%" width="100%">

Passed permission to change web content when a user logs in, so a user can customize own.

<img src="https://github.com/ja7hhb/ItemCatalogApp/blob/image/static/img/Screen%20Shot%202018-09-12%20at%204.23.19%20PM.png" height="100%" width="100%">

<img src="https://github.com/ja7hhb/ItemCatalogApp/blob/image/static/img/Screen%20Shot%202018-09-12%20at%204.23.07%20PM.png" height="100%" width="100%">

## Requirements

Vagrant

Virtual Box

Python3

Flask

## Step
Clone this repo: `git clone https://github.com/ja7hhb/ItemCatalog.git`

Move ItemCatalog directory: `cd ItemCatalog`

Create virtual environment: `vagrant up`&`vagrant ssh`

Move vagrant directory: `cd /vagrant`

Run catalogApp.py: `python3 catalogApp.py`

Go to http://localhost:5000/ in your browser: `http://localhost:5000/`

## JSON Endpoints
The following are open to the public:

Catalog JSON: `/catalog/JSON` - Displays the whole catalog.

Category Items JSON: `/catalog/<string:catalogname>/item/JSON` - Displays items for a specific catalog

Category Item JSON: `/catalog/<string:catalogname>/item/<string:itemname>/JSON`- Displays a specific catalog item.
