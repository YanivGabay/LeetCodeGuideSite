---
layout: default
title: "LeetCode Guide"
---

# 🌍 LeetCode Beginner's Guide

<div id="content-he" style="direction: rtl;">

# 🌍 מדריך למתחילים בליטקוד

</div>

<div style="text-align: center; margin: 20px 0;">
  <button onclick="switchLanguage('en')">🇺🇸 English</button>
  <button onclick="switchLanguage('he')">🇮🇱 עברית</button>
</div>

<div id="content-en">

## 🎓 Welcome to LeetCode Guide

Welcome to the **LeetCode Beginner's Guide**! This guide is designed for students who have **never used LeetCode** before and want to start utilizing the platform effectively.

- **Technical Focus:** Learn how to use the website, navigate its features, and interact with coding problems.
- **No Coding Algorithms:** This guide does **not** cover algorithms or actual coding solutions.

---

## 💡 Why We Solve and Its Importance for New Grads

LeetCode has become a **comprehensive resource** for **coding interview questions**.

### 🔍 Key Benefits:
- **Interactive Testing:** Run and test your code directly on the platform.
- **Edge Case Handling:** Test your solutions against various edge cases.
- **Community Solutions:** View, post, and discuss solutions with others.

### 🎯 Importance for Aspiring Software Engineers:
- **Interview Preparation:** Essential for preparing for coding interviews in the tech industry.
- **Curated Lists:** Access summary lists of the most **important questions** (e.g., *Neetcode 150*, *Top 100 LeetCode Questions*).

---

## ⚙️ How LeetCode Works

### 🛠️ Getting Started

