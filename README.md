<?php
//identifikasikan semua nilai dari variable
$NamaLengkap = "Riyan Cahya Sukoyo";
$Prodi = "Teknologi Informasi A";
$Nim = "202520012";
$AlamatEmail = "riyancahyasukoyo23@gmail.com";
$TempatLahir = "Cianjur,15 Januari 1993";
$Alamat = "Pituruh";
$Minat = "Desain Grafis";
?>
<table>
<tr>
<td><?php echo "Nama Lengkap";?>/td>
<td><?php echo ":"; ?></td>
<td><?php echo $NamaLengkap ?>></td>
<td rowspan="9">
<img src="pasfoto.JPEG" width="130" height="200">
</td>
</tr>
<tr>
<td><?php echo "Prodi"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $Prodi ;?></td>
</tr>
<tr>
<td><?php echo "Nim"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $Nim ;?></td>
</tr>
<tr>
<td><?php echo "Alamat Email"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $AlamatEmail ;?></td>
</tr>
<tr>
<td><?php echo "Tempat,Tanggal Lahir"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $TempatLahir ;?></td>
</tr>
<tr>
<td><?php echo "Alamat"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $Alamat ;?></td>
</tr>
<tr>
<td><?php echo "Minat"; ?></td>
<td><?php echo ":"; ?></td>
<td><?php echo $Minat ;?></td>
</tr>
</table>
