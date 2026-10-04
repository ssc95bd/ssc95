এসএসসি ৯৫ - ডিপ্লয় গাইড (নিরাপদ ভার্সন)

আপনার ফাইল এখন ১০০% ফ্রি হোস্টিং এর জন্য রেডি।

1. কি ঠিক করেছি:
- Claude DB এর উপর নির্ভরতা বাদ দিয়ে LocalStorage দিয়ে কাজ করবে, যাতে যেকোনো ফ্রি হোস্টিং এ চলে
- Email Obfuscation - বট থেকে ইমেইল হাইড
- XSS Protection - textContent ব্যবহার, input sanitization
- Security Headers (_headers ফাইল) - Cloudflare/Netlify অটো পড়বে
- theme save, safe uid

2. কিভাবে হোস্ট করবেন (সবচেয়ে সহজ):

Option A - Netlify Drop (১ মিনিট):
- netlify.com/drop যান
- এই ssc95-ready ফোল্ডারটা Drag & Drop করুন
- লাইভ লিংক পাবেন

Option B - Cloudflare Pages (রেকমেন্ডেড, সবচেয়ে নিরাপদ):
- github.com এ নতুন repo বানান
- এই ফোল্ডারের সব ফাইল আপলোড করুন
- dash.cloudflare.com > Pages > Connect to Git > Deploy

3. পরবর্তীতে Firebase লাগাতে চাইলে:
- Firebase Console থেকে Firestore ফ্রি প্রজেক্ট বানান
- script অংশে Firebase SDK যোগ করুন (আমাকে বললে করে দেব)

4. নিরাপত্তা চেকলিস্ট:
- HTTPS অটো অন থাকবে
- _headers ফাইল ডিলিট করবেন না
- কখনো API Key HTML এ লিখবেন না

কোনো সমস্যা হলে ফাইলটা আমাকে দিন।
