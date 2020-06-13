## एक घेरा बनाएँ

The design uses six interlocking hoops in the centre, and a larger hoop around the outside. झुमका का व्यास 4cm है, साथ ही लटकना के लिए घेरा। यह 2mm मोटी है, इसलिए यह बहुत जल्दी 3D प्रिंट करेगा।

सबसे पहले, एक आंतरिक घेरा बनाएं।

--- task ---

BlocksCAD editor को वेब ब्राउज़र (web browser) में खोलें [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){:target="_blank"}.

3D चीज़ों को बनाने के लिए कोड लिखने के लिए आप ब्लॉक को ड्रैग और ड्रॉप कर सकते हैं।

--- /task --- --- task ---

एक `cylinder` बनाएं जिसका त्रिज्या `12` है और ऊंचाई `2` है (यहां इकाई mm है)।

![स्क्रीनशॉट](images/pendant-cylinder.png)

`Cylinders` are automatically centred along the X and Y axes. `not centered` को चुनें ताकि झुमका सतह पर बैठ जाए। (इसका अर्थ है कि Z- अक्ष का मान 0 से बड़ा है)।

परिणाम देखने के लिए अपने कोड में प्रत्येक परिवर्तन के बाद **Render** बटन पर क्लिक करें।

--- /task --- --- task ---

अब, केंद्र से एक छोटा `cylinder` निकालने के लिए `difference`{:class="blockscadsetops"} का उपयोग करें। यह एक घेरा बनाता है:

![स्क्रीनशॉट](images/pendant-hoop.png)

यदि आप चाहें, तो आप viewer में उपयोग किए जाने वाले रंग को बदलने के लिए रंगीन वर्ग पर क्लिक कर सकते हैं। यह आपके झुमका के रंग को प्रभावित नहीं करता है, क्योंकि यह आपके द्वारा उपयोग किए जाने वाले फिलामेंट के रंग पर निर्भर करता है।

--- /task ---
	
	
