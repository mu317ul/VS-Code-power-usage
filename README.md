# VS-Code-power-usage
Emmet in VS Code 
---
📌 What is Emmet?

Emmet is a productivity tool built into VS Code that lets you write HTML and CSS faster using shortcuts called abbreviations. Instead of typing full tags and properties, you type a short expression, hit Tab (or the Emmet expand key), and Emmet expands it into full code.

🚀 Why use Emmet?

Saves time: Write 10–20 lines of HTML in one abbreviation.
Reduces typos: Less manual typing → fewer mistakes.
Improves workflow: Lets you focus on structure, not boilerplate.
Built-in: No extra extension needed in VS Code.

⚡ How to use Emmet in VS Code

Open an HTML or CSS file.
Type an abbreviation (e.g. ul>li*3>a{Link $}).
Press Tab → it expands into full code.
Make sure Settings → Emmet: Trigger Expansion On Tab is enabled. 

Link : https://gist.github.com/mu317ul/69a961b8c0dc4bca042e8ad1d70ee7c0
---

🚀 Custom HTML Snippet in VS Code
---

✨ What is a Snippet?
A snippet in VS Code (or any code editor) is a shortcut that expands into a larger block of code automatically.
It helps you save time and avoid writing the same code again and again.

This guide shows how to create and use a custom HTML5 boilerplate snippet in Visual Studio Code.

📌 Step 1: Add Snippet in html.json

Open VS Code → Command Palette (Ctrl + Shift + P / Cmd + Shift + P) →
Select Preferences: Configure User Snippets → choose html.json.
```html
{
  "HTML Boilerplate": {
    "prefix": "html5",
    "body": [
      "<!DOCTYPE html>",
      "<html lang=\"en\">",
      "<head>",
      "  <meta charset=\"UTF-8\">",
      "  <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">",
      "  <title>$1</title>",
      "  <link rel=\"stylesheet\" href=\"style.css\">",
      "</head>",
      "<body>",
      "  $2",
      "</body>",
      "</html>"
    ],
    "description": "Custom HTML5 boilerplate"
  }
}
```

📌 Step 2: Use the Snippet

Open a new .html file.
Type html5 (your prefix).
Press Tab → it will expand into:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
</body>
</html>
```

✅ Benefits
Saves time writing boilerplate code.
Ensures consistency across projects.
Can be customized with CSS/JS links as needed.

---
