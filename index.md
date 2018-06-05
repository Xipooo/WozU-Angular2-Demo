## Glossary  
Please wait for entire page to load before using links.  
* [**Lesson 1: TypeScript**](#lesson-1-typescript)  
* [**Lesson 2: TypeScript Continued**](#lesson-2-typescript-continued)  

## Lesson 1: TypeScript  
* [**Sandbox Project**](index.md#sandbox-project)  
* [**Static Typing**](#static-typing)  
* [**Common Types**](#common-types)  
* [**Interfaces**](#interfaces)  
* [**Optional Properties**](#optional-properties)  
* [**Interfaces And Classes**](#interfaces-and-classes)  

### Sandbox Project  
Now that everything is installed follow the below instructions to create a very simple project that will be used as a sandbox to play around with different TypeScript code examples.  
<iframe src="https://stackblitz.com/edit/ts-sandbox-project?embed=1&file=index.ts&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 1](#lesson-1-typescript)  

### Static Typing  
The variables below have type declarations that are specifying the type to be used by the variable. If the value were changed, it would need to correspond to the type specified.  
<iframe src="https://stackblitz.com/edit/ts-static-typing?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 1](#lesson-1-typescript)  

### Common Types   
The most commonly used types in TypeScript include the following:  
<iframe src="https://stackblitz.com/edit/ts-common-types?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 1](#lesson-1-typescript)  

### Interfaces  
Below is an example of an interface which defines what it means to be a sandwich.  
<iframe src="https://stackblitz.com/edit/ts-interfaces?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 1](#lesson-1-typescript)  

### Optional Properties  
Not all properties of an interface need to be required. Some exist under certain conditions or may not be there at all. The question mark (?) is used to denote an optional property.  
<iframe src="https://stackblitz.com/edit/ts-optional-properties?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 1](#lesson-1-typescript)  

### Interfaces And Classes  
The most common use of an interface in other strongly typed languages like C# and Java is to enforce that a class meets a particular structure. In TypeScript and Interface can be used in the same way as shown in the example below.  
<iframe src="https://stackblitz.com/edit/ts-interfaces-classes-pt1?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 1](#lesson-1-typescript)  

You can also describe methods in an interface to be implemented by the class. Below the Interfaces and class have been updated to include a method that prints the date in a clean format.  
<iframe src="https://stackblitz.com/edit/ts-interfaces-classes-pt2?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 1](#lesson-1-typescript)  

Much like classes, interfaces can also be used to extend one another. This allows you to copy the members of one interface into another and add additional to create a new interface.  
<iframe src="https://stackblitz.com/edit/ts-interfaces-classes-pt3?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 1](#lesson-1-typescript)  


## Lesson 2: TypeScript Continued  
* [**Classes**](#classes)  
* [**Unnamed And Named Expressions**](#unnamed-and-named-expressions)  
[Back To Top](#glossary)  

### Classes
Much like classes, interfaces can also be used to extend one another. This allows you to copy the members of one interface into another and add additional to create a new interface.  
<iframe src="https://stackblitz.com/edit/ts-class-declaration?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 2](#lesson-2-typescript-continued)  

### Unnamed And Named Expressions  
A class expression can be done in one of two ways, named or unnamed.  
<iframe src="https://stackblitz.com/edit/ts-unnamed-class-expression?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
<iframe src="https://stackblitz.com/edit/ts-named-class-expression?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#glossary)  
[Back To Lesson 2](#lesson-2-typescript-continued)  

