# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** Randa miqad ALotaibi
| **Student ID** |445052139 |
| **University Email** | 445052139@std.psau.edu.sa |
| **GitHub Username** | randa20m |
| **Repository Link** [| [Paste your repository link here] |](https://github.com/randa20m/OS-Assignment1-Randa-Alotaibi.git)
 
---

## 🎥 Video Link

**Video Link**: https://drive.google.com/file/d/125AvK7roAdedzTt7JFOdOO0Xwzpn6xn4/view?usp=sharing

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 7, 2026]
**What I did**:Set up and personalized the assignment project.

**Details**:examined the Java scheduling simulation in the beginning project.

The random number generator was seeded with an updated student ID.

The student ID modification was committed to GitHub along with the message. To generate a random number, update the student ID.

**Challenges**:Understanding the existing project structure before making changes.

**Solution**: Reviewed the Java code and identified where the student ID was used in the simulation.

**Time spent**:40 minutes

---

### Entry 2 - [ October 9, 2026]
**What I did**: Implemented randomized process priorities.

**Details**:Each process now has a priority number between 1 and 10.

Priorities were assigned using the random number generator.

showed the priority of each operation as it joined the ready queue.

maintained the FIFO order of the ready queue.
Committed the feature with the message feature 1: Add randomized process priority display.

**Challenges**:: Displaying process priorities without changing the ready queue order.

**Solution**:Added the priority as process information and kept the queue's existing FIFO behavior.

**Time spent**:30 minutes

---

### Entry 3 - [- October 9, 2026]
**What I did**:Implemented the context switch counter.

**Details**:The static variable contextSwitchCount was added.

When a scheduled thread was about to begin, the counter was increased.

At the conclusion of the simulation, the total counter value was printed.
Committed the feature with the message Feature 2: Add context switch counter
**Challenges**:Choosing where to increment the counter in the scheduling loop.

**Solution**:Placed the increment immediately before currentThread.start().

**Time spent**:30 minutes

---

### Entry 4 - [ October 9, 2026]
**What I did**: Implemented waiting time tracking and process timing statistics.

**Details**:The Process class now tracks waiting times.

utilized the system.To keep track of ready queue entry times, use currentTimeMillis().

When a process was scheduled, the total waiting time was updated.

A final table with process names, burst times, wait times, and turnaround times was added.
Committed the feature with the message Feature 3: Add process waiting time statistics.

**Challenges**: Tracking waiting time when processes returned to the ready queue.

**Solution**:  Recorded the ready queue entry time and calculated the elapsed waiting time when the process was selected to run again.
**Time spent**:40 minutes


### Entry 5 - [ October 10, 2026]
**What I did**:Reviewed the implementation and worked on the assignment documentation.

**Details**:examined the three features that were put into place.

examined the program's output that was provided.

worked on teaching the project's multithreading concepts and recording the development process.


**Challenges**:Explaining the implementation accurately and connecting the technical answers to the actual code and output.

**Solution**:Reviewed the Java implementation, the assignment requirements, and the available output before preparing the documentation.

**Time spent**:1 hour 

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**:: Several work sessions across October 7, 9, and 10, 2026.[3 hours and 20 minutes.]

**Most challenging part**:knowing how waiting time is added up when a procedure is scheduled again after returning to the ready queue.

**Most interesting learning**:I discovered how Java threads can mimic process execution, how Round-Robin scheduling assigns processes turns to run, and how waiting and turnaround times can be computed.

**What I would do differently next time**:Every work session would be promptly documented, every feature would be tested after it was implemented, and the program output would be kept accessible for reviewing the outcomes.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

I discovered that a software can control several threads of execution thanks to multithreading. For this assignment, I defined the behavior of each process using Java's `Runnable` interface and made a `Thread` for each. I discovered that while `Thread.join()` enables the scheduler to wait for a thread to complete, `Thread.start()` initiates a thread's execution. The scheduler assigns a time quantum to each task and manages them using a ready queue. I also discovered that a process's execution time may be simulated using `Thread.sleep()`. All things considered, this research improved my understanding of how waiting time, scheduling, and threads interact in an operating system simulation.


## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

Finding the waiting times for each process was the hardest part of this task. Before a process completes its execution, it may wait in the ready queue multiple times. I had to keep track of when a process joined the queue and figure out how long it waited. I updated the total waiting time and recorded the time using `System.currentTimeMillis()`. Additionally, I had to ensure that the final results accurately represented the waiting time. I learned from this assignment that process scheduling entails more than just executing each step.



## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

