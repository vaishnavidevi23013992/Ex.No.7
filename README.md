# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 19-09-2025
# Register no. 212223040230
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: ChatGPT


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

# Procedure: 
## 1. Define Core Requirements
The assistant should:

### 1. Daily Task Manager

- Accept tasks via natural language.

- Organize them by priority, category, and deadline.

- Provide summaries of pending, completed, and upcoming tasks.

### 2. Smart Scheduler

- Suggest optimal time slots.

- Detect conflicts (overlapping tasks/events).

- Reschedule intelligently based on user goals (e.g., productivity in mornings, lighter tasks in evenings).

### 3. Reminder System

- Set one-time or recurring reminders.

- Provide early nudges.

- Send follow-up notifications if ignored.

### 4. Wellness Tips Generator

- Suggest hydration, posture, exercise, screen-time breaks, mindfulness.

- Adapt based on user history (e.g., if hydration is skipped, recommend stretches instead).

### 5. General Query Handling

- Answer contextual queries (e.g., food, health, productivity hacks, small knowledge lookups).

### 6. Adaptation & Personalization (Optional with Memory)

- Learn user preferences over time. 

- Preferred notification style (short vs. detailed).

- Daily routines (morning focus, evening relaxation).

- Past feedback (e.g., user ignored hydration → switch to exercise tips).
  
