# Markdown Code Block Language Tags with Examples

Use fenced code blocks like this:

---

## 📄 General Languages

### Plain Text

```text title="add_a_title_to_your_code_block" linenums="1"
This is plain text.
Nothing will be highlighted.
```

### Markdown

```markdown title="add_a_title_to_your_code_block" linenums="4"
# This is a heading
- List item
- Another item
```

### HTML

```html title="add_a_title_to_your_code_block" linenums="1"
<!DOCTYPE html>
<html>
  <head><title>Page</title></head>
  <body><h1>Hello World</h1></body>
</html>
```

### C++

```cpp title="Highlight the line number" linenums="3" hl_lines='2-4'
#include <iostream>
int main() {
  std::cout << "Hello, World!";
  return 0;
}
```

### XML

```xml title="add_a_title_to_your_code_block" linenums="5"
<note>
  <to>User</to>
  <message>Hello</message>
</note>
```

### JSON

```json title="add_a_title_to_your_code_block" linenums="1"
{
  "name": "John",
  "age": 30
}
```

### YAML

```yaml title="add_a_title_to_your_code_block" linenums="2"
name: John
age: 30
```

### TOML

```toml title="add_a_title_to_your_code_block" linenums="1"
[owner]
name = "John"
```

### CSV

```csv title="add_a_title_to_your_code_block" linenums="1"
name,age
John,30
Jane,25
```

### javascript

```js title="code-examples.md" linenums="1" hl_lines="2-4"
// Function to concatenate two strings
function concatenateStrings(str1, str2) {
  return str1 + str2;
}

// Example usage
const result = concatenateStrings("Hello, ", "World!");
console.log("The concatenated string is:", result);
```
