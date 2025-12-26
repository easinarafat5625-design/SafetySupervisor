Safety Supervisor (Android Studio) - READY PROJECT SKELETON

What you get:
- Kotlin Android project
- Room (SQLite) schema for Topics, Questions (MCQ), Chapters (Learning Book), Bookmarks, Attempts
- Basic screens: Home, Learning Chapters, Chapter Reader, Practice Setup, Mock Setup, Progress

How to open:
1) Extract the ZIP
2) Open the folder in Android Studio (File > Open)
3) Let Gradle sync (Android Studio will download dependencies)

IMPORTANT:
- This skeleton creates an EMPTY database by default.
- To include 10,000+ MCQs offline:
    a) Build a prefilled SQLite DB file named: safety_supervisor.db
    b) Put it in: app/src/main/assets/safety_supervisor.db
    c) In DbProvider.kt change builder to:
        Room.databaseBuilder(...).createFromAsset("safety_supervisor.db")

Templates:
- templates/questions_template.csv
- templates/chapters_template.csv
