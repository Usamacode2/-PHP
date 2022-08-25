
<?php
//by Osama Mohamed
// حل تكليفات الاسيوع الثاني php
?>

#1
<!DOCTYPE html>
<html>
<body>

<?php  
echo (int)(15.2 + 14.7) + (10.5 + 10.5); // 50
echo "<br>";
echo gettype ((int)(15.2 + 14.7 )+(int) (10.5 + 10.5)); // Integer
?>  

</body>
</html>
============================
#2
<!DOCTYPE html>
<html>
<body>

<?php  
echo gettype(100); 
echo "<br>"; 
echo  var_dump(100);
echo "<br>"; 
echo (is_int(100) ? "int" : " ") ;
echo "<br>";
?>  

</body>
</html>
===============================
#3
<!DOCTYPE html>
<html>
<body>

<?php  
echo" Hello \"Elzero\" \\\\ \"\"\" We Love \"\$\$PHP\"";
echo "<br>"; 

?>  

</body>
</html>

=============================
#4
<!DOCTYPE html>
<html>
<body>

<?php  
echo nl2br("We
Love
Elzero
Web
School"
);

?>  
</body>
</html>

==============================
#5
<!DOCTYPE html>
<html>
<body>

<?php  
echo "<br>";
echo nl2br(<<<'output'
"Hello "'Elzero'"
We Love $Programming$
Languages Specially "PHP"
output);

?>  

</body>
</html>

==================================
#6
<!DOCTYPE html>
<html>
<body>

<?php  
$something = "Programming";

echo <<<"code"
Hello \PHP\
We Love $something
code;

?>  

</body>
</html>
==================================
#7
<!DOCTYPE html>
<html>
<body>

<?php  
echo (bool)"Hello PHP";
echo '<br>';
echo gettype ((int)(bool)"Hello PHP");
?>  

</body>
</html>
==================================
#8
<!DOCTYPE html>
<html>
<body>

<?php  
echo "<pre>" ;

print_r([
    "FrontEnd" => [
         "HTML" ,
         "CSS",
        "JS" => [
            "Vuejs" => [
                2 => "v2" ,
                3 => "v3"
            ],
            "Reactjs" ,
            "Svelte"
        ]
    ],
    "BackEnd" => [
        "PHP" ,
        "MySQL" ,
        "Security"
    ],
    "Git" ,
    "GitHub",
    "Testing" => [
        "Unit Testing" ,
        "End To End",
        "Integration"
    ]
]);
echo "</pre>" ;
?>  

</body>
</html>
