# JavaSQLiteDatabase
A SQLite Database for Android devices

Extract the file and Open the project with Android Studio to edit files

In android, we have different storage options such as shared preferences, internal storage, external storage, SQLite storage, etc. to store and retrieve the application data based on our requirements.

 

In previous chapters, we learned how to use shared preferences, internal storage, external storage and now we will see how to use the SQLite Database option to store structured data in a private database.

 

SQLite is an open-source lightweight relational database management system (RDBMS) to perform database operations, such as storing, updating, retrieving data from the database. To know more about SQLite, check this SQLite Tutorial with Examples.

 

Generally, in our android applications Shared Preferences, Internal Storage and External Storage options are useful to store and maintain a small amount of data. In case, if we want to deal with large amounts of data, then SQLite database is the preferable option to store and maintain the data in a structured format.

 

By default, Android comes with built-in SQLite Database support so we don’t need to do any configurations.

 

Just like we save the files on the device’s internal storage, Android stores our database in a private disk space that’s associated with our application and the data is secure, because by default this area is not accessible to other applications.

 

The package android.database.sqlite contains all the required APIs to use an SQLite database in our android applications.

 

Now we will see how to create a database and required tables in SQLite and perform CRUD (insert, update, delete and select) operations in android applications.
