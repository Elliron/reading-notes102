# Javascript notes

## This is the HTML file I created that will be include an interactive javascript function.

```
<!DOCTYPE html>
<html>
    <head>
        <title>Constructive &amp; Co.</title>
        <link rel="stylesheet" href="css/c01.css" />
    </head>
    <body>
        <h1>Constructive &amp; Co.</h1>
    <script>document.write('<h3>Welcome</h3>');
    </script>
        <p>For all orders and inquiries please call
          <em>555-3344</em></p>
    </body>
</html>
```

## This is the javascript function that greets the visitor with the time of day.

```
var today = new Date();
var hourNow = today.getHours();
var greeting;

if (hourNow > 18) {
    greeting = 'Good evening!';
}  else if (hourNow > 12) {
    greeting = 'Good afternoon!';
}  else if (hourNow > 0) {
    greeting = 'Good morning!';
}  else {
    greeting = 'Welcome!';
}

document.write('<h3>' + greeting + '</h3>');
```


[<==Back[README.md)