## Rails scaffold generator template for Astah Community's any&lt;code /&gt;

This template helps you to generate a bunch of scaffolds to your Ruby on Rails projects based on classes created on an Astah Diagram.

For example: class Posts, with attributes title : String, url : string, content : text on astah, will be converted to the command "rails g scaffold title:string url:string content:text", and will be executed on your rails project.


In order to do that, you need:

- [Astah Community](http://astah.net/editions/community) (or any other)
- Install the [any&lt;code /&gt; plugin](http://anycode.labulle.in/)
- Create your classes
- Download this repository and use as a any&lt;code /&gt; template
- Run any of the generated files, it will ask your project's path
- Profit!

If you don't want to generate the scaffold of a class, just the model, simple put the anotation &lt;&lt;entity&gt;&gt; on that class.