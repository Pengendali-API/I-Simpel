# List Command $app_name <small>$app_version</small>

<table class="table">

<thead>

<tr>

<th>Nama</th>

<th>URL</th>

<th>Keterangan</th>

</tr>

</thead>

<tbody>

<tr>

<td colspan="3">**LOGIN**</td>

</tr>

<tr>

<td>Request OTP</td>

<td>http://$url/otp?username=$username&pin=xxxxxxx</td>

<td> </td>

</tr>

<tr>

<td>VerifyOTP</td>

<td>http://$url/verifyOtp?username=$username&otp=xxxxxx</td>

<td>otp=isi sms otp</td>

</tr>

<tr>

<td colspan="3">**INFO**</td>

</tr>

<tr>

<td>Balance</td>

<td>http://$url/balance?username=$username</td>

<td> </td>

</tr>

<tr>

<td>Komisi</td>

<td>http://$url/komisi?username=$username</td>

<td> </td>

</tr>

<tr>

<td>Info Koin</td>

<td>http://$url/koin_info?username=$username</td>

<td> </td>

</tr>

<tr>

<td>Status Koin</td>

<td>http://$url/koin_status?username=$username</td>

<td> </td>

</tr>

<tr>

<td colspan="3">**TRANSAKSI**</td>

</tr>

<tr>

<td>Daftar Produk</td>

<td>http://$url/list_product?username=$username</td>

<td> </td>

</tr>

<tr>

<td>Topup/Pulsa</td>

<td>http://$url/topup?username=$username&to=[tujuan]&dnmcode=[kode]</td>

<td>opsional lokasi gps &latitude=xxx.xxxx&longitude=xxx.xxxx</td>

</tr>

<tr>

<td>Data</td>

<td>http://$url/data?username=$username&to=[tujuan]&dnmcode=[kode]</td>

<td>opsional lokasi gps &latitude=xxx.xxxx&longitude=xxx.xxxx</td>

</tr>

<tr>

<td>Voucher</td>

<td>http://$url/voucher?username=$username&to=[tujuan]&dnmcode=[kode]</td>

<td>opsional lokasi gps &latitude=xxx.xxxx&longitude=xxx.xxxx</td>

</tr>

<tr>

<td>SIM Registrasi</td>

<td>http://$url/voucher?username=$username&to=[tujuan]&dnmcode=[kode]</td>

<td> </td>

</tr>

<tr>

<td colspan="3">**HISTORY**</td>

</tr>

<tr>

<td>History Topup</td>

<td>http://$url/history_topup?username=$username&page=1&pagesize=20&start_date=$tahun-$bulan-01&end_date=$tahun-$bulan-$tanggal</td>

<td>untuk pencarian tambahkan &search=nomor_hp, untuk filter status tambahkan &status=1</td>

</tr>

<tr>

<td>History Data</td>

<td>http://$url/history_data?username=$username&page=1&pagesize=20&start_date=$tahun-$bulan-01&end_date=$tahun-$bulan-$tanggal</td>

<td>untuk pencarian tambahkan &search=nomor_hp, untuk filter status tambahkan &status=1</td>

</tr>

<tr>

<td>History SIM Registrasi</td>

<td>http://$url/history_registrasi?username=$username&page=1&pagesize=20&start_date=$tahun-$bulan-01&end_date=$tahun-$bulan-$tanggal</td>

<td>untuk pencarian tambahkan &search=nomor_hp, untuk filter status tambahkan &status=1</td>

</tr>

<tr>

<td>History Koin Redeem</td>

<td>http://$url/history_redeem?username=$username&page=1&pagesize=20&start_date=$tahun-$bulan-01&end_date=$tahun-$bulan-$tanggal</td>

<td> </td>

</tr>

<tr>

<td colspan="3">**Lain-lain**</td>

</tr>

<tr>

<td>Request Credit</td>

<td>http://$url/request_credit?username=$username&amount=100000</td>

<td> </td>

</tr>

<tr>

<td>Status Registrasi SIM</td>

<td>http://$url/sim_status?username=$username&to=nomor_hp</td>

<td> </td>

</tr>

<tr>

<td>Performa</td>

<td>http://$url/performa?username=$username</td>

<td> </td>

</tr>

<tr>

<td>Income</td>

<td>http://$url/income?username=$username</td>

<td> </td>

</tr>

<tr>

<td>Program</td>

<td>http://$url/program?username=$username</td>

<td> </td>

</tr>

<tr>

<td>Ganti PIN</td>

<td>http://$url/change_pin?username=$username&pin=pin_baru</td>

<td> </td>

</tr>

<tr>

<td>Reset PIN</td>

<td>http://$url/reset_pin?username=$username</td>

<td> </td>

</tr>

<tr>

<td>Logout</td>

<td>http://$url/logout?username=$username</td>

<td> </td>

</tr>

</tbody>

</table>
