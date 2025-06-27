# prog6221-poe-AndileNzama21
 ✅ Features
1. 💬 Chatbot Tab
•	Ask cybersecurity questions like:
o	"How do I make a strong password?"
o	"What is phishing?"
o	"Tell me about privacy settings"
•	The bot gives smart responses using keyword detection.
•	Responses are logged in the activity log.
Example Test:
Type: What is a strong password?
Result: Bot replies: "Use a strong password with numbers and symbols."
 
2. 📋 Task Assistant Tab
•	Add cybersecurity tasks like setting up 2FA or updating passwords.
•	Set a reminder date using a calendar control.
•	View all tasks in a task list.
Example Test:
1.	Enter:
o	Task Title: Enable 2FA
o	Description: Turn on 2FA for all important accounts
o	Pick reminder date.
2.	Click Add Task.
3.	See it appear in the list.
 
3. 🧠 Cybersecurity Quiz Tab
•	Take a 10-question quiz on key cybersecurity topics.
•	Questions are a mix of multiple choice and true/false.
•	Immediate feedback after each answer.
•	Final score shown at the end.
Example Test:
First question: What should you do if you receive a suspicious email?
Select: Report as phishing → Press Submit Answer
See: Correct! and score updates.
 
4. 📜 Activity Log Tab
•	View the last 10 actions performed.
•	Includes chat, quiz attempts, and task additions.
Example Test:
Click Show Activity Log
See items like:
•	[Chat] User said: what is phishing
•	[Task] Added: Enable 2FA, Reminder: 27/06/2025
•	[Quiz] Q1: Correct
 
🛠️ How to Run the App
Step-by-Step:
1.	Create a Windows Forms App (.NET Framework)
o	Open Visual Studio
o	File > New > Project > Select Windows Forms App (.NET Framework)
o	Name: CybersecurityChatbotGUI
2.	Paste the Full Code
o	Replace the default form code (Form1.cs) with the code from CyberChatForm.cs.
3.	Set Entry Point
In Program.cs, update to:
4.	static class Program
5.	{
6.	    [STAThread]
7.	    static void Main()
8.	    {
9.	        Application.EnableVisualStyles();
10.	        Application.SetCompatibleTextRenderingDefault(false);
11.	        Application.Run(new CyberChatForm());
12.	    }
13.	}
14.	Run It
o	Press F5 or click Start Debugging.
 
💡 Technologies Used
•	C# .NET Framework
•	Windows Forms (WinForms)
•	GUI Controls: TabControl, TextBox, ListBox, DateTimePicker, RadioButton
•	Custom logic for:
o	Chatbot NLP simulation
o	Task management
o	Quiz scoring
o	Activity logging

📚 References (Harvard Style)
Anderson, R., 2020. Security Engineering: A Guide to Building Dependable Distributed Systems. 3rd ed. Hoboken: Wiley.

Hadnagy, C., 2018. Social Engineering: The Science of Human Hacking. 2nd ed. Indianapolis: Wiley.

National Institute of Standards and Technology (NIST), 2023. Cybersecurity Framework. [online] Available at: https://www.nist.gov/cyberframework [Accessed 25 Jun 2025].

Microsoft, 2024. Windows Forms Overview. [online] Microsoft Docs. Available at: https://learn.microsoft.com/en-us/dotnet/desktop/winforms/ [Accessed 25 Jun 2025].

OWASP Foundation, 2024. OWASP Top 10: The Ten Most Critical Web Application Security Risks. [online] Available at: https://owasp.org/www-project-top-ten/ [Accessed 25 Jun 2025].

