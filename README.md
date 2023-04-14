# CSS-animation-assignment-
<!DOCTYPE html>

<html>

<head>

  <title>Continuous Movement Animation</title>

  <style>

    .box {

      width: 50px;

      height: 50px;

      background-color: red;

      position: absolute;

      top: 50%;

      left: 0;

      animation: move-box 2s linear infinite;

    }

    

    @keyframes move-box {

      0% {

        left: 0;

      }

      100% {

        left: calc(100% - 50px);

      }

    }

  </style>

</head>

<body>

  <div class="box"></div>

</body>

</html>
