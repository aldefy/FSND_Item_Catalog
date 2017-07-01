# Item Catalog
Item Catalog - Tasked with creating an item catalog using Flask and SQLAlchemy. Language in this project was Python 2.7.

## Getting Started

Clone this repository by typing `git clone https://github.com/aldefy/FSND_Item_Catalog.git`

## Launching Vagrant

Once you have installed [Vagrant](http://vagrantup.com), clone the Full Stack Nanodegree files from [here](https://github.com/udacity/fullstack-nanodegree-vm). Once done, navigate to the folder, then type `vagrant up`. Once ready, type `vagrant ssh` which will connect you to the VM.

## Setting up the database

Once you are connected in the VM, type `cd /vagrant` to change to the current directory. Navigate to `/catalog`. You should see `vagrant@vagrant-ubuntu-trusty-32:/vagrant/catalog$`. This will be where you enter your commands. To set up the database, first type `python database_setup.py`. This is to create the schema. You should see a `itemCatalog.db` file after you type that command. Next, type `python testData.py`. This is to populate the database with some sample data.

## Testing

Once the database is created, you are all ready to test the app! To test, type `python main.py`. Once ready, type `localhost:5000/` in your browser. When you have loaded the website, create an account by pressing the `Login` button, or feel free to browse around.

## MIT License

Copyright (c) 2017 Adit Lal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
