# AGS MedHub Desktop Downloads

This public repository is reserved for official Windows and macOS installer binaries, SHA-256 checksum files, release notes, and installation guidance. It contains no AGS MedHub application source code.

## Downloads / التنزيلات

No installer release is published yet. Direct download links will be added only after acceptance is complete and the owner approves publication. Do not install or redistribute a private GitHub Actions artifact.

لا توجد ملفات تثبيت منشورة حاليًا. ستُضاف روابط التنزيل المباشرة بعد اكتمال الاختبارات وموافقة المالك على النشر. لا تثبّت أو تعِد توزيع ملفات CI الخاصة.

## Unsigned installer guidance / إرشادات التثبيت للنسخ غير الموقّعة

These installers are planned to be unsigned. Windows may show Microsoft Defender SmartScreen, and macOS may show a Gatekeeper warning. First confirm the download came from an official AGS MedHub release and verify its SHA-256 against the checksum published beside that exact file. If the verified installer triggers an operating-system warning, use only the operating system's documented, per-app confirmation. Do not disable antivirus, SmartScreen, Gatekeeper, or other system protections globally.

المثبتات المخطط نشرها غير موقّعة؛ قد يعرض Windows تحذير Microsoft Defender SmartScreen، وقد يعرض macOS تحذير Gatekeeper. قبل التثبيت، تأكد أن الملف من إصدار AGS MedHub الرسمي، ثم طابق SHA-256 مع ملف التحقق المنشور بجانب الملف نفسه. إذا ظهر تحذير بعد التحقق من المصدر والبصمة، استخدم خيار التأكيد الخاص بهذا التطبيق فقط من النظام. لا تعطّل مضاد الفيروسات أو SmartScreen أو Gatekeeper أو أي حماية للنظام بشكل عام.

### Windows

1. Download the official `.exe` after it is published and verify its adjacent `.sha256` file.
2. Run the installer. If SmartScreen appears, check the source and checksum first; use **More info** → **Run anyway** only when both match the official release. Otherwise cancel.

### macOS (Apple Silicon)

1. Open the official `.dmg` and drag AGS MedHub to Applications. Verify its published SHA-256 first.
2. If Gatekeeper blocks this unsigned app, confirm its source and checksum, then use the app-specific **Open Anyway** option in Privacy & Security. Do not disable Gatekeeper globally.

## Planned platform targets

- Windows 10/11, x64, NSIS `.exe`
- macOS Apple Silicon, `.dmg`
