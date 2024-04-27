# lab7_web

Nama  : Fajri Al Jauhari

Kelas : TI.22.A5

NIM   : 312210476

<?php

namespace App\Models;

use CodeIgniter\Model;

class ArtikelModel extends Model

{

protected $table = 'artikel';

protected $primaryKey = 'id';

protected $useAutoIncrement = true;

protected $allowedFields = ['judul', 'isi', 'status', 'slug',

'gambar'];

}
