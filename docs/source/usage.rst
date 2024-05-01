Usage
=====

.. _installation:

Installation
------------

To run the tutor app, first install flutter `here <https://docs.flutter.dev/get-started/install>`_ and download the latest stable release for your operating system. The Flutter SDK comes bundled with the Flutter framework, Dart SDK, and other necessary tools.

Once the download is complete, extract the contents of the zip file to a location on your machine. For example, on macOS or Linux, you can extract it to your home directory or any other preferred location.

To run Flutter commands from the terminal easily, you can add the Flutter bin directory to your system's PATH variable. This step is optional but highly recommended for convenience.

You can verify that flutter has been installed properly by typing

.. code-block:: console

   $ flutter doctor

in a terminal.

Running the project
----------------

If you're using an IDE like Android Studio or Visual Studio Code, you can run your Flutter project directly from the IDE. Look for options like "Run" or "Debug" and select your target device or emulator.

Alternatively in the terminal for the IDE run the following command:

.. code-block:: console

   $ flutter run

and the application should open in the selected browser.

Maintaining the project
-----------------------

All project dependencies are stored in the pubspec.yaml. To add additional dependencies update the pubspec.yaml file and run 

.. code-block:: console

   $ flutter pub get

All code has been made modular, readable and has comments in all places where neccesary to aid future maintenance and collaboration.

Regularly update Flutter and Dart versions to benefit from the latest features, improvements, and bug fixes. Use the Flutter SDK manager 


.. code-block:: console

   $ flutter upgrade

Unit tests have been made to ensure the project is debugged and troubleshooting is made easy and efficient.

Version control has been done using git where we have branches for each individual feature added and have only merged once a feature has been completed and made compatible.

Firebase
------------

Firebase is a powerful platform provided by Google that offers a variety of features for building and managing mobile and web applications. One of the key features of Firebase is its real-time database and cloud storage capabilities, which allow developers to store and sync data across multiple clients in real-time.

Firebase provides a set of Flutter plugins that make it easy to integrate Firebase services into your Flutter app. These plugins offer APIs for accessing Firebase services such as Firestore (a NoSQL cloud database), Realtime Database, Cloud Storage, Authentication, and more.

We are using Firebase's firestore database to store different types of data needed like users, sessions hosted and reviews left.

