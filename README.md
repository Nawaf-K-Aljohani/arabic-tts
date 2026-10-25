# Arabic Text-to-Speech

**Speaks exactly what is written: every letter and every tashkeel (تشكيل) mark, as written.**

> This repository is a project showcase. The model and its source code are private.

## What makes it different

Most Arabic text-to-speech tools guess the tashkeel, or quietly "fix" it before speaking, so what you hear is not always what you wrote. This one reads the text **exactly as it is written**:

- **Correct tashkeel** is spoken as written.
- **Wrong tashkeel** is spoken as written too. Nothing is autocorrected.
- **Letters without tashkeel** are read as written, with no vowels guessed.
- **Similar letters are never merged:** ة and ه, ى and ي, أ and ا all keep their own sound.

This makes it useful wherever every mark matters: teaching, proofreading tashkeel, and hearing classical texts as they are written.

## Samples

Both spoken in my own voice.

### Sample 1: a sentence

https://github.com/user-attachments/assets/6d51e8ef-c2a6-4c31-869f-8bc9ead8589d

<div dir="rtl">

> وَقَدْ حَاوَلْتُ أَنْ أُسْهِمَ فِي هَٰذَا الْعِبْءِ، وَأَنْ أُضِيفَ إِلَى جُهُودٍ سَبَقَتْ جُهْدًا مُتَوَاضِعًا، رَاجِيًا أَنْ يَكُونَ لِي بِهِ شَرَفُ الْمُشَارَكَةِ فِي تَحْقِيقِ أَمَلِ هَٰذِهِ الْأُمَّةِ فِي أَبْنَائِهَا.

</div>

### Sample 2: classical prose (4 minutes)

«المقامة الخلفية» by Badi' al-Zaman al-Hamadhani, read from the vowelled text below:

https://github.com/user-attachments/assets/5178e822-00ea-46be-9a06-3dbfeea15b9a

<details>
<summary><b>Full text (as given to the model)</b></summary>

<div dir="rtl">

لَمَّا وَلِيتُ أَحْكَامَ البَصْرَةِ، وَانْحَدَرْتُ إِلَيْهَا عَنِ الحَضْرَةِ، صَحِبَنِي فِي المَرْكَبِ شَابٌّ كَأَنَّهُ العَافِيَةُ فِي البَدَنِ، فَقَالَ: إِنِّي فِي أَغْطَافِ الأَرْضِ وَأَطْرَافِهَا ضَائِعٌ، لَكِنِّي أَعُدُّ مُعَدَّ أَلْفٍ، وَأَقُومُ مَقَامَ صَفٍّ، وَهَلْ لَكَ أَنْ تَتَّخِذَنِي صَنِيعَةً، وَلاَ تَطْلُبَ مِنِّي ذَرِيعَةً؟ فَقُلْتُ: وَأَيُّ ذَرِيعَةٍ أَكَدُّ مِنْ فَضْلِكَ؟ وَأَيُّ وَسِيلَةٍ أَعْظَمُ مِنْ عَقْلِكَ؟

لاَ بَلْ أَخْدُمُكَ خِدْمَةَ الرَّفِيقِ، وَأُشَارِكُكَ فِي السَّعَةِ وَالضِّيقِ. وَسِرْنَا فَلَمَّا وَصَلْنَا البَصْرَةَ غَابَ عَنِّي أَيَّاماً، فَضِقْتُ لِغَيْبَتِهِ ذَرْعاً، وَلَمْ أَمْلِكْ صَبْراً، فَأَخَذْتُ أَفْتَشُ جُيُوبَ البَلَدِ حَتَّى وَجَدْتُهُ، فَقُلْتُ: مَا الَّذِي أَنْكَرْتَ؟ وَلِمَ هَجَرْتَ؟

