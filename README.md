# Test-Exam-Taker
<p>
  Introduction: <br>
Command-Line Test is a BASH Shell based tool that simulates Login-based Online Testing scenario. Initially, the User will be provided with a Sign-in option where pre-defined Users will be allowed to Login. Upon successful Login, this tool will display Questions for the particular logged-in User from existing data-base. It will also handle Error conditions like Time-out. This tool will also store Answers provided by the particulat logged-in User for future verification.<br>

These days there are a lot of Online Test platform which enables Students to take Tests Online. They will typically have a User-interface, Backend Question Bank and Evaluation mechanism. They will also support other features like pre-defined Time per Question, Output Reports etc. The idea of this project is to simulate such an Online Test Interface using Linux Shell Scripting and Commands.<br>

By implementing this Linux Shell Scripting Project, we make use of Shell programming constructs (eg: loops), Pattern matching commands (eg: grep, sed etc.) and File-handling (eg: permission, directories etc.) aspects during implementation.<br>

Requirements:<br>
Provide a prompt for the user to Sign-up and Sign-in:<br>
<br>
Sign In<br>
a. Take Test<br>
b. View Test<br>
Sign up<br>
Exit<br>
Using sign-up user can register with a User-ID and Password:<br>

Ask for User-name. The User-name should contain only Alpha-Numeric symbols.
Ask for new Password. The Password can contain any symbol in it. Accept at-least 8 characters with at-least a Number and Symbol.
Ask the User to re-enter the Password again for validation.<br>
Already Registered User can Sign-in with ID and Password:<br>

The Script should prompt for User-name and Password.
The Password should be like a Shadow Password (i.e. characters shall be blank while typing).
Show Error in-case the 2 Passwords mismatch.<br>
Create Log-file:<br>

Every activity while the Script is to be Logged in test_activity.log file.
Keep Date and Time along with every Activity.<br>
Question bank:<br>

User should provide a Question Bank file along with the Script.
If not, Search for a file named question_bank.txt as a Default Question Bank.<br>
Taking a test:<br>

Should create a directory called “.TestData” in User’s Directory structure. For eg.: ECEP/LinuxSystems/Projects directory if it doesn’t exist.
Create a file named “answer_file.csv” under TestData directory if it doesn’t exist.
Prompt the User with Questions one by one randomly picked from the question_bank.txt file.
Prompt for Questions with Multiple choice.
Every Question should be Timed, say 10 seconds.
On time-out, the Question should change with fresh time-out.
Every answer should be stored in answer_file.csv with the Question separated by comma.
The answer should be stored with Attempt time. Eg.: If I answer within 5 seconds, then my answer with 5 seconds (Attempt time) should be stored.
If the User chooses one Option, the Script should show all the Questions with all Options and the Answer should be highlighted.
</p>