![images](https://github.com/user-attachments/assets/30846f25-db63-4055-9a11-e97639f11dc2)


## 2. Identify & Construct Prompts for Each Task

We’ll design prompts at three levels: Simple → Intermediate → Advanced.

### Prompt Progression
### A) Daily Task Manager
#### 🔹 Simple Prompt
```
“Add ‘Finish report by 6 PM’ to my tasks.”
```
#### Output:

“✅ Added task: Finish report (deadline: 6 PM).”

#### 🔹 Intermediate Prompt
```
“Here are my tasks: (1) Submit assignment (due 12 PM), (2) Buy groceries, (3) Review code (due 3 PM). Organize by urgency and suggest when I should do them.”
```
#### Output:

“✅ Morning: Submit assignment (urgent, due 12 PM).

☑️ Afternoon: Review code (due 3 PM).

❌ Evening: Buy groceries (low urgency).”

#### 🔹 Advanced Prompt
```
“You are my productivity coach. Review my tasks for today and create a structured plan balancing focus, breaks, and deadlines. Consider that I work best in the mornings and prefer breaks after 90 minutes.”
```
#### Output:

“🔹 9:00–10:30 AM → Submit assignment (urgent, high focus).

🔹 10:30–10:45 AM → Short break.

🔹 11:00 AM–12:30 PM → Review code.

🔹 12:30–1:00 PM → Lunch.

🔹 Evening → Buy groceries.”

### B) Smart Scheduler
#### 🔹 Simple Prompt

```
“Schedule a meeting tomorrow at 10 AM.”
```

#### Output:

“📅 Meeting scheduled for tomorrow 10–11 AM.”

#### 🔹 Intermediate Prompt

```
“I have a meeting 10–11 AM and a doctor’s visit 11–12. Suggest the best time for a 45-min workout.”
```

#### Output:

“Free slot: 12:15–1:00 PM. Recommended workout time: 12:15 PM.”

#### 🔹 Advanced Prompt

```
“You are my smart scheduler. I want mornings for high-focus tasks and afternoons for lighter work. I have: (1) Team meeting (10–11 AM), (2) Update slides (due 2 PM), (3) Grocery run, (4) Reading (20 pages). Suggest a balanced schedule.”
```

#### Output:

- “9:00–10:00 AM → Update slides (high focus).

- 10:00–11:00 AM → Team meeting.

- 11:15–12:00 PM → Continue slide updates.

- 12:30–1:00 PM → Lunch.

- 2:00–3:00 PM → Grocery run.

- 4:00–5:00 PM → Reading (relaxing activity).”

### C) Reminder System
🔹 Simple Prompt

“Remind me to take medicine at 9 PM.”

Output:

```
“⏰ Reminder set for 9:00 PM: Take medicine.”
```

#### 🔹 Intermediate Prompt

“Remind me to call Mom at 6 PM and send a gentle nudge 10 minutes earlier.”

#### Output:

“⏰ Reminder set: Call Mom at 6:00 PM (early nudge at 5:50 PM).”

#### 🔹 Advanced Prompt

```
“You are my assistant. Remind me about my 3 PM client call. If I don’t acknowledge the reminder, prompt me again in 5 minutes.”
```
#### Output:

“⏰ Reminder set for 3 PM client call. Follow-up reminder at 3:05 PM if not acknowledged.”

### D) Wellness Tips Generator
#### 🔹 Simple Prompt

“Give me a wellness tip.”

#### Output:

“💧 Drink one glass of water every two hours.”

#### 🔹 Intermediate Prompt

```
“I’ve been working long hours today. Suggest a short wellness activity I can do between meetings.”
```

#### Output:

“🧘 Try a 3-minute stretch at your desk to release tension in your neck and shoulders.”

#### 🔹 Advanced Prompt

````
“You are my wellness advisor. Suggest one actionable wellness tip for today. I’ve been skipping hydration tips, so give me something different.”
````

#### Output:

“👀 Use the 20-20-20 rule: every 20 minutes, look at something 20 feet away for 20 seconds to reduce eye strain.”

### E) General Query Handling
#### 🔹 Simple Prompt

```
“What’s a quick breakfast idea?”
```

#### Output:

“🍳 Scrambled eggs with toast, oatmeal with fruit, or a smoothie.”

#### 🔹 Intermediate Prompt

```
“Suggest three healthy lunch options I can cook in under 30 minutes.”
```

#### Output:

“🥗 Quinoa salad, 🥪 Grilled chicken wrap, 🍲 Vegetable stir-fry.”

#### 🔹 Advanced Prompt

```
“As my productivity assistant, recommend three science-backed morning routines that boost focus and energy. Keep it short and practical.”
```

#### Output:

“☀️ Morning Routines:

- 10 minutes of light exercise (increases alertness).

- Write down 3 goals for the day (clarity & focus).

- 5 minutes of meditation (reduces stress).”

![lMB7i_9bF57W](https://github.com/user-attachments/assets/18160915-2f07-489f-9479-4da859b45965)


## 3. Simulated CLI Interaction (Example Flow)

```
> User: Add “Prepare presentation slides by 5 PM.”  
Assistant: ✅ Added task with deadline 5 PM.  

> User: I have a meeting at 2 PM. Any free time in the morning?  
Assistant: You’re free from 9–12. Would you like me to schedule slide preparation then?  

> User: Yes, do it.  
Assistant: 📅 Scheduled: Presentation slides (9–11 AM).  

> User: Give me a wellness tip.  
Assistant: 🌿 Take a 5-minute walk after your morning task to refresh your focus.  

> User: Suggest a productivity hack for afternoons.  
Assistant: 🕑 Use the Pomodoro Technique: 25 min work + 5 min break. Repeat 3 times, then take a longer 15 min break.  
```
## 4. Feedback & Adaptation

- If user skips hydration tips → fewer water reminders, more posture/exercise.

- If user accepts long detailed summaries → assistant switches from short bullet points to paragraph-style summaries.

- If user often ignores reminders → assistant adds escalation strategy (repeat notifications).

![Prompt_Engineering](https://github.com/user-attachments/assets/5924c20a-373a-4a64-8d41-4aadc9411be9)


## 5. Expected Output (Summary Features)

### Personal Productivity Assistant Features:

- Daily Task Manager

     - Accept tasks in natural language.

     - Organize by urgency/deadline.

     - Provide summaries (morning/evening).

- Smart Scheduler

     - Context-aware scheduling.

     - Conflict detection & resolution.

     - Balances productivity + wellness.

- Reminder System

     - Flexible reminders (early nudges, repeats).

     - Smart escalation if ignored.

- Wellness Tips Generator

     - Daily, short actionable tips.

     - Adaptive suggestions based on user feedback.

- General Query Handling

     - Contextual, natural responses.

     - Productivity, wellness, lifestyle queries.

- Adaptation & Personalization

     - Learns preferences over time.

     - Adjusts tone, detail, and suggestions.
      
# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
