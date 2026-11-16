GitHub দিয়ে APK তৈরি করার নির্দেশনা

1. GitHub-এ নতুন repository তৈরি করুন; নাম NagadDemo দিন।
2. এই ZIP extract করুন।
3. Extract করা NagadDemoAndroid ফোল্ডারের ভেতরের সব ফাইল ও .github ফোল্ডার repository-র root-এ upload করুন।
   খেয়াল রাখুন: settings.gradle যেন repository-র root-এ থাকে; NagadDemoAndroid নামে আরেকটি nested folder যেন না থাকে।
4. Commit changes করুন।
5. Repository-র Actions tab খুলুন।
6. Build Nagad Demo APK workflow চালু/চালাতে Run workflow চাপুন (প্রথম push-এও স্বয়ংক্রিয়ভাবে চলবে)।
7. Build সফল হলে workflow run খুলে নিচের Artifacts অংশ থেকে NagadDemo-debug-apk ডাউনলোড করুন।
8. ZIP extract করে app-debug.apk ইনস্টল করুন।

নোট:
- এটি একটি অনানুষ্ঠানিক ডেমো অ্যাপ; আসল Nagad অ্যাপ নয়।
- কোনো বাস্তব টাকা, অ্যাকাউন্ট, OTP, PIN বা পেমেন্ট সার্ভিসের সাথে যুক্ত নয়।
- APK ইনস্টল করার আগে Android-এ অজানা উৎস থেকে অ্যাপ ইনস্টল করার অনুমতি চাইতে পারে।
