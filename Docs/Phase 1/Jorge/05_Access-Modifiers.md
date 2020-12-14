# Access Modifiers

There's a way you can manage what piece of code can access certain *classes* or *methods*, and this is easily achievable by using some of the following keywords:

#### Classes
Whenever we want to use a access modifier in a class we have:

- **public:** this class will be accessible for any other class
- **default:** this class will be accessible only for other classes in the same package

> By default, not using any keyword uses `default`

#### Methods and attributes
Otherwise, if we want to use the access modifiers for a method or attribute, we have a few more options:

- **public:** this method/attribute will be accessible for any other class
- **default:** this method/attribute will be accessible only for other classes in the same package
- **protected:** this is the same as default, plus that any subclass have the access to any method or attribute
- **private:** this method/attribute will only be accessible for the class where it was declared

### `Static` keyword

The `static` keyword makes the method/attribute to be part of the class itself and not instanciable. The *static methods/attributes* are "shared" among all the instances of the class.