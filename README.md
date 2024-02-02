Firebase configuration is a little tricky for beginners. So this repo guides configuring Firebase properly for Flutter easily without issues. 
With your help, we can grow this repo for further firebase issues.

1. Download and Install Node Js application from https://nodejs.org/en
2. After Installation run this command on Node Js
   
   ``` npm install -g firebase-tools ```

3. After this the Firebase CLI tools are installed. Now run this command:

   ``` firebase login ```

4. And check if you are logged in by seeing your list of projects on Firebase as this:

   ``` firebase projects:list ```

5. Now enable it for flutter using this command:

   ``` dart pub global activate flutterfire_cli ```

6. Now just go to any Flutter project root folder and run this command in the terminal:

   ``` flutterfire configure ```

7. This will ask you to select platform (You may choose Android, IOS, windows etc), and then set up the ```google-services.json``` file in the platform folder and also connect the project to the Firebase backend.


This is the most basic, easy and fastest way to do this. If you have any other issues raise it on this repository. And if you have any updates on this or have solved any issues please contribute.



