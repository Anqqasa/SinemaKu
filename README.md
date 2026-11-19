# SinemaKu

Aplikasi streaming film & serial pribadi — fork dari
[CloudStream](https://github.com/recloudstream/cloudstream) (v4.9.1) yang
diganti nama menjadi **SinemaKu**.

## Yang berbeda dari CloudStream

- Nama aplikasi **SinemaKu**, package `com.panji.sinemaku` — bisa dipasang
  berdampingan dengan aplikasi CloudStream resmi.
- Ikon launcher, banner TV, dan ikon notifikasi baru.
- Repositori **CloudX** (Moviebox, Idlix, dll.) sudah terpasang bawaan,
  jadi provider langsung tersedia tanpa tambah repo manual.
- In-app updater dimatikan — fork ini tidak diupdate dari rilis
  CloudStream resmi (beda package).

## Build

Butuh JDK 17 dan Android SDK (compileSdk 37, build-tools 36.0.0):

```sh
./gradlew assembleStableDebug
```

APK hasil build ada di `app/build/outputs/apk/stable/debug/`.

## Lisensi

GPL-3.0 — lihat file `LICENSE`. Kode asli © para kontributor CloudStream.
