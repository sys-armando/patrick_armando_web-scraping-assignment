Scraping Publikasi BPS Provinsi Maluku

Tujuan untuk mendapatkan data publikasi BPS Provinsi Maluku yang dirilis tahun 2024
Proses scraping yang dilakukan sebagai berikut :
  import library pandas, requests dan beautiful soup
  mengambil link site bps provinsi maluku "https://maluku.bps.go.id/publication.html"
  kemudian define url ke variabel res
  kemudian define soup berisi library beautiful soup mengambil content dari url dan melakukan parsing html
  kemudian define products berisi mencari semua tag div, class pub even col-md-12 col-xs-12 col-sm-12
  kemudian menampung product di dalam dictionary
  kemudian define df untuk menampung dataframe(library pandas)
  kemudian melakukan ekspor publikasbps.csv

Hasil kerja :
Publikasibps.csv
