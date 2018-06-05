
## Lesson 2: TypeScript Continued  
* [**Classes**](#classes)  
* [**Unnamed And Named Expressions**](#unnamed-and-named-expressions)  
* [**Extending Classes**](#extending-classes)  
* [**Implementing An Interface**](#implementing-an-interface)  
* [**Public Access Modifier**](#public-access-modifier)  
* [**Private Access Modifier**](#private-access-modifier)  

[Back To Main](../)  

### Classes
Much like classes, interfaces can also be used to extend one another. This allows you to copy the members of one interface into another and add additional to create a new interface.  
<iframe src="https://stackblitz.com/edit/ts-class-declaration?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#lesson-2-typescript-continued)  

### Unnamed And Named Expressions  
A class expression can be done in one of two ways, named or unnamed.  
<iframe src="https://stackblitz.com/edit/ts-unnamed-class-expression?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
<iframe src="https://stackblitz.com/edit/ts-named-class-expression?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#lesson-2-typescript-continued)  

### Extending Classes  
Using the Rectangle class you can create a new class for squares. Notice that you have access to this.height and this.width however the properties did not need to be declared inside the Square class because they were inherited from the Rectangle class.  
<iframe src="https://stackblitz.com/edit/ts-extending-classes?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#lesson-2-typescript-continued)  

### Implementing An Interface  
Inheritance can also be used to implement other classes and interfaces. In this example, because you are inheriting from an interface you need to create the properties inside the class because an interface is just a set of rules and the properties inside of the interface are not actually JavaScript objects, they are just a representation of what the real object will need to contain.  
<iframe src="https://stackblitz.com/edit/ts-class-implement-interface?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#lesson-2-typescript-continued)  

### Public Access Modifier  
Everything beening used in classes has been public thus far. TypeScript properties are public by default and can be accessed freely throughout the program. With this in mind, you could explicitly define each property as public.  
<iframe src="https://stackblitz.com/edit/ts-classes-public-access-modifier?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#lesson-2-typescript-continued)  

### Private Access Modifier  
When a member of a class is marked private, it cannot be accessed from outside of the containing class. For example, if the perimeter method were marked as private it would not be accessible outside of the class declaration.  
<iframe src="https://stackblitz.com/edit/ts-class-private-access-modifier?embed=1&file=index.ts&hideExplorer=1&hideNavigation=1&view=editor" width="600px" height="400px"></iframe>  
[Back To Top](#lesson-2-typescript-continued)  

