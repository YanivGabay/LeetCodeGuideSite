---
layout: default
title: "LeetCode Guide"
---

# 🌍 LeetCode Beginner's Guide

<div id="content-he" style="direction: rtl;">

# 🌍 מדריך למתחילים בליטקוד

</div>

<div style="text-align: center; margin: 20px 0;">
<button onclick="setLanguage('en')">🇺🇸 English</button>
<button onclick="setLanguage('he')">🇮🇱 עברית</button>
</div>

<!-- English Content -->
<div id="content-en" markdown="1">
  {% include content-en.md %}
</div>
<!-- Hebrew Content -->
<div id="content-he" style="display:none; direction: rtl;" markdown="1">
  {% include content-he.md %}
</div>



## 🚀 Conclusion

We hope this guide has provided you with a **solid foundation** to begin your LeetCode journey! 🎯  
Remember, **LeetCode is just a tool**—a way to improve your problem-solving skills, prepare for coding interviews, and grow as a software engineer. Keep practicing, stay consistent, and enjoy the process! 💪

---

## 🤝 Contribute to the Guide

Have suggestions, corrections, or new content ideas? We'd love your contributions!  
📌 Check out our repository on **GitHub**:  
[👉 Contribute Here](https://github.com/YanivGabay/LeetCodeGuideSite)

---

## 📅 Stay Consistent with Daily LeetCode Reminders! 📢

Join our **WhatsApp group** where we post **daily easy LeetCode questions** to help keep you on track.  
We’re here to **remind and motivate you daily**! 🚀  

📲 **[Join the WhatsApp Group](https://chat.whatsapp.com/IQ3Mghl3NUz09vIdR0t4gd)**

---

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

---

🚀 **Happy Coding & Good Luck with Your LeetCode Journey!** 🎯💻

---


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
</script>



