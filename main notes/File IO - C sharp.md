31-01-25
08:42 pm

|                  |                                                                                                       |
| ---------------- | ----------------------------------------------------------------------------------------------------- |
| `AppendText()`   | Appends text at the end of an existing file                                                           |
| `Copy()`         | Copies a file                                                                                         |
| `Create()`       | Creates or overwrites a file                                                                          |
| `Delete()`       | Deletes a file                                                                                        |
| `Exists()`       | Tests whether the file exists                                                                         |
| `ReadAllText()`  | Reads the contents of a file                                                                          |
| `Replace()`      | Replaces the contents of a file with the contents of another file                                     |
| `WriteAllText()` | Creates a new file and writes the contents to it. If the file already exists, it will be overwritten. |
```C#
string text = "this is a text";

File.WriteAllText("Hello.txt" , text);
```
