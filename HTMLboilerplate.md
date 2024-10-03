![Boilerplate](https://plus.unsplash.com/premium_photo-1685086785077-ff65bf749544?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

# How to write an HTML Boilerplate

HTML documents have the same basic structure or boilerplate that needs to be in place before anything useful can be done.

## Creating an HTML file

1. Create a new file and name it `index.html`.
   **Note that it requires `.html` at the back of the file name.**
2. Inside your file, add the _boilerplate_:
   `<!DOCTYPE html>`
3. Add the HTML element:

```
<html lang="en">
</html>
```

4. Add the `<head>` and `<meta>` elements:

```
 <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
  </head>
```

5. Add the body element after the `</head>`.

```
<body>
    <h1>Hello World!</h1>
  </body>
```

## Another Way - the Emmet Method

_On your first line of your html file_, Type `!`, click the first Emmet and click enter. It should generate this code:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <script defer src="app.js"></script>
    <link rel="stylesheet" href="style.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

### Now you can begin coding!
