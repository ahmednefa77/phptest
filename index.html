<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><?php echo " My document" ?></title>
</head>

<body>
  <?php
  eCho "يارب وفقني"."<br>";
 $x=true;
  $element="allahom lak el7md";
  
  $connec=mysqli_connect("localhost","root","","zazax");
  $q="select * from clients";
  $RSmex=mysqli_query($connec,$q);
  $RSme=mysqli_fetch_assoc($RSmex);
  echo "<table border='1'>";
  echo "<tr>";$max=0;
   foreach($RSme as $key=> $data)
   {
       echo "<td>".$key."</td>";
       $max++;

   };
   echo $max;
   echo "</tr>";
   $RSmex=mysqli_query($connec,$q);
   while($row=mysqli_fetch_array($RSmex))
   {  echo "<tr>";
      for($i=0;$i<$max;$i++)
      {echo "<td>".$row[$i]."</td>";}
      

      echo"</tr>"; 
       
};mysqli_close($connec);
echo"</table>";
if(isset($_POST['add']))
{
    $I=$_POST['IDn'];$n=$_POST['Namen'];$e=$_POST['emailn'];$b=$_POST['birthdaten'];
    //$mysqli=new mysqli("localhost","root","","zazax");
    //$q=$mysqli->prepare ("insert into clients values(?,?,?,?);");
    //$q->bind_param("isss",$I,$n,$e,$b);
    //$q->execute();
    $connec=mysqli_connect("localhost","root","","zazax");
    $q=mysqli_prepare($connec,"insert into clients values(?,?,?,?);");
    //$RS=mysqli_query($connec,"ALTER TABLE clients AUTO_INCREMENT = SELECT MAX( ID ) FROM clients  ;");

    $I=null;
    mysqli_stmt_bind_param($q, "isss",$I,$n,$e,$b);

    mysqli_stmt_execute($q);
    //$_POST['add']="";
    
    
    
   if (mysqli_error($connec)){echo mysqli_error($connec);}
    echo "الله اكبر";
    echo rand(5000,10000);
  header("refresh:0");
    //$mysqli->close();
}
if(isset($_POST['update']))
{
    $connec=mysqli_connect("localhost","root","","zazax");
    $q=mysqli_prepare($connec,"update clients set Name=?, email=?, birthdate=? where ID=? ");
    $I=$_POST['IDn'];$n=$_POST['Namen'];$e=$_POST['emailn'];$b=$_POST['birthdaten'];
    mysqli_stmt_bind_param($q,"sssi",$n,$e,$b,$I);
    mysqli_stmt_execute($q);
    
    echo "الحمد لله";
    if(mysqli_error($connec)) echo mysqli_error($connec);
    header("refresh:0");

}
if(isset($_POST['delete']))
{
    $connec=mysqli_connect("localhost","root","","zazax");
    $q=mysqli_prepare($connec,"delete from clients  where ID=? ");
    //$I=$_POST['IDn'];$n=$_POST['Namen'];$e=$_POST['emailn'];$b=$_POST['birthdaten'];
    mysqli_stmt_bind_param($q,"i",$_POST['IDn']);
    mysqli_stmt_execute($q);
    
    echo "الحمد لله";
    if(mysqli_error($connec)) echo mysqli_error($connec);
    header("refresh:0");

}
if (isset($_POST['search']))
{

    $connec=mysqli_connect("localhost","root","","zazax");
    $Nc=$_POST['Namec'];$ec=$_POST['emailc'];$bc=$_POST['birthdatec'];
    if ($Nc=="") $Nc="%";
    if ($ec=="") $ec="%";
    if ($bc=="") $bc="%";
    $q="select * from clients  where name like '%".$Nc."%' and email like '".$ec."' and birthdate like '".$bc."'";
     echo $Nc;
    $RSmex=mysqli_query($connec,$q);
    $RSme=mysqli_fetch_assoc($RSmex);
    echo "<table border='1'>";
    echo "<tr>";$max=0;
     foreach($RSme as $key=> $data)
     {
         echo "<td>".$key."</td>";
         $max++;
  
     };
     echo $max;
     echo "</tr>";
     $RSmex=mysqli_query($connec,$q);
     while($row=mysqli_fetch_array($RSmex))
     {  echo "<tr>";
        for($i=0;$i<$max;$i++)
        {echo "<td>".$row[$i]."</td>";}
        
  
        echo"</tr>"; 
         
  };mysqli_close($connec);
 // header("refresh:0");
  echo"</table>";

}
?>
<form method="POST">
    ID   :<input name="IDn" /><br>
    Name :<input name="Namen" /><br>
    email:<input name="emailn"   /><br>
    Birthdate<input name="birthdaten" /><br>
    <button type="submit" name="add" >Add</button>
    <button type="submit" name="update">update</button>
    <button type="submit" name="delete">delete</button>
</form>
<form method="POST">
    Name <input type="text" name="Namec" ><br>
    email <input type="text" name="emailc" ><br>
    birthdate<input type="text" name="birthdatec"><br>
    <button type="submit" name="search">Search</button>
</form>
</body>
</html>
