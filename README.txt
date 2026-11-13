Your document is 90% perfect. The data, the bug explanation, and the tables are exactly what the lecturer wants to see.

However, I found 4 critical things you must fix before you submit, otherwise you will lose marks!

Here is your checklist to fix the document:

🚨 1. The Missing GitHub Link

At the very top of your document, right under your name, you must paste the link to your public GitHub repository. The instructions strictly state: "with the public GitHub repository link to YOUR OWN source code at the top".

🚨 2. Fix the Placeholders in Task A2

Look at your registration number: VU-BSF-2503-2170-DAY. The last digit is 0 (Even). 
You left the placeholder text in your document. You must change it to:

· My Registration Number Last Digit: 0 (Even)
· Chosen Algorithm: Merge Sort (Since 0 is even, the rule dictates Merge Sort).
· Meaningful Key: The records are sorted by score (ascending order).

🚨 3. Fix the Typo in Task A1 Code Snippet

In your code snippet under Task A1, you have a typo with a capital "C":
data(nullptr), count(other. Count), capacity(other.capacity)
Change other. Count to other.count (lowercase 'c'). Also, if you see a stray  ```  at the very end of the snippet, delete it (that's markdown formatting that didn't copy correctly into Word).

🚨 4. Insert the Screenshots!

You currently have blank spaces where the screenshots should be.

· A3.2: You must actually copy and paste the image of your terminal running with ASan.
· A4 Chart: Paste the Excel chart we just made into the document.

---

🔍 Minor Formatting Fix

In your A4 Complexity Table, the removeAt row is a bit messy. It says:

removeAt
shift. O(1) O(n)

Just fix that row to look clean like this:

| removeAt | O(1) | O(n) | O(1) if removing the last element. O(n) if removing the first, requiring a shift. |

---

📦 Final Submission Checklist (The ZIP File)

Inorder to access the project follow the instructions; 
   Compile: g++ -std=c++17 -g -fsanitize=address,undefined StudentResultRegister.cpp -o register
   Run: ./register
