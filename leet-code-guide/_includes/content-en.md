
# 🌍 LeetCode Guide for Beginners

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
   - ![First time you're not logged in]({{/assets/image.png| relative_url}})
2. **Sign In via GitHub:**
   - Click **Sign In** and choose the GitHub option for a streamlined login process.
   - ![Sign-In Options]({{ site.url }}{{ site.baseurl }}/assets/images/image-1.png)
   - ![Login via GitHub]({{ site.url }}{{ site.baseurl }}/assets/images/image-2.png)

3. **Logged-In Homepage:**
   - Once logged in, your homepage will display various navigation options.
   - ![Basic LeetCode Page]({{ site.url }}{{ site.baseurl }}/assets/images/image-3.png)

### 🧭 Navigating the Platform

![Navigation Bar]({{ site.url }}{{ site.baseurl }}/assets/images/image-4.png)
LeetCode offers several key sections:

- **🔍 Explore:**
  - Browse questions categorized visually by different topics.
  - ![Explore Page]({{ site.url }}{{ site.baseurl }}/assets/images/image-5.png)

- **📚 Problems:**
  - Access a comprehensive list of coding problems.
  - **Filters Available:**
    - **Difficulty:** Easy, Medium, Hard
    - **Tags:** Array, String, Tree, SQL, etc.
  - ![Problem Page]({{ site.url }}{{ site.baseurl }}/assets/images/image-6.png)
  - ![Bottom of Problem Page]({{ site.url }}{{ site.baseurl }}/assets/images/image-7.png)

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
   - ![Pressing Easy]({{ site.url }}{{ site.baseurl }}/assets/images/image-8.png)

3. **Daily Challenge:**
   - The first question is the **Daily Challenge**.
   - Solve it daily to build a streak, visible on your profile.
   - ![Daily Challenge]({{ site.url }}{{ site.baseurl }}/assets/images/image-9.png)

4. **Explore the List:**
   - ![Problems List]({{ site.url }}{{ site.baseurl }}/assets/images/image-10.png)
   - **Status:** Indicates if you've solved the problem.
   - **Acceptance Rate:** Percentage of users who solved it.
   - **Lock Icon:** Premium feature showing interview frequency and acceptance rate *(not recommended)*.

5. **Unsolved Problems:**
   - These problems are yet to be tackled.
   - ![Unsolved Problems]({{ site.url }}{{ site.baseurl }}/assets/images/image-11.png)

---

## 🛠️ How to Solve a Question

1. **Select an Unsolved Problem:**
   - Click on a problem you haven't solved yet.
   - ![Merge Sorted Array]({{ site.url }}{{ site.baseurl }}/assets/images/image-12.png)

2. **Understand the Problem Page:**
   - **Coding Area:** Write your code here.
     - ![Coding Area]({{ site.url }}{{ site.baseurl }}/assets/images/image-13.png)
   - **Language Selection:** Choose your preferred programming language.
     - ![Language Selection]({{ site.url }}{{ site.baseurl }}/assets/images/image-14.png)

   **Note:** LeetCode provides necessary libraries; no need to import them manually.

3. **Test Cases:**
   - ![Test Case Area]({{ site.url }}{{ site.baseurl }}/assets/images/image-18.png)
   - You can edit the input values and run basic test cases.
   - Can add your own tests by pressing **+**.

4. **Submitting Your Solution:**
    - ![Run vs Submit]({{ site.url }}{{ site.baseurl }}/assets/images/image-19.png)

   - **Run vs. Submit:**
     - **Run:** Quick checks with limited test cases.
     - **Submit:** Comprehensive testing and performance metrics.
   - **Post-Submission:**
     - View how your solution performs compared to others.
     - If successful, the problem is marked as **solved**.
     - ![Successful Submission]({{ site.url }}{{ site.baseurl }}/assets/images/image-20.png)

5. **Problem Description:**
   - ![Problem Area]({{ site.url }}{{ site.baseurl }}/assets/images/image-15.png)
   - **Tabs Available:**
     - **Description:** Problem statement and constraints.
     - **Editorial:** *(Premium feature, not recommended.)*
     - **Solutions:** Community solutions and discussions.
     - **Submissions:** Your past attempts and their performance.

6. **Viewing Solutions:**
   - ![Solutions Example]({{ site.url }}{{ site.baseurl }}/assets/images/image-16.png)
   - Filter by language and explore different approaches.
   - ![Solution]({{ site.url }}{{ site.baseurl }}/assets/images/image-17.png)
   - View explanations, code, and community comments.

---

## 💻 How to Interact with the Platform - Coding Area Notes

### 🖥️ Examples in C++ and Python

I will demonstrate how to use the coding area with **C++** and **Python**. Feel free to contribute examples in other languages!

---

### 🔷 C++

#### 📝 Function Signature Example

If you select the question [Two Sum](https://leetcode.com/problems/two-sum), you'll see the following function signature:

![Coding Area]({{ site.url }}{{ site.baseurl }}/assets/images/image-22.png)

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
  ![Test Area]({{ site.url }}{{ site.baseurl }}/assets/images/image-21.png)

---

### 🟢 Python

#### 📝 Function Signature Example

For the same question [Two Sum](https://leetcode.com/problems/two-sum), the Python function signature appears as:

![Python Function]({{ site.url }}{{ site.baseurl }}/assets/images/image-23.png)

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
  ![Python Test]({{ site.url }}{{ site.baseurl }}/assets/images/image-24.png)

---
