# marksheet
<?php
if (isset($_POST['submit']))
{

$sname=$_POST['stn'];
$fname=$_POST['stf'];
$mname=$_POST['stm'];
$bname=$_POST['stb'];

$htheory=$_POST['theory'];
$hpractical=$_POST['practical'];
$htotal=$htheory+$hpractical;

$etheory=$_POST['etheory'];
$epractical=$_POST['epractical'];
$etotal=$htheory+$hpractical;

$mtheory=$_POST['mtheory'];
$mpractical=$_POST['mpractical'];
$mtotal=$htheory+$hpractical;

$sctheory=$_POST['sctheory'];
$scpractical=$_POST['scpractical'];
$sctotal=$htheory+$hpractical;

$sotheory=$_POST['sotheory'];
$sopractical=$_POST['sopractical'];
$sototal=$htheory+$hpractical;

$satheory=$_POST['satheory'];
$sapractical=$_POST['sapractical'];
$satotal=$htheory+$hpractical;

$all_number=$htotal+$etotal+$mtotal+$sctotal+$sototal+$satotal;


}

?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>
<h1>BOARD OF SECONDERY EDUCATION  MADHAY PRADESH BHOPAL  </h1>    
<table border="1" cellpadding="3" cellspacing="0">
<tr>
    <td>
        center no.
    </td>
    <td>
        School No.
    </td>
    <td>
        Enrolament No.
    </td>
    <td>
        Roll NO.
    </td>
</tr>

<tr>
    <td>
        1111
    </td>
    <td>
    111
    </td>
    <td>
    22
    </td>
    <td>
    1111
    </td>

</tr>
</table>

<table border="0">
<tr> 
    <td>
    Student Name: <td><?=$sname?></td>
    </td>
</tr>
<tr>     
    <td>
    Student Father Name:
    </td>
</tr>
<tr>      
    <td>
    Student Mother Name:
    </td>
</tr>
</td>
<tr>   
    <td>
    Date of Brith:
    </td>   


</tr>
</table>

<table border="1" cellpaddin="3" cellspacing="0">
<tr>
    <td rowspan="2">Subject Name </td>
    <td colspan="3">Maximum Marks </td>
    <td colspan="2">Minimum marks</td>
    <td colspan="3">Marks Obtained</td>
    <td rowspan="2">Remarks</td>
</tr>   
<tr>
    <td>Theory </td>
    <td> Internal/<br>practical</td>
    <td>total</td>
    <td>Theory</td>
    <td>Internal/<br>practical</td>
    <td>Theory</td>
    <td>internal/<br>practical</td>
    <td>Total</td>

</tr>    
<tr>
    <td>Hindi</td>
    <td>80</td>
    <td>20</td>
    <td>26</td>
    <td>07</td></td>
    <td>100
    <td><?=$htheory?></td>
    <td><?=$hpractical?></td>
    <td><?=$htotal?></td>
</tr>
<tr>
   <td>English</td>
   <td>80</td>
    <td>20</td>
    <td>26</td>
    <td>07</td></td>
    <td>100
    <td><?=$etheory?></td>
    <td><?=$epractical?></td>
    <td><?=$etotal?></td> 
</tr>
<tr>   
    <td>Maths</td>
    <td>80</td>
    <td>20</td>
    <td>26</td>
    <td>07</td></td>
    <td>100
    <td><?=$mtheory?></td>
    <td><?=$mpractical?></td>
    <td><?=$mtotal?></td>
</tr>
<tr>    
    <td>Science</td>
    <td>80</td>
    <td>20</td>
    <td>26</td>
    <td>07</td></td>
    <td>100
    <td><?=$sctheory?></td>
    <td><?=$scpractical?></td>
    <td><?=$sctotal?></td>
</tr>
<tr>    
    <td>Social science</td>
    <td>80</td>
    <td>20</td>
    <td>26</td>
    <td>07</td></td>
    <td>100
    <td><?=$sotheory?></td>
    <td><?=$sopractical?></td>
    <td><?=$sototal?></td>
</tr>

<tr>    
    <td>Sanskrit</td>
    <td>80</td>
    <td>20</td>
    <td>26</td>
    <td>07</td></td>
    <td>100
    <td><?=$satheory?></td>
    <td><?=$sapractical?></td>
    <td><?=$satotal?></td>
</tr>    

<tr>
    <td colspan="2"></td>
    <td colspan="6">GRAND TOTAL : 600 </td>
    <td><?=$all_number?> </td>
    <td></td>
</tr>

</table>








</body>
</html>
