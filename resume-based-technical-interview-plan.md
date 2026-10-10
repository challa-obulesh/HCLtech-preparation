# HCLTech Resume-Based Technical Interview Preparation

**Candidate:** Challa Chinna Obulesh  
**Target:** HCLTech campus hiring — technical interview preparation, with Java/software development as the main focus.

> This is a preparation guide based on the resume shared for this chat and candidate-reported interview experiences. It is not an official HCLTech question paper. Actual questions vary by campus, role, and interviewer.

## 1. Resume-based interview priorities

### Priority A — Java and coding
The resume lists Java, OOP, and Data Structures and Algorithms. Practise explaining the approach before writing code.

- Arrays: maximum, second-largest distinct element, reverse, move zeroes, duplicates, rotate/check sorted-rotated.
- Strings: reverse, palindrome, character frequency, first non-repeating character, anagram check.
- Number programs: prime, palindrome number, reverse digits, digit sum, factorial, Fibonacci.
- Searching/sorting: linear search, binary search, bubble sort; know the basic time complexity.
- Scenario questions: process sales/marks/telemetry-like values, handle ties, empty input, invalid input, and duplicate values.
- For each solution: explain logic, write code, dry-run an example, test edge cases, and state time/space complexity.

### Priority B — Core Java and computer science
- Four OOP pillars: encapsulation, inheritance, polymorphism, abstraction.
- Class vs object; constructor; this; static; access modifiers.
- Overloading vs overriding; interface vs abstract class.
- String vs StringBuilder; == vs equals(); exception handling; Java collections.
- JVM vs JRE vs JDK; why Java is called platform-independent.
- SQL/DBMS: primary and foreign keys, joins, normalization, WHERE vs HAVING, aggregate functions, second-highest salary query.
- OS/networking basics: process vs thread, deadlock, TCP vs UDP, HTTP vs HTTPS, DNS.

### Priority C — Explain every resume project honestly

#### AI Professor Assistant — Telegram AI Agent
Resume technologies: Python, FastAPI, MongoDB Atlas, GitHub.

Prepare:
1. What problem does the assistant solve?
2. What is the user input, and what output does the system return?
3. How does the Telegram message reach the backend?
4. What APIs did you build with FastAPI?
5. What information is stored in MongoDB, and why use a database?
6. How do appointment scheduling and notifications work?
7. What was your personal contribution, hardest bug, and limitation?

Use the actual implementation to support each claim. Do not claim a feature you cannot demonstrate.

#### Real-Time Edge-AI Autonomous Navigation System
Resume technologies: Python, PyTorch, OpenCV, TensorRT, NVIDIA Jetson AGX Orin; SegFormer-B0 segmentation and YOLOv8 object detection.

Prepare:
1. Explain semantic segmentation vs object detection.
2. What does SegFormer-B0 produce? What does YOLOv8 produce?
3. Why deploy on Jetson AGX Orin?
4. Why use TensorRT and FP16 optimisation?
5. What are the camera input, model outputs, and downstream navigation use?
6. What did you measure or optimise, and what are the current limitations?
7. Explain the related IEEE conference paper, which the resume lists as **under review**. Do not describe it as accepted or published.

#### FitAI Pro — AI-Powered Fitness and Nutrition Assistant
Resume technologies: Python, OpenCV, Streamlit, Plotly, Pandas.

Prepare:
1. What user problem does the application address?
2. How does meal calorie estimation work in your implementation?
3. What inputs and outputs does it have?
4. Why use Streamlit and Plotly?
5. How are workout and nutrition recommendations generated?
6. What is the system's limitation, and how would you improve it?

### Priority D — General interview communication
- Prepare a 60–90 second self-introduction.
- For each project, explain: problem → input → approach → technology → output → your contribution → limitation.
- Prepare “Why HCLTech?”, strengths, learning from a mistake, teamwork, and willingness to learn.
- Keep answers clear and truthful. Practise speaking aloud in simple English.

