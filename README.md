![Zoder Logo](./asset/images/Logo.png)

# Zoder

# Introduction

Zoder is a dark theme designed to enhance your coding experience with a visually appealing and comfortable environment. Inspired by the Monokai Pro theme, Zoder brings a unique color palette that is easy on the eyes and perfect for long coding sessions.

# Features

- **Dark Theme:** Eye-friendly dark background with high-contrast, vibrant colors.
- **Language Support:** Tailored color schemes for JavaScript, TypeScript, React, Python, and more.
- **Consistency:** Balanced color usage for easy readability across various programming languages.

# Preview

#### Python

```python
def greet(name: str) -> str:
    greeting = f"Hello, {name}!"
    print(greeting)
    return greeting

if __name__ == "__main__":
    greet("World")
```

#### Typescript

```typescript
function greet(name: string): string {
  const greeting: string = `Hello, ${name}!`;
  console.log(greeting);
  return greeting;
}

greet("World");
```

#### Javascript

```javascript
function greet(name) {
  const greeting = `Hello, ${name}!`;
  console.log(greeting);
  return greeting;
}

greet("World");
```

#### Java

```java
public class Main {
    public static void main(String[] args) {
        System.out.println(greet("World"));
    }

    public static String greet(String name) {
        return "Hello, " + name + "!";
    }
}

```

#### C#

```C#
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine(Greet("World"));
    }

    static string Greet(string name)
    {
        return $"Hello, {name}!";
    }
}
```

#### C++

```c++
#include <iostream>
#include <string>

std::string greet(const std::string& name) {
    return "Hello, " + name + "!";
}

int main() {
    std::cout << greet("World") << std::endl;
    return 0;
}

```

#### Go(Golang)

```go
package main

import "fmt"

func greet(name string) string {
    return fmt.Sprintf("Hello, %s!", name)
}

func main() {
    fmt.Println(greet("World"))
}
```

#### Rust

```rust
fn greet(name: &str) -> String {
    format!("Hello, {}!", name)
}

fn main() {
    println!("{}", greet("World"));
}
```

## Installation

You can install the Zoder theme from the Visual Studio Code Marketplace.

- **Extension URL:** [Zoder on Marketplace](https://marketplace.visualstudio.com/items?itemName=ZahoorOnly.zoder)
- **Hub URL:** [Manage Zoder](https://marketplace.visualstudio.com/manage/publishers/ZahoorOnly/extensions/zoder/hub)

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

- Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
- Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
- Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ZahoorOnly/Zoder-vscode-theme/issues) on GitHub.

## For More Information

- [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
- [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

```
This updated `README.md` includes demo code for the top 8 languages while preserving the original content.
```

**Enjoy coding with Zoder!**
