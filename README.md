<!doctype html>
<html lang="fa">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Centered Image</title>
<style>
  html,body { height:100%; margin:0; }
  body {
    display: flex;
    align-items: center;      /* مرکز عمودی */
    justify-content: center;  /* مرکز افقی */
    flex-direction: column;   /* تصویر بالاتر، تیتر پایین یا بالعکس */
    gap: 1rem;
    font-family: sans-serif;
  }
  img {
    width: 50%;       /* اندازه مثل README */
    max-width: 900px; /* حداکثر اندازه */
    height: auto;
    display: block;
  }
  h1 { margin: 0; text-align: center; }
</style>
</head>
<body>
  <img src="./Subject.png" alt="Subject">
  <h1>Hello Dear</h1>
</body>
</html>
