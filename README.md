Movie Fun Sample
=============

This is a full JEE6 sample.

Building the Application
------------------------

### Maven

Make sure you have [Maven](http://maven.apache.org/ "Maven") installed.
Then, *cd* into the root directory and execute:

	mvn clean package

That will create the *moviefun.war* file within the 'app/target' directory.

Running the Application
-----------------------

To run the application, make sure you have the Stackato client installed and that you are logged in successfully for your desired target environment (e.g. http://api.stackato.local).

Then execute:

	stackato push -n 

Then go on your application url.

That's all. Have fun!
