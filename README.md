# Basic-IO
A easy to use .dll file for managing / modifying files and directories on your windows pc

This .dll simplifies System.IO to help reduce lines of codes and help users to easily manage files and directories

## How to setup BIO.dll on Visual Studio

1. First you will need to download the BIO.rar file at https://github.com/Ruan191/Basic-IO/blob/master/BIO.rar. After you have downloaded
   the file feel free to extract the file anywhere you want on your PC.
   
2. Open up your project you want to use the BIO.dll on.

3. Click on Solution Explorer, then right click on References and select "Add Reference..."

![github-large](https://github.com/Ruan191/Basic-IO/blob/master/images/ref.PNG)

4. You will see a Reference Manager pop up, on the left side click "Browse" and then click the "Browse..." button on the bottom right.

![github-large](https://github.com/Ruan191/Basic-IO/blob/master/images/rm.PNG)

5. Go to the directory where you have extracted the BIO.rar then double click the BIO.dll file.

6. You will be placed back to the Reference Manager where you will see the BIO.dll being checked. Click "OK".

![github-large](https://github.com/Ruan191/Basic-IO/blob/master/images/done.PNG)

7. After all that is done you will need to declare that you will be using the BIO.dll in you code. Then you are ready to use BIO.

## BIO code

### Class F and D
contains two classes, class "F" contains methods for files while class "D" contains methods for directories. You will first need to declare BIO.F or BIO.D as an object  before you can access it.

### Class F Methods
#### rf
* rf(String location) reads a files content to the end and returns it as a String
* rf(String location, Char split)  splits the files content to an array

#### wf
* wf(String location, String write, bool writeline, bool append) Writes to a file location (if the location does not exist the a new file will be created) 
* "location" the file location.
* "write" what will be written on the file.
* "writeline" determines if what is written will go to a new line or not.
* "append" determines if file will be overwritten or added upon.
