# GDSC-flutter-class-1

## Table of Content
- <a href='https://github.com/rahulmokaria/gdsc-flutter-classes/blob/main/README.md#getting-started'>Getting Started</a>
- <a href='https://github.com/rahulmokaria/gdsc-flutter-classes/blob/main/README.md#class-resources'>Class Resources</a>
- <a href='https://github.com/rahulmokaria/gdsc-flutter-classes/blob/main/README.md#additional-resources'>Additional Resources</a>

## Getting Started

If you're new to Flutter, the first thing you should do is visit the <a href='https://docs.flutter.dev/get-started/install'>official Flutter website</a> and follow the instructions to install Flutter on your machine. You'll also need an IDE, such as Android Studio or Visual Studio Code, to develop Flutter applications.

[Video Link:](https://www.youtube.com/watch?v=ozyzWJxHLwY)

After installing flutter if you want to use VS Code then also install flutter extension in VS Code.

Once you have Flutter installed and your IDE set up, you're ready to start learning!

## Class Resources

Class ppt: [Flutter_Introduction.pptx](https://github.com/rahulmokaria/gdsc-flutter-classes/files/11094063/Flutter_Introduction.pptx)

### Creating a Flutter project
There are many ways in which we can create a project, out of which some are listed below:

#### Using Terminal
- Firstly, we will move into the directory in which we want to create a project, for eg. Documents.
```
cd Documents
```
- Now we will create the flutter project.
```
flutter create hello_world
```
- Now move into the project's directory.
```
cd hello_world
```
- Now open the project in VS Code using **Ctrl+K+O**.
#### Using VS Code
- After installing flutter extension in VS Code, Open command pallete using the shortcut **Ctrl+Shift+P**. The following dialog box appears.
 ![image](https://user-images.githubusercontent.com/76885050/228367220-ab3aa3c9-d315-4c8f-a515-ccbeb4506097.png)
- Select Flutter: New Project. A new dialog Box appears.
 ![image](https://user-images.githubusercontent.com/76885050/228367316-d2ee64b2-401d-452a-bb7a-280ad24eebf5.png)
- Select Application. After which we have to select the folder in which we have to select the folder in which we want our project.
 ![image](https://user-images.githubusercontent.com/76885050/228367485-fb92153e-f140-4a7b-b032-ca3a47ad070b.png)
- Now give the name of our Project **hello_world**.
 ![image](https://user-images.githubusercontent.com/76885050/228367771-e222dbf8-d450-4bea-96e4-813ff04774a0.png)
- Let it load and your project is created.

### Running the project and playing with it
- To run the project, in Vscode , press **F5** or in terminal move into the project directory. And run the following.
```
flutter run
```
- Select the device in which we want to run our project, here we will choose chrome i.e. we will write **2**.
 ![image](https://user-images.githubusercontent.com/76885050/228369486-71ea1edd-cc84-4bf6-b2fc-368fd53e4c52.png)
 - After a while it will run the project in Chrome.
  ![image](https://user-images.githubusercontent.com/76885050/228369950-3fe49cb1-9103-42c4-8ec5-b6d36a35b02a.png)

- When we have created the project the following file structure appears.

 ![image](https://user-images.githubusercontent.com/76885050/228370259-29994338-edcb-4074-9ccc-541c6770c186.png)
- In this, the corresponding directories correspond to that environment, i.e. android for our android app, ios for ios app, web for our web app,etc.
- We only need to add/edit code in the lib directory.
- main.dart is the current code that is running.
- main function loads our app, which calls an inbuild function runApp() where we pass the class we want to load which in our case is MyApp.
- MyApp returns a MaterialApp widget.
- This MyApp class loads the MyHomePage.

#### Exploring the code
- To remove the debug tag in the app, we need to add the following code which is an attribute to the Material App at **Line 14**
```
debugShowCheckedModeBanner: false,
```
- To change the theme of our app, change the color blue to green at **Line 26**.
```
primarySwatch: Colors.green, 
```
Run again(which can be done using r in terminal) and the theme changes.
![image](https://user-images.githubusercontent.com/76885050/228373058-7158fcfc-42b1-4ec0-9eb7-713f12c44b7e.png)
- At **Line 82** it uses a widget Column, changing it to Row will show both, the text and the count in a row.
```
        child: Row(
```
- Try to explore more by changing style, adding attributes, etc.
#### Adding Dependencies
- Dependencies can be added to our flutter project in pubspect.yaml file in the root directory which can be added after **Line 31** .
- To add a directory select the dependency from pub.dev and run the follwoing code in terminal to load the dependecy.
```
flutter pub get
```
## Additional Resources
- [Flutter Documentation](https://docs.flutter.dev/)
- [pub.dev](https://pub.dev/)
- [Flutter Widgets Catalog](https://docs.flutter.dev/development/ui/widgets)
- [Flutter Layout Cheat Sheet](https://medium.com/flutter-community/flutter-layout-cheat-sheet-5363348d037e)
- [Video Tutorials](https://www.youtube.com/playlist?list=PLlxmoA0rQ-Lw6tAs2fGFuXGP13-dWdKsB)


