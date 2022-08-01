###### Nama     : irdian candra.w
###### kelas    : XII RPL1
###### No absen : 28
## sebelum lanjut langkah sebaiknya kita akan membuka  modul 1 & 2 yang ada di bawah ini
```
https://github.com/irdiancandraw/test_readme/blob/main/README.md
```
# Modul 3
### selanjut nya kita akan membuat Route yang menuju kehalaman Kategori
```
<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class KategoriController extends Controller
{
    public function iya(){
    return 'Mengakses Fungsi di controller menggunakan route iya';
}
}
```

###### ubah script seperti dibawah ini.


![image](https://user-images.githubusercontent.com/109930652/182097015-949c4f12-6d51-474d-ad6d-9b4309378507.png)

###### Tahap berikut nya kita akan mencari WEB.php atau seperti di bawah.
![image](https://user-images.githubusercontent.com/109930652/182100029-b833a634-3783-446a-9dbb-4216c529d43e.png)

dan kita akan membuat kodingan seperti di bawah ini.
```
<?php

use Illuminate\Support\Facades\Route;
use App\Http\Controllers\BarangController;
use App\Http\Controllers\KategoriController;

Route::get('/barang', [BarangController::class, 'home']);
Route::get('/barang/add', [BarangController::class, 'add']);
Route::get('/kategori' ,[KategoriController:: class, 'iya']);
```
###### ubah script seperti dibawah ini.
![image](https://user-images.githubusercontent.com/109930652/182100711-fe40d6df-86d3-41d3-b5e0-80e8297ef351.png)

dan jangan lupa kita meruning dulu biar kode keluar.

![image](https://user-images.githubusercontent.com/109930652/182102093-dd7025aa-ad2c-4fa8-b079-ce99d6fbf119.png)

dan kita akan membuka crom di dalam kode "http/127.0.0.1:8000/kategori"
dan hasilnya seperti ini

![image](https://user-images.githubusercontent.com/109930652/182102795-80056910-0f18-453d-b143-fed93b53fbe9.png)

seleseilah tugas Modul 3.

