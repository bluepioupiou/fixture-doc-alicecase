Fixtures Documentation Alice Case
=========

This project has been done for the sole purpose of beeing a working exemple for the  [Fixture Documentation Bundle](https://github.com/adlarge/fixtures-documentation-bundle).

It demonstrates the use of this bundle with the fixtures manager [Alice Bundle](https://github.com/hautelook/AliceBundle).

# Usage

To use this repository, you have to clone it next to the fixture documentation bundle.

The launch the following commands in order

    make init
    make load
    make start
    
* make init will launch the composer install command and create the database in sqlite
* make load will populate the database with alice fixture bundle
* make start will launch a web server on port 8000

Then go to your [localhost](http://localhst:8000/fixtures/doc) to see the result by yourself

# Modifications

You can edit, add, delete files in src/entity to test some behaviors. Don't forget (or do to see what it does) to add theses entities
in config/packages/fixtures_doc.yaml and to edit yaml files in fixtures folder to change your data.

If you change the structure of the models you'll have to run 'make init' command again

