Javascript example is easy to code. JavaScript provides 3 places to put the JavaScript code: within body tag, within head tag and external JavaScript file.

The script tag specifies that we are using JavaScript.

The text/javascript is the content type that provides information to the browser about the data.

The document.write() function is used to display dynamic content through JavaScript.
3 Places to put JavaScript code

    Between the head tag of html
    Between the body tag of html
    In .js file (external javaScript)

1. JavaScript Example : code between the head tag

Let’s see the same example of displaying alert dialog box of JavaScript that is contained inside the head tag.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>JavaScript</title>
    <script>
        document.write("Hello from Yahoo Baba");
    </script>
</head>
<body>
    <h1>Hello</h1>
</body>
</html>

2. JavaScript Example : code between the body tag

In this example, we have displayed the dynamic content using JavaScript in body tag.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>JavaScript</title>
</head>
<body>
    <h1>Hello</h1>
    <script> 
        document.write("Hello from Yahoo Baba");
    </script>
</body>
</html>

3. External JavaScript file

We can create external JavaScript file and embed it in many html page.

It provides code re usability because single JavaScript file can be used in several html pages.

An external JavaScript file must be saved by .js extension. It is recommended to embed all JavaScript files into a single file. It increases the speed of the webpage.

Let's create an external JavaScript test.js file that prints Hey Hello Again.

// test.js file
document.write("Hey Hello Again");

Let's include the JavaScript file into html page. It calls the JavaScript function.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>JavaScript</title>
   <!-- External JavaScript -->
    <script src="js/test.js"></script> 
</head>
<body>
    <h1>Hello</h1>
</body>
</html>
