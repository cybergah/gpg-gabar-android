<div align="center">

<img src="image%20(4).jpg" alt="GPG Gabar" width="720" />

</div>

# GPG Gabar

**OpenPGP encryption for Android** · [Kurmancî](README.md)

GPG Gabar is an Android app built on the worldwide PGP/OpenPGP standard. It lets
you encrypt your texts and files with strong security and decrypt them whenever
you need to.

## Key features

- Encrypt and decrypt text
- Encrypt files (with the `.gpg` extension) and decrypt them (`.gpg` / `.pgp`)
- Generate PGP keys
- Import keys from `.asc` files (public and secret keys)
- Export keys (public key only, or public + secret key)
- Manage keys inside the app (list, delete)
- Multiple languages (Kurmanji, Turkish, English and more)
- Encrypt and decrypt directly from the Android "Share" menu

## Tech stack

- **Language & UI:** Kotlin, Jetpack Compose, Material 3
- **Cryptography:** Bouncy Castle (`bcprov`, `bcpg`)
- **Data protection:** SQLCipher + AndroidX Security (EncryptedSharedPreferences)
- **Min SDK:** 24
- **Target/Compile SDK:** 36

## Security notes

- The app enforces a very long key passphrase (at least 100 characters).
- Release signing files (`signing/`, `keystore.properties`, `.jks`) are **never**
  committed to the repository.
- Local files such as `local.properties`, `.idea/` and `build/` are not committed.

## Getting started

### Requirements

- Android Studio (latest version)
- JDK (the one bundled with Android Studio is enough)
- Android SDK (minSdk 24 or higher)

### Setup

```bash
git clone https://github.com/cybergah/gpg-gabar-android.git
cd gpg-gabar-android
```

Then open the project in Android Studio and run it on a device or emulator.

## License

[MIT](LICENSE)

---

<div align="center">

A [**Cybergah**](https://cybergah.com/) project

</div>
