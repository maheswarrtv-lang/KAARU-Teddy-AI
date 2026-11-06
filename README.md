# KAARU Teddy Flutter starter

- Entry point: `lib/main.dart` (includes `void main()`).
- `assets/kaaru_teddy.glb` is currently a PLACEHOLDER cube. Replace it with your real teddy 3D model (same file name).
- The `android/` folder is generated automatically by the GitHub workflow (`flutter create`), and the manifest is patched with INTERNET permission for the 3D viewer.
- Chat reply is a placeholder; Gemini Worker and voice are not connected yet.
- Keep Gemini API keys in Cloudflare Worker secrets, never inside Flutter source.
- Build online: push to GitHub `main` (or run "Build Android APK" manually) and download the `kaaru-teddy-apk` artifact.
- Build locally: `flutter create --platforms=android .` then `flutter pub get` then `flutter build apk --release`.
