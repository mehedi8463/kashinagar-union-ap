কাশিনগর ইউনিয়ন Android অ্যাপ — প্রাথমিক নমুনা

এই প্রজেক্টে রয়েছে:
- ইউনিয়নের পরিচিতি
- নোটিশ ও খবর
- জনপ্রতিনিধিদের তথ্য
- যোগাযোগ
- ছবি ও গ্যালারি (এখন placeholder)

GitHub-এ যোগ করার নিয়ম:
1. ZIP ফাইলটি ফোনে ডাউনলোড করে Extract করুন।
2. GitHub-এ mehedi8463/kashinagar-union-apk রিপোজিটরি খুলুন।
3. Add file > Upload files নির্বাচন করুন।
4. Extract করা ফোল্ডারের ভেতরের সব ফাইল/ফোল্ডার আপলোড করুন; শুধু ZIP আপলোড করবেন না।
5. Commit changes করুন।
6. Actions ট্যাব > Build Kashinagar Union APK workflow-তে গিয়ে build শেষ হওয়া পর্যন্ত অপেক্ষা করুন।
7. সবুজ টিক এলে run-এ ঢুকুন। নিচের Artifacts থেকে KashinagarUnion-APK ডাউনলোড করুন।
8. ZIP খুললে app-debug.apk পাবেন। Android-এ ইনস্টল করতে হলে ডাউনলোড করা APK-টি খুলুন।

গুরুত্বপূর্ণ:
- এই APK প্রাথমিক নমুনা; প্রকৃত ইউনিয়নের তথ্য এখনো বসানো হয়নি।
- Workflow নিজে APK বানাতে পারে না যদি app source files না থাকে। এই ZIP-এ সেই প্রয়োজনীয় ফাইলগুলো আছে।
- Android Studio-তে compile করার সময় SDK/Gradle সেটআপ আলাদা লাগতে পারে; GitHub Actions workflow সেটি পরিচালনা করবে।
