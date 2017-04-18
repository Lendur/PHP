# PHP
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <?php
    $day = date("l");
    if($day == "Monday"){
      $day = "Esmaspäev";
    }elseif($day == "Tuesday"){
      $day = "Teisipäev";
    }elseif($day == "Wednesday"){
      $day = "Kolmapäev";
    }elseif($day == "Thursday"){
      $day = "Neljapäev";
    }elseif($day == "Friday"){
      $day = "Reede";
    }elseif($day == "Saturday"){
      $day = "Laupäev";
    }elseif($day == "Sunday"){
      $day = "Pühapäev";
    }
    echo "" . date("d/m/Y");
    date_default_timezone_set("Europe/Tallinn");
    echo " " . date("H:i");
    ?>
  </body>
</html>
