<html>
  <head>
    <title>Luas Lingkaran</title>
  </head>
  <body>
    
    <script language="javascript">
    function luaslingkaran()
    { var jari2 =
    perseFloat(document.funday.nilai_jari2.value);
    if(isNaN(jari2)){
    jari2=0.0;}
    var hasil = 3.14*jari2*jari2;
    alert("Jadi, luas lingkaran adalah : "+ hasil);}
    </script>
    
    <form name="funday">
    <pre>
    Nilai Jari-jari = <input type="text" name="nilai_jari2"
    />
    </pre>
    <input type="button" value="Hitung Sekarang"
    onClick="luaslingkaran()" />
    <input type="reset" value="Reset" />
    </form>
    
    </body>
    </html>
