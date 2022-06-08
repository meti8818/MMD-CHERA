# MMD-CHERA
BEGO CHERA
<!doctype html>
<html lang+"fa"
<meta charset="utf-8"
<head>
</head>
<body> 
</body>
</html>

<!DOCTYPE html>
<html lang='en' class=''>
  <head>
    <meta charset='UTF-8'>
    <title>Search Bar Demo</title>
    <style>
        body {
        background-color: #3745c2;
        margin: 200px 40%;
      }

      form {
        background-color: #4654e1;
        width: 300px;
        height: 44px;
        border-radius: 5px;
        display:flex;
        flex-direction:row;
        align-items:center;
      }

      input {
        all: unset;
        font: 16px system-ui;
        color: #fff;
        height: 100%;
        width: 100%;
        padding: 6px 10px;
      }

      ::placeholder {
        color: #fff;
        opacity: 0.7; 
      }

      svg {
        color: #fff;
        fill: currentColor;
        width: 24px;
        height: 24px;
        padding: 10px;
      }

      button {
        all: unset;
        cursor: pointer;
        width: 44px;
        height: 44px;
      }
    </style>
  </head>
  <body>
    <form role="search" id="form">
      <input type="search" id="query" name="q" placeholder="Search..." aria-label="Search through site content">
      <button>
        <svg viewBox="0 0 1024 1024"><path class="path1" d="M848.471 928l-263.059-263.059c-48.941 36.706-110.118 55.059-177.412 55.059-171.294 0-312-140.706-312-312s140.706-312 312-312c171.294 0 312 140.706 312 312 0 67.294-24.471 128.471-55.059 177.412l263.059 263.059-79.529 79.529zM189.623 408.078c0 121.364 97.091 218.455 218.455 218.455s218.455-97.091 218.455-218.455c0-121.364-103.159-218.455-218.455-218.455-121.364 0-218.455 97.091-218.455 218.455z"></path></svg>
      </button>
    </form>
    <script>
      const f = document.getElementById('form');
      const q = document.getElementById('query');
      const google = 'https://www.google.com/search?q=site%3A+';
      const site = 'pagedart.com';

      function submitted(event) {
        event.preventDefault();
        const url = google + site + '+' + q.value;
        const win = window.open(url, '_blank');
        win.focus();
      }

      f.addEventListener('submit', submitted);
    </script>
  </body>
</html>
<div class="scroll-div"></div>
سلام دوستان عزیز من ممد افضلی یک عدد گاواست شک داری میتونی سرچ کن
<img src="https://cdn.asriran.com/files/fa/news/1401/3/18/1399440_806.jpg">


.scroll-div {
width:100%;
height: 500px;
overflow-y: scroll;
position: absolute;
right:5px;
  top:5px;
}
body {
  color:red;
}
h1 { 
  text-align: right;
}
