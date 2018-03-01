
//php code for Fibonacci series
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <?php
function pattern($x)
 {
 
  $no1 = 0;
  $no2 = 1;
 
  echo "Pattern is \n";
 
  echo $no1.' '.$no2.' ';
 
  for($i = 2; $i < $x; $i++){
 
    $nox= $no1 + $no2;
 
    echo $nox.' ';
 
    $no1 = $no2;
    $no2 = $nox;
 
    }
}
    echo pattern(10);
    ?>
</body>
</html>

