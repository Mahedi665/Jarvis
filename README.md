# JARVIS - Native Android AI Voice Assistant
Package: com.mahedi.jarvis
Architecture: Kotlin + Jetpack Compose + Material 3
AI: Gemini AI Integration
Languages: Bengali (Bangladesh bn-BD) & English (US en-US)

## Android Phone Build Instructions (ফোন দিয়ে বিল্ড করার নিয়ম):

1. আপনার ফোনে Termux ইনস্টল করুন।
2. এই প্রজেক্টটি আনজিপ করুন:
   unzip JARVIS-Android-Project.zip -d ~/jarvis
3. বিল্ড করুন:
   cd ~/jarvis/JARVIS-Android-com.mahedi.jarvis
   chmod +x gradlew
   ./gradlew assembleDebug

APK লোকেশন:
app/build/outputs/apk/debug/app-debug.apk