فَقَالَ: إِنَّ الوَحْشَةَ تَقْدَحُ فِي الصَّدْرِ اِقْتِدَاحَ النَّارِ فِي الزَّنْدِ، فَإِنْ أُطْفِئَتْ نَارَتْ وَتَلاَشَتْ، وَإِنْ عَاشَتْ، طَارَتْ وَطَاشَتْ، وَالقَطْرُ إِذَا تَتَابَعَ عَلَى الإِنَاءِ اِمْتَلأَ وَفَاضَ، وَالعَتَبُ إِذَا تُرِكَ فَرَّخَ وَبَاضَ،

وَالحُرُّ لاَ يَعْلَقُهُ شَرَكٌ كَالَعَطَاءِ، وَلاَ يَطْرُدُهُ سَوْطٌ كَالجَفَاءِ، وَعَلَى كُلِّ حَالٍ، نَنظُرُ مِنْ عَالٍ، عَلَى الكَرِيمِ نَظَرَ إِذْلاَلٍ، وَعَلَى اللَّئِيمِ نَظَرَ إِذْلاَلٍ، فَمَنْ لَقِيَنَا بِأَنْفٍ طَوِيلٍ، لَقِينَاهُ بِخُرْطُومِ فِيلٍ، وَمَنْ لَحَظَنَا بِنَظَرٍ شَزْرٍ، بَعْنَاهُ بِثَمَنٍ نَزْرٍ، وَأَنْتَ لَمْ تَغْرِسْنِي لِتَقْتَلِعَنِي غُلاَمَكَ، وَلاَ اِشْتَرَيْتَنِي لِتَبِيعَنِي خُدَّامَكَ،

وَالْمَرْءُ مِنْ غِلْمَانِهِ، كَالْكِتَابِ مِنْ عُنْوَانِهِ، فَإِنْ كَانَ جَفَاؤُهُمْ شَيْئاً أَمَرْتَ بِهِ فَمَا الَّذِي أَوْجَبَ؟ وَإِنْ لَمْ تَكُنْ عَلِمْتَ بِهِ كَانَ أَعْجَبَ!! ثُمَّ قَالَ:

ظَفِرَتْ يَدَا خَلَفِ بْنِ أَحْمَدَ إِنَّهُ ... سَهْلُ الفِنَاءِ مُؤَدَّبُ الخُدَّامِ أَوْ مَا رَأَيْتَ الجُودَ يَجْتَازُ الوَرَى ... وَيَحُلُّ مِنْ يَدِهِ بِدَارِ مُقَامِ

قَالَ عِيسَى بْنُ هِشَامٍ: ثُمَّ أَعْرَضَ وَتَبِعْتُهُ أَسْتَعْطِفُهُ، وَمَا زِلْتُ أُلاَطِفُهُ حَتَّى اِنْصَرَفَ، بَعْدَ أَنْ حَلَفَ أَنْ لاَ أَوْرَذْتُ مِنْ أَسَاءَ عِشْرَتَهُ، فَوَهَبْتُ لَهُ حُرْمَتَهُ.

</div>
</details>

## Features

- Exact reading: letters and تشكيل as written
- No autocorrection of tashkeel or spelling
- Natural voice

---

<div dir="rtl">

### بالعربية

نموذج لتحويل النص العربي إلى كلام، ينطق النص كما هو مكتوب تمامًا، حرفًا وتشكيلًا:

- التشكيل الصحيح يُنطق كما كُتب.
- التشكيل الخاطئ يُنطق كما كُتب أيضًا، دون أي تصحيح تلقائي.
- الحروف غير المشكّلة تُقرأ كما كُتبت، دون تخمين للحركات.
- لا يخلط بين الحروف المتشابهة: ة و ه، ى و ي، أ و ا.

عيّنتان صوتيتان أعلاه بصوتي: جملة قصيرة، و«المقامة الخلفية» لبديع الزمان الهمذاني كاملة.

</div>

---

<sub>Built by [Eng. Nawaf Aljohani](https://github.com/Nawaf-K-Aljohani) · [LinkedIn](https://www.linkedin.com/in/nawaf-aljohani-862a2025b/)</sub>