## 2. Seven-day daily checklist

Aim for about 2–3 focused hours per day; adjust to the available time. Tick tasks only after completing them.

### Day 1 — Arrays
- [ ] Explain array indexing and traversal.
- [ ] Code maximum and minimum.
- [ ] Code second-largest **distinct** element without sorting.
- [ ] Code reverse array and move zeroes to the end.
- [ ] Dry-run at least two examples and handle duplicates/empty input.

### Day 2 — Strings
- [ ] Explain String, length(), charAt(), equals(), and ==.
- [ ] Code string reversal without a built-in reverse method.
- [ ] Code palindrome check.
- [ ] Count character frequencies.
- [ ] Find the first non-repeating character.

### Day 3 — Number programs and complexity
- [ ] Code prime number and factorial.
- [ ] Code palindrome number and reverse digits.
- [ ] Code Fibonacci or digit sum.
- [ ] Explain O(1), O(n), and O(n²) with examples.
- [ ] Review mistakes from Days 1–2.

### Day 4 — Mixed scenario coding
- [ ] Solve 3 timed easy coding problems.
- [ ] Practise handling duplicates, ties, empty input, and boundary cases.
- [ ] Explain the algorithm before coding.
- [ ] State time and space complexity after coding.
- [ ] Record mistakes and corrected solutions.

### Day 5 — Core Java and SQL
- [ ] Explain the four OOP pillars with examples.
- [ ] Revise overloading vs overriding and interface vs abstract class.
- [ ] Revise String vs StringBuilder and == vs equals().
- [ ] Write 5 SQL queries using filtering, grouping, joins, or aggregates.
- [ ] Explain primary key, foreign key, and normalization.

### Day 6 — Resume projects
- [ ] Practise a 60–90 second explanation for each of the three projects.
- [ ] Explain each project's input, processing, output, stack, and personal contribution.
- [ ] Review likely follow-up questions for FastAPI/MongoDB, SegFormer/YOLO/TensorRT, and OpenCV/Streamlit.
- [ ] Explain the IEEE paper's status accurately as under review.
- [ ] Identify one limitation and one possible improvement for each project.

### Day 7 — Mock interview and revision
- [ ] Complete a timed set of 5–6 mixed technical questions.
- [ ] Solve at least 2 coding problems without looking at solutions.
- [ ] Answer 10 rapid-fire Java/SQL/CS fundamentals questions.
- [ ] Give a self-introduction and explain one project aloud.
- [ ] Revise every wrong or guessed answer and plan the next week's weak topics.

## 3. Daily progress log

Update this section after each study session.

| Date / Day | Topics completed | Coding solved | Score / confidence | Mistakes to revisit | Next task |
|---|---|---|---|---|---|
| Day 1 | — | — | — | — | Arrays |
| Day 2 | — | — | — | — | Strings |
| Day 3 | — | — | — | — | Number programs |
| Day 4 | — | — | — | — | Scenario coding |
| Day 5 | — | — | — | — | Java + SQL |
| Day 6 | — | — | — | — | Projects |
| Day 7 | — | — | — | — | Mock interview |

## 4. Interview practice method

For every question:
1. Restate what the problem asks.
2. Explain the approach in 2–3 sentences.
3. Write readable Java code.
4. Dry-run the sample.
5. Test normal cases and edge cases.
6. State time and space complexity.
7. Record the mistake if the answer was wrong or incomplete.

## 5. Repository and project links

- HCLTech preparation repository: https://github.com/challa-obulesh/HCLtech-preparation
- AI Professor Assistant: https://github.com/challa-obulesh/RGMCET-AI-ASISTANCE-
- Edge-AI navigation: https://github.com/challa-obulesh/semantic_segmentation_jetson
- FitAI Pro: https://github.com/challa-obulesh/fitai-pro

**Important:** The checklist is a plan, not evidence that a task is complete. Update the progress log honestly after practice. Prioritise the placement-cell instructions if the actual hiring format differs.
