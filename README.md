```csharp 
Console.WriteLine("Hello World!");

Human human = new Human()
{
  Name = "Tanveer Najib",
  Age = "18",
  DOB = new DateTime(2002, 7, 15),
  Organization = new Organization("Kitric"),
  Languages = LanguageCollection.Build(new string[] { "c#", "python", "java" }),
  Learning = LanguageCollection.Build(new string[] { "c++", "javascript", "django" })
};

human.AgeAsync();
```
