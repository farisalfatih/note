### 1. Nonaktifkan Pagefile (Virtual Memory)
1. Tekan `Win + R`, ketik `sysdm.cpl`, Enter.
2. Masuk tab **Advanced → Performance → Settings → Advanced → Virtual memory → Change**.
3. Hilangkan centang **Automatically manage paging file size**.
4. Pilih drive, centang **No paging file**, klik **Set**, lalu **OK**.
5. Restart komputer.

### 2. Nonaktifkan Hibernation
1. Buka Command Prompt sebagai Admin.
2. Jalankan:
'powercfg /h off'
3. Ini akan menghapus file `hiberfil.sys` yang besar dan tidak bisa dipindahkan.

### 3. Nonaktifkan System Restore Sementara
1. Tekan `Win + R`, ketik `sysdm.cpl`, Enter.
2. Tab **System Protection → Configure → Turn off system protection**.
3. Klik **OK**.

### 4. Jalankan Disk Defragmenter
1. Buka **Defragment and Optimize Drives**.
2. Pilih drive C:, klik **Optimize**.
3. Ini memindahkan file ke awal drive supaya shrink bisa lebih besar.

### 5. Shrink Volume
1. Buka **Disk Management** (`Win + X → Disk Management`).
2. Klik kanan drive → **Shrink Volume**.
3. Sekarang angka shrink maksimal akan lebih besar dari sebelumnya.

### 6. Setelah selesai
- Aktifkan kembali pagefile, hibernation, dan system restore sesuai kebutuhan.
- Restart komputer jika perlu.

> Catatan: Jika Windows masih membatasi, bisa pakai **software pihak ketiga** (MiniTool Partition Wizard / AOMEI Partition Assistant) untuk memindahkan file yang “locked” dan shrink lebih besar.