1. **Create an Account:**
   - Visit [LeetCode](https://leetcode.com) and sign up for a free account.
   - ![First time you're not logged in](images/image.png)

2. **Sign In via GitHub:**
   - Click **Sign In** and choose the GitHub option for a streamlined login process.
   - ![Sign-In Options](images/image-1.png)
   - ![Login via GitHub](images/image-2.png)

3. **Logged-In Homepage:**
   - Once logged in, your homepage will display various navigation options.
   - ![Basic LeetCode Page](images/image-3.png)

### 🧭 Navigating the Platform

![Navigation Bar](images/image-4.png)

LeetCode offers several key sections:

- **🔍 Explore:**
  - Browse questions categorized visually by different topics.
  - ![Explore Page](images/image-5.png)

- **📚 Problems:**
  - Access a comprehensive list of coding problems.
  - **Filters Available:**
    - **Difficulty:** Easy, Medium, Hard
    - **Tags:** Array, String, Tree, SQL, etc.
  - ![Problem Page](images/image-6.png)
  - ![Bottom of Problem Page](images/image-7.png)

- **🏆 Contests:**
  - Participate in weekly coding contests.
  - View upcoming, ongoing, and past contests.

- **💬 Discuss:**
  - Engage with the community through forums.
  - Ask questions and view discussions.

- **🗣️ Interview:**
  - Simulate real interview scenarios.
  - *(Note: This feature is less popular compared to others.)*

---

## 📝 How to Select a Question

1. **Navigate to Problems:**
   - Go to the **Problems** section.

2. **Filter by Difficulty:**
   - Select **Easy** to start with manageable problems.
   - ![Pressing Easy](images/image-8.png)

3. **Daily Challenge:**
   - The first question is the **Daily Challenge**.
   - Solve it daily to build a streak, visible on your profile.
   - ![Daily Challenge](images/image-9.png)

4. **Explore the List:**
   - ![Problems List](images/image-10.png)
   - **Status:** Indicates if you've solved the problem.
   - **Acceptance Rate:** Percentage of users who solved it.
   - **Lock Icon:** Premium feature showing interview frequency and acceptance rate *(not recommended)*.

5. **Unsolved Problems:**
   - These problems are yet to be tackled.
   - ![Unsolved Problems](images/image-11.png)

---

## 🛠️ How to Solve a Question

1. **Select an Unsolved Problem:**
   - Click on a problem you haven't solved yet.
   - ![Merge Sorted Array](images/image-12.png)

2. **Understand the Problem Page:**
   - **Coding Area:** Write your code here.
     - ![Coding Area](images/image-13.png)
   - **Language Selection:** Choose your preferred programming language.
     - ![Language Selection](images/image-14.png)

   **Note:** LeetCode provides necessary libraries; no need to import them manually.

3. **Test Cases:**
   - ![Test Case Area](images/image-18.png)
   - You can edit the input values and run basic test cases.
   - Can add your own tests by pressing **+**.

4. **Submitting Your Solution:**
    - ![Run vs Submit](images/image-19.png)

   - **Run vs. Submit:**
     - **Run:** Quick checks with limited test cases.
     - **Submit:** Comprehensive testing and performance metrics.
   - **Post-Submission:**
     - View how your solution performs compared to others.
     - If successful, the problem is marked as **solved**.
     - ![Successful Submission](images/image-20.png)

5. **Problem Description:**
   - ![Problem Area](images/image-15.png)
   - **Tabs Available:**
     - **Description:** Problem statement and constraints.
     - **Editorial:** *(Premium feature, not recommended.)*
     - **Solutions:** Community solutions and discussions.
     - **Submissions:** Your past attempts and their performance.

6. **Viewing Solutions:**
   - ![Solutions Example](images/image-16.png)
   - Filter by language and explore different approaches.
   - ![Solution](images/image-17.png)
   - View explanations, code, and community comments.

---

## 💻 How to Interact with the Platform - Coding Area Notes

### 🖥️ Examples in C++ and Python

I will demonstrate how to use the coding area with **C++** and **Python**. Feel free to contribute examples in other languages!

---

### 🔷 C++

#### 📝 Function Signature Example

If you select the question [Two Sum](https://leetcode.com/problems/two-sum), you'll see the following function signature:

![Coding Area](images/image-22.png)

```cpp
class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        // Write your solution here
        // No need for main function, includes, or namespace std
    }
};
```

**Explanation:**
- **Object-Oriented:** The function is part of a class.
- **Simplified Setup:** No need to write `main()`, include statements, or use namespaces.

#### 🛠️ Running Locally (C++)

To run the code in your local environment:

1. **Create `main.cpp`:**

    ```cpp
    // In local environment, we need to include the libraries
    #include <vector>
    #include <iostream>
    
    // Add your using statements
    using std::vector;
    using std::cout;
    using std::endl;
    
    class Solution {
    public:
        vector<int> twoSum(vector<int>& nums, int target) {
            // Some code
        }
    };
    
    int main() {
        Solution sol; // Create an object named sol from the class Solution
        vector<int> nums = {2, 7, 11, 15}; // Input for the function
        int target = 9; // Target for the function
        vector<int> result = sol.twoSum(nums, target);
        
        // Do something with result
        for (int i = 0; i < result.size(); i++) {
            cout << result[i] << " ";
        }
    
        return 0;
    }
    ```

2. **Compile and Run:**
    ```sh
    g++ main.cpp -o main && ./main
    ```

**Note:**  
Outputs in the code will be shown in the test cases output area. Ensure to **remove print statements** before submitting, as they can affect performance metrics (LeetCode measures execution time).

**Example with Print Statement:**

```cpp
class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        cout << "hello";
        return vector<int>{2}; 
    }
};
```

- **Run Result:**
  ![Test Area](images/image-21.png)

---

### 🟢 Python

#### 📝 Function Signature Example

For the same question [Two Sum](https://leetcode.com/problems/two-sum), the Python function signature appears as:

![Python Function](images/image-23.png)

```python
class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
```

**Explanation:**
- **Object-Oriented:** The function is part of a class.
- **Simplified Setup:** No need to write `main()`, import statements, or handle namespaces.

#### 🛠️ Running Locally (Python)

To run the code in your local environment:

1. **Create `main.py`:**

    ```python
    class Solution(object):
        def twoSum(self, nums, target):
            """
            :type nums: List[int]
            :type target: int
            :rtype: List[int]
            """
            # Write your solution here
            # No need for main function, includes, or namespace std
            # Example of just returning [0, 1]
            return [0, 1]
    
    if __name__ == "__main__":
        sol = Solution()
        nums = [2, 7, 11, 15]
        target = 9
        result = sol.twoSum(nums, target)
        print(result)
    ```

2. **Run the Script:**
    ```sh
    python main.py
    ```

**Note:**  
Outputs in the code will be shown in the test cases output area. Ensure to **remove print statements** before submitting, as they can affect performance metrics (LeetCode measures execution time).

**Example with Print Statement:**

```python
class Solution(object):
    def twoSum(self, nums, target):
        print("hello")
        return [0, 1]
```

- **Run Result:**
  ![Python Test](images/image-24.png)

---


</div>

<div id="content-he" style="display:none; direction: rtl;">

## 🎓 ברוכים הבאים למדריך LeetCode

ברוכים הבאים ל**מדריך למתחילים בליטקוד**! מדריך זה נועד לסטודנטים שמעולם לא השתמשו בליטקוד ורוצים להתחיל להשתמש בפלטפורמה בצורה יעילה.

- **מיקוד טכני:** נלמד כיצד להשתמש באתר, לנווט בתכונות שלו.
- **אין אלגוריתמים :** מדריך זה **אינו** מכסה אלגוריתמים או פתרונות קוד בפועל.

---

## 💡 למה אנחנו פותרים ולמה זה חשוב  

ליטקוד הפך ל**משאב מקיף** ל**שאלות ראיונות קוד**.

### 🔍 יתרונות מרכזיים:
- **בדיקה אינטראקטיבית:** הרץ ובדוק את הקוד שלך ישירות על הפלטפורמה.
- **טיפול במקרים קצה:** בדוק את הפתרונות שלך נגד מגוון מקרים קצה.
- **קהילה:** צפה, פרסם ודון בפתרונות עם אחרים.

### 🎯 חשיבות למהנדסי תוכנה עתידיים:
- **הכנה לראיונות:** חיוני להכנה לראיונות קוד בתעשיית הטכנולוגיה.
- **רשימות מסוננות:** גישה לרשימות מסכמות של שאלות (למשל, *Neetcode 150*, *Top 100 LeetCode Questions*).

---

## ⚙️ כיצד LeetCode עובד

### 🛠️ התחלה

1. **צור חשבון:**
   - בקר ב-[LeetCode](https://leetcode.com) וצרו חשבון חינם.
   - ![פעם ראשונה שלא התחברת](images/image.png)

2. **אפשר גם ישירות להתחבר דרך GitHub:**
   - לחץ על **Sign In** ובחר באפשרות GitHub לתהליך התחברות יעיל.
   - ![אפשרויות התחברות](images/image-1.png)
   - ![התחברות דרך GitHub](images/image-2.png)

3. **דף הבית לאחר התחברות:**
   - לאחר ההתחברות, דף הבית יציג אפשרויות ניווט שונות.
   - ![דף LeetCode בסיסי](images/image-3.png)

### 🧭 ניווט בפלטפורמה

![סרגל ניווט](images/image-4.png)

ליטקוד מציע מספר חלקים מרכזיים:

- **🔍 Explore:**
  - דפדף בשאלות המסווגות ויזואלית לפי נושאים שונים.
  - ![דף Explore](images/image-5.png)

- **📚 Problems:**
  - גש לרשימה מקיפה של בעיות קוד.
  - **מסננים זמינים:**
    - **קושי:** קל, בינוני, קשה
    - **תגיות:** Array, String, Tree, SQL, וכו'
        - אופציה זו מומלצת לסטודנטים שעדיין לא מכירים את כל האפשרויות, לדוגמא סננו לפי Array.
  - ![דף Problems](images/image-6.png)
  - ![תחתית דף Problems](images/image-7.png)

- **🏆 Contests:**
  - השתתף בתחרויות קידוד שבועיות.
  - צפה בתחרויות הקרבות, הנוכחיות והעבר.

- **💬 Discuss:**
  - התחבר עם הקהילה דרך פורומים.
  - שאל שאלות וצפה בדיונים.

- **🗣️ Interview:**
  - הדמיה של סצנות ראיון אמיתי.
  - *(הערה: תכונה זו פחות פופולרית בהשוואה לאחרים.)*

---

## 📝 כיצד לבחור שאלה

1. **גש ל-Problems:**
   - לחצו על **Problems**.

2. **סנן לפי קושי:**
   - מומלץ להתחיל בבעיות **קלות** אם אתם מתחילים.
   - ![לחיצה על Easy](images/image-8.png)

3. **אתגר יומי:**
   - השאלה הראשונה היא **אתגר יומי**.
   - פתרו אותה מדי יום לבניית רצף, הנראה בפרופיל שלך.
   - ![אתגר יומי](images/image-9.png)

4. **דפדוף ברשימה:**
   - ![רשימת בעיות](images/image-10.png)
   - **סטטוס:** מציין אם פתרתם את הבעיה.
   - **שיעור קבלה:** אחוז המשתמשים שפתרו אותה.
   - **סמל נעילה:** תכונה פרימיום המציגה תדירות ראיון ושיעור קבלה *(לא מומלץ)*.

5. **בעיות שלא פותרו:**
   - אלו הן הבעיות שטרם התמודדת איתן.
   - אין להם סימון ירוק בצד שמאל.
   - ![בעיות שלא פותרו](images/image-11.png)

---

## 🛠️ כיצד לפתור שאלה

1. **בחר בעיה שלא פתרתם:**
   - לחץ על בעיה שטרם פתרתם.
   - ![Merge Sorted Array](images/image-12.png)

2. **הבן את דף השאלה:**
   - **אזור הקוד:** כתבו את הקוד שלכם כאן.
     - ![אזור הקוד](images/image-13.png)
   - **בחירת שפה:** בחר את שפת התכנות המועדפת עליך.
     - ![בחירת שפה](images/image-14.png)

   **הערה:** ליטקוד מספק את הספריות הנדרשות; אין צורך לייבא אותן ידנית.

3. **מבחני קלט:**
   - ![אזור מבחני קלט](images/image-18.png)
   - אתם יכולים לערוך את הטסטים או להוסיף טסטים משלכם.


4. **שליחת הפתרון שלך:**
    - ![הפעל מול שליחה](images/image-19.png)
   - **Run מול Submit:**
     - **Run:** בדיקות מהירות עם מספר מוגבל של מבחנים.
     - **Submit:** בדיקות מקיפות ומדדי ביצועים.
   - **לאחר השליחה:**
     - צפה כיצד הפתרון שלך מתמודד מול אחרים.
     - אם הצלחת, הבעיה תסומן כ**נפתרה**.
     - ![הגשה מוצלחת](images/image-20.png)

5. **תיאור הבעיה:**
   - ![אזור הבעיה](images/image-15.png)
   - **כרטיסיות זמינות:**
     - **Description:** ניסוח הבעיה והגבלות.
     - **Editorial:** *(תכונה פרימיום, לא מומלץ.)*
     - **Solutions:** פתרונות בפורום קהילתי ודיונים.
     - **Submissions:** ניסיונות קודמים שלכם וביצועיהם.

6. **צפייה בפתרונות:**
   - סינון לפי שפה וחקור גישות שונות.
   - ![דוגמת פתרונות](images/image-16.png)
   - לחיצה על אחד הפתרונות תציג הסברים, קוד ותגובות מהקהילה.
   - ![פתרון](images/image-17.png)


---

## 💻 כיצד להתפעל עם הפלטפורמה - הערות על אזור הקוד

### 🖥️ דוגמאות ב-C++ ו-Python

אני אראה כיצד להשתמש באזור הקוד עם **C++** ו-**Python**. אתם מוזמנים לתרום דוגמאות בשפות נוספות!

---

### 🔷 C++

#### 📝 דוגמת חתימת פונקציה

אם תבחרו בשאלה [Two Sum](https://leetcode.com/problems/two-sum), תראו את חתימת הפונקציה הבאה:

![אזור קידוד](images/image-22.png)

<div style="direction: ltr;">

```cpp
class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        // Write your solution here
        // No need for main function, includes, or namespace std
    }
};
```

</div>

**הסבר:**
- **תכנות מונחה עצמים:** הפונקציה היא חלק ממחלקה.
- **הגדרה פשוטה:** אין צורך לכתוב `main()`, הצהרות include, או להשתמש ב-namespace.

#### 🛠️ הרצת הקוד מקומית (C++)

כדי להריץ את הקוד בסביבה המקומית שלך:

1. **צור `main.cpp`:**

<div style="direction: ltr;">

```cpp
    // In local environment, we need to include the libraries
    #include <vector>
    #include <iostream>

    // Add your using statements
    using std::vector;
    using std::cout;
    using std::endl;

    class Solution {
    public:
        vector<int> twoSum(vector<int>& nums, int target) {
            // Some code
        }
    };

    int main() {
        Solution sol; // Create an object named sol from the class Solution
        vector<int> nums = {2, 7, 11, 15}; // Input for the function
        int target = 9; // Target for the function
        vector<int> result = sol.twoSum(nums, target);
        
        // Do something with result
        for (int i = 0; i < result.size(); i++) {
            cout << result[i] << " ";
        }

        return 0;
    }
```

</div>

2. **קומפליציה והרצה:**
    ```sh
    g++ main.cpp -o main && ./main
    ```

**הערה:**  
פלט בקוד יוצג באזור פלט מבחני הקלט. ודא להסיר הצהרות הדפסה לפני השליחה, שכן הן עלולות להשפיע על מדדי הביצועים (LeetCode מודד זמן הרצה).

**דוגמה עם הצהרת הדפסה:**

<div style="direction: ltr;">

```cpp
class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
        cout << "hello";
        return vector<int>{2}; 
    }
};
```

</div>

- **תוצאת ריצה:**
  ![אזור מבחן](images/image-21.png)

---

### 🟢 Python

#### 📝 דוגמת חתימת פונקציה

לאותה שאלה [Two Sum](https://leetcode.com/problems/two-sum), חתימת הפונקציה ב-Python מופיעה כך:

![פונקציית Python](images/image-23.png)

<div style="direction: ltr;">

```python
class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
```

</div>

**הסבר:**
- **תכנות מונחה עצמים:** הפונקציה היא חלק ממחלקה.
- **הגדרה פשוטה:** אין צורך לכתוב `main()`, הצהרות import, או לטפל ב-namespaces.

#### 🛠️ הרצת הקוד מקומית (Python)

כדי להריץ את הקוד בסביבה המקומית שלך:

1. **צור `main.py`:**

<div style="direction: ltr;">

```python
class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
        # Write your solution here
        # No need for main function, includes, or namespace std
        # Example of just returning [0, 1]
        return [0, 1]

if __name__ == "__main__":
    sol = Solution()
    nums = [2, 7, 11, 15]
    target = 9
    result = sol.twoSum(nums, target)
    print(result)
```

</div>


2. **הרצת הסקריפט:**
    ```sh
    python main.py
    ```

**הערה:**  
פלט בקוד יוצג באזור פלט מבחני הקלט. ודאו להסיר הדפסות לפני השליחה, שכן הן עלולות להשפיע על מדדי הביצועים (LeetCode מודד זמן הרצה).

**דוגמה עם הצהרת הדפסה:**

<div style="direction: ltr;">

```python
class Solution(object):
    def twoSum(self, nums, target):
        print("hello")
        return [0, 1]
```

</div>

- **תוצאת ריצה:**
  ![מבחן Python](images/image-24.png)

---
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



</div>

<script>
  function switchLanguage(lang) {
    if (lang === 'he') {
      document.getElementById("content-en").style.display = "none";
      document.getElementById("content-he").style.display = "block";
    } else {
      document.getElementById("content-en").style.display = "block";
      document.getElementById("content-he").style.display = "none";
    }
  }
</script>



