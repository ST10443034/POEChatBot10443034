# POEChatBot10443034 Cybersecurity Awareness Chatbot
This is a C# console application that educates users about cybersecurity best practices, with a focus on South African threats.

Features
Interactive Chatbot - Discusses various cybersecurity topics
Text-to-Speech - Optional voice responses using System.Speech
Sound Effects - Audible feedback for interactions
User-Friendly Interface - Colorful console output with ASCII art
South African Context - Localized advice for common scams

Topics Covered
🔒 Password safety
🎣 Phishing scams
🌐 Safe browsing
📱 Social media security
💳 Banking fraud protection
📞 SIM swap fraud prevention

Prerequisites
Visual Studio 2022 (or later)

.NET 6.0+ (or .NET Core 3.1+)

System.Speech (for voice synthesis)

Installation
Clone the repository

sh
Copy
git clone https://github.com/yourusername/cybersecurity-chatbot.git
Open in Visual Studio 2022

Launch St10443034Part1.sln

Run the project

Press F5 or click the Start Debugging button

Usage
Type your questions about cybersecurity (e.g., "How do I create a strong password?")

Commands:

help - Shows available topics

exit - Closes the application

Screenshot
Chatbot Demo (Example: Replace with an actual screenshot)

Configuration
Toggle settings in Program.cs:

csharp
Copy
private static bool useVoice = true;      // Enable/disable voice  
private static bool useSoundEffects = true; // Enable/disable sounds  
Contributing
Contributions are welcome! Please:

Fork the repository

Create a feature branch (git checkout -b feature/your-feature)

Commit changes (git commit -m 'Add some feature')

Push to the branch (git push origin feature/your-feature)

Open a Pull Request

License
This project is licensed under the MIT License - see LICENSE for details.
