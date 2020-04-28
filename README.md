# Lambok-Java

Lambok Java getter setters annotations
  @data
  @getter  @setter
  @noargsArgument



CustomLog	
Causes lombok to generate a logger field based on a custom logger implementation.
Data	
Generates getters for all fields, a useful toString method, and hashCode and equals implementations that check all non-transient fields.
Delegate	Deprecated.
Use Delegate instead.
EqualsAndHashCode	
Generates implementations for the equals and hashCode methods inherited by all objects, based on relevant fields.
EqualsAndHashCode.AnyAnnotation	Deprecated.
Don't use this annotation, ever - Read the documentation.
EqualsAndHashCode.Exclude	
If present, do not include this field in the generated equals and hashCode methods.
EqualsAndHashCode.Include	
Configure the behaviour of how this member is treated in the equals and hashCode implementation; if on a method, include the method's return value as part of calculating hashCode/equality.
Generated	
Lombok will eventually automatically add this annotation to all generated constructors, methods, fields, and types.
Getter	
Put on any field to make lombok build a standard getter.
Getter.AnyAnnotation	Deprecated.
Don't use this annotation, ever - Read the documentation.
NoArgsConstructor	
Generates a no-args constructor.
NoArgsConstructor.AnyAnnotation	Deprecated.
Don't use this annotation, ever - Read the documentation.
NonNull	
If put on a parameter, lombok will insert a null-check at the start of the method / constructor's body, throwing a NullPointerException with the parameter's name as message.
RequiredArgsConstructor	
Generates a constructor with required arguments.
RequiredArgsConstructor.AnyAnnotation	Deprecated.
Don't use this annotation, ever - Read the documentation.
Setter	
Put on any field to make lombok build a standard setter.
Setter.AnyAnnotation	Deprecated.
Don't use this annotation, ever - Read the documentation.
Singular	
The singular annotation is used together with @Builder to create single element 'add' methods in the builder for collections.
SneakyThrows	
@SneakyThrow will avoid javac's insistence that you either catch or throw onward any checked exceptions that statements in your method body declare they generate.
Synchronized	
Almost exactly like putting the 'synchronized' keyword on a method, except will synchronize on a private internal Object, so that other code not under your control doesn't meddle with your thread management by locking on your own instance.
ToString	
Generates an implementation for the toString method inherited by all objects, consisting of printing the values of relevant fields.
ToString.Exclude	
If present, do not include this field in the generated toString.
ToString.Include	
Configure the behaviour of how this member is rendered in the toString; if on a method, include the method's return value in the output.
val	
Use val as the type of any local variable declaration (even in a for-each statement), and the type will be inferred from the initializing expression.
Value	
Generates a lot of code which fits with a class that is a representation of an immutable entity.
var	
Use var as the type of any local variable declaration (even in a for statement), and the type will be inferred from the initializing expression (any further assignments to the variable are not involved in this type inference).
With	
Put on any field to make lombok build a 'with' - a withX


<a href="http://starwalt.in/Blogs/index.html">Follow us on Blog</a>
