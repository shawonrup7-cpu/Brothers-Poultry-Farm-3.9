# ব্রাদার্স পোল্ট্রি ফার্ম (Brothers Poultry Farm)

পোল্ট্রি ফার্মের হিসাব-নিকাশ PWA অ্যাপ (অফলাইনে চলে)।

## GitHub Pages-এ দেওয়ার নিয়ম
1. এই ফোল্ডারের সব ফাইল (`.nojekyll` ও `.well-known` সহ) repo-র মূল ফোল্ডারে আপলোড করুন।
2. Settings → Pages → Branch: `main` / `(root)` → Save।
3. অ্যাপ খুলবে: https://shawonrup7-cpu.github.io/Brothers_Poultry_Farm-3.9/

## Android অ্যাপ (PWABuilder)
- `.well-known/assetlinks.json` ফাইলটি অবশ্যই ডোমেইনের একদম মূলে থাকতে হবে:
  `https://shawonrup7-cpu.github.io/.well-known/assetlinks.json`
  তাই এটি `shawonrup7-cpu.github.io` নামের আলাদা repo-তে রাখতে হবে (শুধু তাহলেই Play Store অ্যাপে ঠিকানা-বার লুকাবে)।
- `signing.keystore` ও `signing-key-info.txt` কখনো GitHub-এ দেবেন না। নিরাপদ জায়গায় রাখুন।