By closely examining the code and completing the task one feature at a time, I was able to overcome the difficulties. I examined how each procedure updated its waiting time and entered the ready queue. In order to see the scheduling behavior and examine the end statistics, I also ran the application. I concentrated on the pertinent techniques and how they interacted when I wanted to comprehend a particular aspect of the implementation. I was able to pinpoint areas that required improvement by testing the program. This method helped me finish the necessary features and made the code easier to understand.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*
Many practical applications employ multithreading to effectively manage several processes. Web browsers, for instance, can load content, handle user interactions, and carry out background operations using several threads. Server programs use threads to manage requests from several clients. Applications that are being downloaded may run in the background while users are still able to interact with the UI. Although shared resources must be properly managed to prevent synchronization issues, multithreading can increase responsiveness. I gained a better understanding of the fundamental scheduling principles underlying multitasking apps thanks to this project.


### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A thread is an execution channel inside a program, whereas a process is an independent program in operation. While threads inside the same Java process can share resources and memory, distinct processes typically have their own memory regions. Compared to distinct operating-system processes, threads typically have lower creation overhead and provide easier communication through shared data. In my assignment, a simulated process is represented by the `Process` class, and the real Java thread that runs it is created by the `new Thread(process)` in `addProcessToQueue()`. Without the need to create distinct operating-system processes, scheduling ideas can be demonstrated through the use of threads.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*
Every process in my Round-Robin simulation is given a time quantum of 4000 milliseconds. A process is moved to the end of the ready queue so that other processes can run if it does not complete within its time quantum. For instance, P5 had to be re-queued twice before it was finished. There were 5442 milliseconds left after its first turn and 1442 milliseconds left after its second. Before it was finished, P9 was also re-queued twice. Instead of allowing one process to continue consuming the CPU while other processes wait, this behavior gives each process a turn, making scheduling more equitable.

Example from my output:
P5 executing quantum [4000ms]
Remaining time: 5442ms
P5 yields CPU for context switch
P5 added to ready queue

P5 executing quantum [4000ms]
Remaining time: 1442ms
P5 yields CPU for context switch
P5 added to ready queue

P5 executing quantum [1442ms]
Remaining time: 0ms
P5 finished execution!
**Explanation of example:**
Because its remaining time was larger than zero, the output indicates that P5 did not finish during its first two rounds. There were 5442 milliseconds left after the first turn and 1442 milliseconds left after the second turn. As a result, before P5 finished executing on the third turn, it was added to the end of the ready queue twice. As P5 waits for its next turn, this permits other processes to run. Round-Robin scheduling thus offers a more equitable allocation of CPU time among tasks.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1For instance, when new Thread(process) generates a new thread within the addProcessToQueue() method, P1 enters the New state. When the scheduler calls currentThread.start(), it enters the Runnable state and is ready to run. P1 is conceptually in the Running state, simulating its execution for a single quantum, when Java schedules the thread to run its run() method. While currentThread is running, Thread.sleep(stepTime) pauses P1 momentarily and places it in the Timed Waiting state.The scheduler thread is forced to wait until P1 completes its present execution by join(). P1's Java thread reaches the Terminated state upon the completion of its execute() method. The scheduler uses addProcessToQueue() to establish a new Java thread for P1's subsequent turn if there is still burst time left.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

## Example 1 (operating-system level): CPU Scheduling

**Description**:
Several processes that require CPU time are managed by an operating system. Each process is given a finite amount of time to run by the scheduler. A process may be moved to the end of the ready queue to wait for another turn if it does not complete within its time quantum.

**Why Round-Robin works well here**:

Round-Robin aids in the equitable distribution of CPU time among processes. One process cannot use the CPU constantly while other processes are waiting because of the time quantum. This is comparable to the FIFO ready queue and time quantum control process execution in my simulation.

### Example 2: Handling Multiple Client Tasks in a Server
**Description**:
Processing requests from various users is one of the many client jobs that a server could have to manage. Each task can be given a finite turn to complete using a Round-Robin-style scheduler. While other activities are processed, incomplete tasks might wait for another turn.

**Why Round-Robin works well here**:
By preventing one task from controlling processing time, this strategy can increase fairness. By giving other activities consistent processing time, it can also increase responsiveness. This is relevant to my Java simulation, as unfinished processes may return to the ready queue and threads run for a finite amount of time.

## Summary

**Key concepts I understood through these questions:**
1. I discovered the distinction between a process and a thread, as well as how to construct and launch Java threads using `Thread.start()`.
2. I comprehended how the Round-Robin algorithm assigns execution turns to processes using a FIFO ready queue and a fixed time quantum.
3. I discovered that thread execution and process scheduling may be illustrated through the use of `Thread.sleep()`, `Thread.join()`, context switch counting, and waiting time tracking.

**Concepts I need to study more:**
1. I must research Java's actual thread lifecycle stages and comprehend how thread execution is impacted by `Thread.start()`, `Thread.sleep()`, and `Thread.join()`.
2. I need to study more about how CPU scheduling functions in an actual operating system and about genuine operating-system context transitions.
---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
