
<!-- <!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stmo Production</title>
  <style>
    .responsive-iframe {
      position: absolute;
      top: 0;
      left: 0;
      bottom: 0;
      right: 0;
      width: 100vw;
      height: 100vh;
      border: none;
    }
  </style>
</head>
<body style="padding:0px; margin:0px; width:100vw; height:100vh; background-color:#eee;">
  <div> 
    <iframe id="myframe" class="responsive-iframe" src="" allowFullScreen  frameborder="0" scrolling="no" style="width: 100%; height: 100%;"></iframe>
    <br/>
  </div>
  <script>
    const apps = new URL(window.location);
    const formUrl = apps.searchParams.get('apps');
    const url = decodeURIComponent(formUrl)
          document.getElementById('myframe').src = url
  </script>
</body>
</html>
 -->


 
<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stmo Production</title>
  <style>
    .responsive-iframe {
      position: absolute;
      top: 0;
      left: 0;
      bottom: 0;
      right: 0;
      width: 100vw;
      height: 100vh;
      border: none;
    }
  </style>
</head>

<body style="padding:0px; margin:0px; width:100vw; height:100vh; background-color:#eee;">
  <div>
    <iframe id="myframe" class="responsive-iframe" src="" allowFullScreen frameborder="0" scrolling="no"
      style="width: 100%; height: 100%;"></iframe>
    <br />
  </div>
  <script>
    const apps = new URL(window.location);
    const formUrl = apps.searchParams.get('apps');
    const url = decodeURIComponent(formUrl)
    document.getElementById('myframe').src = url
  </script>
</body>

</html>
