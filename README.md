# MCQ
An interactive, multiplayer-enabled MCQ practice web platform with real-time tracking, custom themes, and a local library for students.

# RAMISH MCQs 🚀

RAMISH MCQs is a powerful, interactive web application designed to help students practice Multiple Choice Questions (MCQs) in a realistic computer-based test (CBT) environment. It allows users to parse raw text into standardized quizzes, save them in a local library, and even host real-time multiplayer quiz sessions.

## ✨ Key Features

*   **Custom Library & Folders:** Save your quizzes locally, organize them into folders, and resume tests right from where you left off.
*   **Multiplayer Mode (PeerJS):** Host live quizzes! Connect mobile devices via QR code to act as player remotes or admin controllers.
*   **Smart Exam Modes:** 
    *   **Exam Mode:** Hides correct answers and scores until the end.
    *   **Shuffle:** Randomizes question order.
    *   **Timer:** Set custom time limits per question.
*   **Question Palette:** A grid map to track unseen, attempted, and current questions easily.
*   **Performance Analytics:** View detailed results including total time, average time per question, accuracy, and a leaderboard for multiplayer.
*   **Mistake Review & Practice:** Instantly review wrong answers and start a dedicated practice session for mistakes.
*   **Custom Themes:** Choose from Multiple UI themes (Blue, Emerald, Violet, Rose, Amber) and toggle Dark/Light mode.

## 📝 How to Format Questions

To paste questions into the app, use the following strict format:

1. Start every question with a number.
2. Enclose the question text inside `<Q>` and `</Q>` tags.
3. Enclose the options inside `<A>` and `</A>` tags.
4. Place an asterisk `(*)` exactly before the correct option's bracket.

**Example:**
```text
1. <Q> Psychology is the scientific study of? </Q>
<A>
*(a) Behaviour and mental processes
(b) Only behaviour
(c) Only mind
(d) Human biology 
</A>

🛠️ Tech Stack
HTML5 / CSS3 / JavaScript (Modular Structure)

Tailwind CSS (Styling & Responsiveness)

PeerJS (WebRTC for Multiplayer Remote Control)

Canvas Confetti (Celebration Animations)

👨‍💻 Developed By
Ramish Bhai
