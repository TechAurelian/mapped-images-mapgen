# mapped-images-mapgen

The script was created by Microsoft Bing chat mode, a conversational interface that can generate code, among other things. This is the prompt that was used to generate the script:

> Write the code for a Node.js script in JavaScript that:
>
> * finds all the image files in a directory and all its subdirectories; the image types should be defined as a global const to update easily; the directory is sent to the script as a parameter on the command line
> * creates an object with a property for each image file path that contains an object with only the width and height of the image calculated using the image-size Node package; the image file path should be relative to the initial directory and have "/" delimiters
> * writes the object as a TypeScript module that exports that object, with whitespace and nicely formatted; the file path of the TypeScript module is sent to the script as a parameter on the command line
> * writes a success message to the console with the number of image files that were processed
