JANAPAD USER — Android WebView APK Project

এই প্যাকেজে Android wrapper project এবং আপনার HTML app assets রাখা আছে।
এখানে সরাসরি APK compile করা হয়নি কারণ এই পরিবেশে Android SDK/Gradle নেই।

APK বানানোর সহজ cloud পদ্ধতি:
1) ZIP unzip করে JANAPAD_USER ফোল্ডার GitHub repository-তে upload করুন।
2) GitHub repository-র Actions tab খুলুন।
3 Build JANAPAD USER APK workflow চালান (Run workflow) অথবা main branch-এ push হলে নিজে চলবে।
4) workflow শেষ হলে Artifacts থেকে JANAPAD-USER-debug-apk ডাউনলোড করুন।

Local build:
Android Studio দিয়ে project open করে Gradle sync, তারপর Build > Build APKs.

বিঃদ্রঃ APK-এর HTML app এখন local prototype. Firebase login/Firestore online backend এখনো যুক্ত করা হয়নি।
