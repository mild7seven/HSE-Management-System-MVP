# HSE Management System — MVP

PWA standalone untuk factory/warehouse.

## Implemented
- Login demo + RBAC dasar
- Dashboard KPI
- SBO: Safe Behavior / Unsafe Act / Unsafe Condition
- Kategori bahaya
- Immediate action
- Foto evidence via camera/gallery
- Finding otomatis dari Unsafe Act/Unsafe Condition
- Corrective Action
- Assign PIC + due date
- Workflow OPEN → ASSIGNED → IN_PROGRESS → SUBMITTED → VERIFICATION → CLOSED / REJECTED
- Verification dan rejection
- Offline-first local persistence menggunakan IndexedDB
- Outbox/sync queue dasar
- PWA Service Worker

## Demo login
- admin / admin123
- hse / hse123
- supervisor / supervisor123
- worker / worker123
- security / security123

Catatan: ini MVP frontend standalone. Endpoint backend REST dan PostgreSQL belum diaktifkan. Data demo disimpan lokal di browser.

## Jalankan
Karena Service Worker membutuhkan secure context, jalankan melalui HTTPS atau localhost.

Contoh:
```bash
python -m http.server 8080
```
Lalu buka `http://localhost:8080`.

Untuk GitHub Pages, upload seluruh isi folder ini ke repository dan aktifkan Pages.
