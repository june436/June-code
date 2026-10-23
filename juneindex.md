def run_quiz():
    questions = {
        "What is the capital of France?": "Paris",
        "What does CPU stand for?": "Central Processing Unit",
        "What is 2 + 3?": "5",
    }

    score = 0

    for question, correct_answer in questions.items():
        print(f"\n{question}")
        user_answer = input("Your answer: ").strip()

        if user_answer.lower() == correct_answer.lower():
            print("Correct!")
            score += 1
        else:
            print(f"Wrong! The correct answer is: {correct_answer}")

    print(
        f"\nGame Over! You got {score} out of {len(questions)} questions right."
    )


if __name__ == "__main__":
    run_quiz()
Use code with caution.

How to Run It

1. Save the code in a file named quiz.py.
2. Open your terminal or command prompt.
3. Run the command: python quiz.py
If you want, let me know:
• What programming language you prefer (Python, JavaScript, C++, etc.)
• If you want multiple-choice options (A, B, C, D) instead of typed answers
• A specific topic for the questions
I can customize the code for you.
• 
YouTube·BracesAndSemicolons
SIMPLE QUIZ GAME - Project #3 | Python for Beginners ...
Jul 24, 2025 — In this beginner-friendly Python project, we build a simple text-based quiz game that asks the user questions, checks their answer...
4:10
AI responses may include mistakes. Learn more
    
