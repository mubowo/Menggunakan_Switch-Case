# Menggunakan_Switch-Case
[Exercises 4] Mengenal penggunaan Conditional (Switch-Case) dalam JavaScript

var hari = "1"; // assign nilai variabel tanggal disini! (dengan angka antara 1 - 31)
var bulan = "5"; // assign nilai variabel bulan disini! (dengan angka antara 1 - 12)
var tahun = "1945"; // assign nilai variabel tahun disini! (dengan angka antara 1900 - 2200)
var bln;



switch (bulan) {
    case "1" : { bln = "Januari"; console.log(hari+" "+bln+" "+tahun); break;}
    case "2" : { bln = "Februari"; console.log(hari+" "+bln+" "+tahun); break;}
    case "3" : { bln = "Maret"; console.log(hari+" "+bln+" "+tahun); break;}
    case "4" : { bln = "April"; console.log(hari+" "+bln+" "+tahun); break;}
    case "5" : { bln = "Mei"; console.log(hari+" "+bln+" "+tahun); break;}
    case "6" : { bln = "Juni"; console.log(hari+" "+bln+" "+tahun); break;}
    case "7" : { bln = "Juli"; console.log(hari+" "+bln+" "+tahun); break;}
    case "8" : { bln = "Agustus"; console.log(hari+" "+bln+" "+tahun); break;}
    case "9" : { bln = "September"; console.log(hari+" "+bln+" "+tahun); break;}
    case "10" : { bln = "Oktober"; console.log(hari+" "+bln+" "+tahun); break;}
    case "11" : { bln = "November"; console.log(hari+" "+bln+" "+tahun); break;}
    case "12" : { bln = "Desember"; console.log(hari+" "+bln+" "+tahun); break;}
    default : (console.log("Salah Input Data");
}
