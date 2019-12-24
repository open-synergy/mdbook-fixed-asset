# Penjelasan Asset Impairment

Informasi pada **Asset Impairment** dibagi menjadi beberapa area, diantaranya:
* [Header](#bagian-header)
* [Tab Note](#tab-note)
* [Tab Accounting Entry](#tab-accounting)
* [Tab Policy](#tab-policy)
* [Tab Log](#tab-log)

### <a name="bagian-header">HEADER</a>

![](../../img/asset-impairment/header.png)

#### <a name="field-dokumen"># Dokumen</a>

Nomor Dokumen.
(Nomor akan terisi otomatis setelah dikonfirmasi)

#### <a name="field-date">Date</a>

Tanggal Impairment.

#### <a name="field-period">Period</a>

Periode Impairment.
Biasanya sesuai dengan tanggal

#### <a name="field-aset">Aset</a>

Pilih Aset yang akan diimpairment.

#### <a name="field-impairment-amount">Impairment Amount</a>

Nilai Impairment(Penurunan Nilai).

#### <a name="field-impairment-account">Impairment Account</a>

Akun untuk impairment.

#### <a name="field-contra-impairment-account">Contra Impairment Account</a>

Akun untuk contra impairment.

#### <a name="field-journal">Journal</a>

Pilih Jurnal untuk impairment.

### <a name="tab-note">TAB NOTE</a>

![](../../img/asset-impairment/tab-note.png)

#### <a name="field-note">Note</a>

Catatan tambahan.

### <a name="tab-accounting">TAB ACCOUNTING ENTRY</a>

![](../../img/asset-impairment/tab-accounting.png)

#### <a name="field-accounting-entry"># Accounting Entry</a>

Nomor Accounting Entry.

### <a name="tab-policy">TAB POLICY</a>

![](../../img/asset-impairment/tab-policy.png)

#### <a name="field-change-can-confirm">Can Confirm</a>

Diisi otomatis oleh Odoo. Jika aktif, maka user yang membuka data transisi dapat melakukan [mengkonfirmasi impairment](./mengkonfirmasi.md).

#### <a name="field-change-can-validate">Can Validate</a>

Disii otomatis oleh Odoo. Jika aktif, maka user yang membuka data dapat [memvalidasi imapirment](./memvalidasi.md).

#### <a name="field-change-can-cancel">Can Cancel</a>

Diisi otomatis oleh Odoo. Jika aktif, maka user yang membuka data dapat [membatalkan impairment](./membatalkan.md).

#### <a name="field-change-can-restart">Can Restart</a>

Diisi otomatis oleh Odoo. Jika aktif, maka user yang membuka data dapat [merestart impairment](./merestart.md).

### <a name="tab-log">TAB LOG</a>

![](../../img/asset-impairment/tab-log.png)

#### <a name="field-log-confirmation">Confirmation</a>

Diisi otomatis oleh Odoo. Tanggal, waktu dan user yang [mengkonfirmasi impairment](./mengkonfirmasi.md).

#### <a name="field-log-validation">Validation</a>

Diisi otomatis oleh Odoo. Tanggal, waktu, dan user yang [memvalidasi impairment](./memvalidasi.md).

#### <a name="field-log-cancellation">Cancellation</a>

Diisi otomatis oleh Odoo. Tanggal, waktu, dan user yang [membatalkan impairment](./membatalkan.md).

[**Kembali ke menu Asset Impairment**](./../asset-impairment.md)
