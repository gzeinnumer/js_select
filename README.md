# js_select

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script
      src="https://code.jquery.com/jquery-3.3.1.js"
      integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
      crossorigin="anonymous"
    ></script>
  </head>
  <body>
    <select name="name" id="name">
      <option value="1">One</option>
      <option value="2">One</option>
      <option value="3">One</option>
    </select>
    <script>
      $(function () {
        initSelect();
      });

      function initSelect() {
        $("select#name").change(function () {
          var value = $(this).val();
          alert(value);
        });
      }
    </script>
  </body>
</html>
```

---

```
Copyright 2023 M. Fadli Zein
```