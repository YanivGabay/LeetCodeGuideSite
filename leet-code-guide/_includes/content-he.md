
# 🌍 מדריך למתחילים בליטקוד

## 🎓 ברוכים הבאים למדריך LeetCode

ברוכים הבאים ל**מדריך למתחילים בליטקוד**! מדריך זה נועד לסטודנטים שמעולם לא השתמשו בליטקוד ורוצים להתחיל להשתמש בפלטפורמה בצורה יעילה.

- **מיקוד טכני:** נלמד כיצד להשתמש באתר, לנווט בתכונות שלו.
- **אין אלגוריתמים :** מדריך זה **אינו** מכסה אלגוריתמים או פתרונות קוד בפועל.

---

## 🔗 <a id="navigation"></a> נווט במדריך

1. **[למה LeetCode?](#why-leetcode)**
2. **[חיבור וניווט ראשוני](#setup-navigation)**
3. **[כיצד לבחור שאלה](#choosing-questions)**
4. **[איך לפתור שאלה](#solving-questions)**
5. **[כיצד להתפעל עם הפלטפורמה - הערות על אזור הקוד](#platform-tips)**
6. **דוגמאות קוד**
    - **[C++](#cpp-example)**
    - **[Python](#python-example)**


---


## <a id="why-leetcode"></a> 💡 למה אנחנו פותרים ולמה זה חשוב


ליטקוד הפך ל**משאב מקיף** ל**שאלות ראיונות קוד**.

### 🔍 יתרונות מרכזיים:
- **בדיקה אינטראקטיבית:** הרץ ובדוק את הקוד שלך ישירות על הפלטפורמה.
- **טיפול במקרים קצה:** בדוק את הפתרונות שלך נגד מגוון מקרים קצה.
- **קהילה:** צפה, פרסם ודון בפתרונות עם אחרים.

### 🎯 חשיבות למהנדסי תוכנה עתידיים:
- **הכנה לראיונות:** חיוני להכנה לראיונות קוד בתעשיית הטכנולוגיה.
- **רשימות מסוננות:** גישה לרשימות מסכמות של שאלות (למשל, *Neetcode 150*, *Top 100 LeetCode Questions*).

---

## ⚙️ <a id="setup-navigation"></a> חיבור\הרשמה וניווט ראשוני

### 🛠️ התחלה

1. **צור חשבון:**
   - כנסו ל-[LeetCode](https://leetcode.com) וצרו חשבון חינם.
   - ![פעם ראשונה שלא התחברת]({{ site.url }}{{ site.baseurl }}/assets/images/image.png)

2. **אפשר גם ישירות להתחבר דרך GitHub:**
   - לחצו על **Sign In** ובחרו באפשרות GitHub להתחברות נוחה.
   - ![אפשרויות התחברות]({{ site.url }}{{ site.baseurl }}/assets/images/image-1.png)
   - ![התחברות דרך GitHub]({{ site.url }}{{ site.baseurl }}/assets/images/image-2.png)

3. **דף הבית לאחר התחברות:**
   - לאחר ההתחברות, דף הבית יציג אפשרויות ניווט שונות.
   - ![דף LeetCode בסיסי]({{ site.url }}{{ site.baseurl }}/assets/images/image-3.png)

### 🧭 ניווט בפלטפורמה

![סרגל ניווט]({{ site.url }}{{ site.baseurl }}/assets/images/image-4.png)

ליטקוד מציע מספר חלקים מרכזיים:

- **🔍 Explore:**
  - דפדף בשאלות המסווגות ויזואלית לפי נושאים שונים.
  - ![דף Explore]({{ site.url }}{{ site.baseurl }}/assets/images/image-5.png)

- **📚 Problems:**
  - גש לרשימה מקיפה של בעיות קוד.
  - **מסננים זמינים:**
    - **קושי:** קל, בינוני, קשה
    - **תגיות:** Array, String, Tree, SQL, וכו'
        - אופציה זו מומלצת לסטודנטים שעדיין לא מכירים את כל האפשרויות, לדוגמא סננו לפי Array.
  - ![דף Problems]({{ site.url }}{{ site.baseurl }}/assets/images/image-6.png)
  - ![תחתית דף Problems]({{ site.url }}{{ site.baseurl }}/assets/images/image-7.png)

- **🏆 Contests:**
  - השתתף בתחרויות קוד שבועיות.
  - צפה בתחרויות הקרבות, הנוכחיות והעבר.

- **💬 Discuss:**
  - התחבר עם הקהילה דרך פורומים.
  - שאל שאלות וצפה בדיונים.

- **🗣️ Interview:**
  - הדמיה של סצנות ראיון אמיתי.
  - *(הערה: תכונה זו פחות פופולרית בהשוואה לאחרים.)*

---

## 📝 <a id="choosing-questions"></a> כיצד לבחור שאלה

1. **גש ל-Problems:**
   - לחצו על **Problems**.

2. **סנן לפי קושי:**
   - מומלץ להתחיל בבעיות **קלות** אם אתם מתחילים.
   - ![לחיצה על Easy]({{ site.url }}{{ site.baseurl }}/assets/images/image-8.png)

3. **אתגר יומי:**
   - השאלה הראשונה היא **אתגר יומי**.
   - פתרו אותה מדי יום לבניית רצף, הנראה בפרופיל שלך.
   - ![אתגר יומי]({{ site.url }}{{ site.baseurl }}/assets/images/image-9.png)

4. **דפדוף ברשימה:**
   - ![רשימת בעיות]({{ site.url }}{{ site.baseurl }}/assets/images/image-10.png)
   - **סטטוס:** מציין אם פתרתם את הבעיה.
   - **שיעור קבלה:** אחוז המשתמשים שפתרו אותה.
   - **סמל נעילה:** תכונה פרימיום המציגה תדירות ראיון ושיעור קבלה *(לא מומלץ)*.

5. **בעיות שלא פותרו:**
   - אלו הן הבעיות שטרם התמודדת איתן.
   - אין להם סימון ירוק בצד שמאל.
   - ![בעיות שלא פותרו]({{ site.url }}{{ site.baseurl }}/assets/images/image-11.png)

---

## 🛠️ <a id="solving-questions"></a> איך לפתור שאלה

1. **בחרו בעיה שלא פתרתם:**
   - לחצו על בעיה שטרם פתרתם.
   - ![Merge Sorted Array]({{ site.url }}{{ site.baseurl }}/assets/images/image-12.png)

2. **הבן את דף השאלה:**
   - **אזור הקוד:** כתבו את הקוד שלכם כאן.
     - ![אזור הקוד]({{ site.url }}{{ site.baseurl }}/assets/images/image-13.png)
   - **בחירת שפה:** בחרו את שפת התכנות המועדפת עליכם.
     - ![בחירת שפה]({{ site.url }}{{ site.baseurl }}/assets/images/image-14.png)

   **הערה:** ליטקוד מספק את הספריות הנדרשות; אין צורך לייבא אותן ידנית.

3. **מבחני קלט:**
   - ![אזור מבחני קלט]({{ site.url }}{{ site.baseurl }}/assets/images/image-18.png)
   - אתם יכולים לערוך את הטסטים או להוסיף טסטים משלכם.


4. **שליחת הפתרון שלך:**
    - ![הפעל מול שליחה]({{ site.url }}{{ site.baseurl }}/assets/images/image-19.png)
   - **Run מול Submit:**
     - **Run:** מריץ את התכנית שלכם, כולל קומפיליציה ובדיקה לעומת מספר טסטים קטן שנמצא בחלון טסטים
     - **Submit:** מריץ ומקמפל את התכנית שלכם ומשווה אותה לכל הטסטים האפשריים עבור הבעיה
   - **לאחר השליחה:**
     - צפו כיצד הפתרון שלכם ביחס לאחרים.
     - אם הצלחת, הבעיה תסומן כ**נפתרה**.
     - ![הגשה מוצלחת]({{ site.url }}{{ site.baseurl }}/assets/images/image-20.png)

5. **תיאור הבעיה:**
   - ![אזור הבעיה]({{ site.url }}{{ site.baseurl }}/assets/images/image-15.png)
   - **כרטיסיות זמינות:**
     - **Description:** ניסוח הבעיה והגבלות.
     - **Editorial:** *(תכונה פרימיום, לא מומלץ.)*
     - **Solutions:** פתרונות בפורום קהילתי ודיונים.
     - **Submissions:** ניסיונות קודמים שלכם וביצועיהם.

6. **צפייה בפתרונות:**
   - סינון לפי שפה וחקור גישות שונות.
   - ![דוגמת פתרונות]({{ site.url }}{{ site.baseurl }}/assets/images/image-16.png)
   - לחיצה על אחד הפתרונות תציג הסברים, קוד ותגובות מהקהילה.
   - ![פתרון]({{ site.url }}{{ site.baseurl }}/assets/images/image-17.png)


---


## 💻 <a id="platform-tips"></a> כיצד להתפעל עם הפלטפורמה - הערות על אזור הקוד



### 🖥️ דוגמאות ב-C++ ו-Python

אני אראה כיצד להשתמש באזור הקוד עם **C++** ו-**Python**. אתם מוזמנים לתרום דוגמאות בשפות נוספות!

---

## 🔷 <a id="cpp-example"></a> דוגמת קוד ב-C++

#### 📝 דוגמת לחתימת פונקציה

אם תבחרו בשאלה [Two Sum](https://leetcode.com/problems/two-sum), תראו את חתימת הפונקציה הבאה:

![אזור קידוד]({{ site.url }}{{ site.baseurl }}/assets/images/image-22.png)

<div style="direction: ltr;" markdown="1">

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

#### 🛠️ הרצת קוד מקומית (C++)

כדי להריץ את הקוד בסביבה המקומית שלך:

1. **צור `main.cpp`:**

<div style="direction: ltr;" markdown="1">

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

<div style="direction: ltr;" markdown="1">

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
  ![אזור מבחן]({{ site.url }}{{ site.baseurl }}/assets/images/image-21.png)

---

## 🟢 <a id="python-example"></a> דוגמת קוד ב-Python

#### 📝 דוגמת לחתימת פונקציה

לאותה שאלה [Two Sum](https://leetcode.com/problems/two-sum), חתימת הפונקציה ב-Python מופיעה כך:

![פונקציית Python]({{ site.url }}{{ site.baseurl }}/assets/images/image-23.png)

<div style="direction: ltr;" markdown="1">

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

<div style="direction: ltr;" markdown="1">

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

<div style="direction: ltr;" markdown="1">

```python
class Solution(object):
    def twoSum(self, nums, target):
        print("hello")
        return [0, 1]
```

</div>

- **תוצאת ריצה:**
  ![מבחן Python]({{ site.url }}{{ site.baseurl }}/assets/images/image-24.png)

---
