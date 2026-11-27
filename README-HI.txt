SK BAJAJ WEBSITE — हिंदी निर्देश
================================

इस पैकेज में:
1. index.html     — मुख्य वेबसाइट
2. admin.html     — बाइक जोड़ने, एडिट करने और हटाने का Admin Panel
3. bikes.json     — बाइक/स्कूटर का डेटा
4. README-HI.txt  — ये निर्देश

GitHub पर अपलोड:
1. ZIP Extract करें।
2. GitHub में अपनी Sk-Bajaj-NTN Repository खोलें।
3. चारों फाइलें Repository के मुख्य/root folder में अपलोड करें।
4. पुरानी फाइलें हों तो Replace करें।
5. GitHub Pages चालू/अपडेट करें (Settings > Pages)।
6. वेबसाइट index.html से खुलेगी और Admin Panel के लिए admin.html लिंक दबाएँ।

Admin Panel कैसे इस्तेमाल करें:
1. admin.html खोलें।
2. बाइक जोड़ें या मौजूदा बाइक Edit/Delete करें।
3. बदलाव ब्राउज़र के localStorage में सेव होते हैं।
4. "बाइक JSON डाउनलोड करें" दबाएँ।
5. डाउनलोड हुई bikes.json को GitHub Repository के root folder में पुरानी bikes.json की जगह अपलोड करें।
6. कुछ समय बाद वेबसाइट रिफ्रेश करें।

महत्वपूर्ण:
- index.html, admin.html और bikes.json एक ही folder में होने चाहिए।
- fetch() के कारण index.html को सीधे file:// से खोलने पर डेटा लोड न हो; GitHub Pages या किसी local web server से खोलें।
- Admin Panel में पासवर्ड सुरक्षा नहीं है। इसे सार्वजनिक वेबसाइट पर संवेदनशील/अनधिकृत बदलावों से सुरक्षित न मानें।
- फोटो के लिए सार्वजनिक रूप से उपलब्ध image URL डालें।
- अपलोड की गई bikes.json में शुरुआती 8 मॉडल हैं; यह पूरी 38-बाइक सूची नहीं है।
- Admin Panel में बदलाव वेबसाइट पर अपने-आप प्रकाशित नहीं होते; नई bikes.json GitHub पर अपलोड करनी होती है।
