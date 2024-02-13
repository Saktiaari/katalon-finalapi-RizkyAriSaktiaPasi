# katalon-finalapi-RizkyAriSaktiaPasi

## TC Get Token
1. Mengirim permintaan ke server menggunakan objek permintaan yang telah dikonfigurasi menggunakan fungsi WS.sendRequest(findTestObject('POST Create Token'))
2. Hasil dari permintaan ini disimpan dalam variabel response
3. Membuat objek JsonSlurper yang akan membantu kita mengurai teks respons JSON
4. Mengurai teks respons JSON yang diterima dari permintaan dan hasilnya disimpan dalam result
5. mengambil nilai token dari objek result
6. Nilai token yang diperoleh dari respons disimpan dalam global variabel dengan nama TOKEN
7. Mencetak nilai token yang disimpan dalam global variabel TOKEN
8. Memverifikasi bahwa kode status respons yang diterima adalah 200 OK

## TC DELETE BOOKING
1. Mengirim permintaan API dengan objek permintaan POST Create Token dan Hasil dari permintaan ini disimpan dalam variabel response
2. Memverifikasi bahwa kode status respons yang diterima adalah 200 OK
3. Mengambil nilai token dari respons yang diambil dari properti bernama “token” dalam respons
4. Nilai token yang diperoleh dari respons disimpan dalam Global Variabel dengan nama TOKEN
5. Mengirim permintaan DELETE dengan menggunakan token yang telah diperoleh dan hasilnya disimpan dalam variabel updated
6. Mencetak hasil dari permintaan DELETE (respons dari server)
7. Memverifikasi bahwa kode status respons dari permintaan DELETE adalah 201 Created

## TC Get Booking
1. Mengirim permintaan API dengan objek permintaan Get BOOKING dan Hasil dari permintaan ini disimpan dalam variabel response
2. Memverifikasi bahwa kode status respons yang diterima adalah 200 OK

Link Video https://drive.google.com/file/d/1p_XPtqQA3IO3lKNo32IBRqNMOrG5mw8u/view?usp=sharing
