---
layout: default
title: "LeetCode Guide"
---

<div style="text-align: center; margin: 20px 0;">
<button onclick="setLanguage('en')">English</button>
<button onclick="setLanguage('he')">עברית</button>
</div>

<!-- Hebrew Content -->

<div id="content-he" class="lang-he" style="display: none; direction: rtl;" markdown="1">

  {% include content-he.md %}

  ## 🚀 בהצלחה 🎯
  לכל שאלה ניתן לפנות ולעדכן בגיטהב.

  ## 🤝 לתרום דרך גיטהאב
  אם יש לכם הצעות, תיקונים או רעיונות לתוכן חדש, אשמח שתתרמו גם לקוד.
  כנסו לקישור ותוכלו לראות את הקוד ולתרום דרך גיטהאב.
  [👉 לתרום כאן](https://github.com/YanivGabay/LeetCodeGuideSite)

## 📅 רוצים תזכורת יומית ? 📢

הצטרפו לקבוצת הוואטסאפ שלנו, שם אנחנו מפרסמים שאלות קלות באופן יומי כתזכורת.

📲 **[הצטרפו לקבוצת הוואטסאפ](https://chat.whatsapp.com/IQ3Mghl3NUz09vIdR0t4gd)**


## 🌍 רוצים לבנות אתר כמו זה?

המדריך הזה נבנה במרקדאון והומר לאתר ע"י ג'קיל.
האתר נבנה בעזרת ערכת העיצוב Minimal כדי לשמור על ניקיון ופשטות.

🎨 **ערכת העיצוב שנמצאת בשימוש:** [Minimal]( https://github.com/pages-themes/minimal)

רוצים ללמוד איך בונים אתר כזה? כנסו לקישורים הבאים:

📖 **מדריכים שימושיים:**
- 📌 **[יצירת אתר ב-GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)**  
  *(תיעוד רשמי של GitHub)*

- 🎓 **שיעור חינמי באינטרנט (בעברית) עם גאבור סבו - יצירת אתר ב-GitHub Pages בעזרת Markdown**  
    *(בשעה אחת, תוכלו ללמוד איך ליצור אתר בסיסי כמו זה!)*
  📅 **7 בפברואר, 2025**
  🔗 **[הרשמה כאן](https://www.meetup.com/pyweb-il/events/305773690/)**




</div>



<!-- English Content -->
<div id="content-en" class="lang-en" markdown="1">
  
  {% include content-en.md %}



  ## 🚀 Good luck 🎯
  for any questions feel free to contact me.

  ## 🤝 Contribute to the Guide

Have suggestions, corrections, or new content ideas? We'd love your contributions!  
📌 Check out our repository on **GitHub**:  
[👉 Contribute Here](https://github.com/YanivGabay/LeetCodeGuideSite)



## 📅 Stay Consistent with Daily LeetCode Reminders! 📢

Join our **WhatsApp group** where we post **daily easy LeetCode questions** to help keep you on track.  
We’re here to **remind and motivate you daily**! 🚀  

📲 **[Join the WhatsApp Group](https://chat.whatsapp.com/IQ3Mghl3NUz09vIdR0t4gd)**


## 🌍 About This Site

This guide was **built in Markdown** and converted to **HTML using Jekyll**.  
We use the **Minimal theme** to keep things clean and simple.  

🎨 **Theme Used:** [Minimal](https://github.com/pages-themes/minimal)  

Want to learn how this site was created and deployed? Check out these resources:  

📖 **Helpful Resources:**
- 📌 **[Create a GitHub Pages Site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)**  
  *(Github official documentation)*
  
- 🎓 **Free Online Lesson (In Hebrew) with Gabor Sabo - Creating a website on GitHub Pages using Markdown**  
    *(In 1 hour, you can learn how to create a basic website like this one!)*
  📅 **February 7th, 2025**  
  🔗 **[Register Here](https://www.meetup.com/pyweb-il/events/305773690/)**  


</div>






<!-- JavaScript for Language Toggling -->
<script>
  function setLanguage(lang) {
    if (lang === 'he') {
      document.getElementById("content-en").style.display = "none";
      document.getElementById("content-he").style.display = "block";
    } else {
      document.getElementById("content-en").style.display = "block";
      document.getElementById("content-he").style.display = "none";
    }
  }

  // Set default language on page load
  document.addEventListener("DOMContentLoaded", function() {
    // You can set the default language here. For example, default to English:
    setLanguage('he');

    
  });
</script>

