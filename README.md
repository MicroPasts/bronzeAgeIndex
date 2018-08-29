Bronze Age Index app for PyBossa
================================

[![DOI](https://www.zenodo.org/badge/16073715.svg)](https://www.zenodo.org/badge/latestdoi/16073715)


This application has four files:

*  createTasks.py: for creating the application in PyBossa, and fill it with some tasks.
*  config.py.template: for configuring the Flickr API KEY (required!)
*  template.html: the view for every task and deal with the data of the answers.
*  tutorial.html: a simple tutorial for the volunteers.

Testing the application
=======================

You need to install the pybossa-client first (use a virtualenv):

```bash
    $ pip install -r requirements.txt
```
Then, you can follow the next steps:

*  Create an account in PyBossa
*  Copy under your account profile your API-KEY
*  Run python createTasks.py -u http://crowdcrafting.org -k API-KEY
*  Open with your browser the Applications section and choose the FlickrPerson app. This will open the presenter for this demo application.

Documentation
=============

We recommend that you read the section: [Build with PyBossa](http://docs.pybossa.com/en/latest/build_with_pybossa.html) and follow the [step by step tutorial](http://docs.pybossa.com/en/latest/user/tutorial.html).

**NOTE**: This application uses the [pybossa-client](https://pypi.python.org/pypi/pybossa-client) in order to simplify the development of the application and its usage. Check the [documentation](http://pythonhosted.org/pybossa-client/).

Updating template
=================

After making changes to your source code and committing to github do the following:

*  Clone or pull changes from repo to your server and then issue this command:

```bash
    $ python createTasks.py -k APIKEY -s SERVERURL -t 
```

*  Template should update

LICENSE
=======

Please, see the COPYING file.


Acknowledgments
===============
The thumbnail is from the Portable Antiquities Scheme and shows the Near Lewes hoard.  Image licensed as CC BY-SA. 
