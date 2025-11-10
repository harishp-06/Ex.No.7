# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Register no.212223060086

# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

# AI Tools Required: 

  -> ChatGPT (GPT-5 or GPT-4)

  -> (Optional) Python / Web interface for user interaction

  -> Prompt Engineering techniques

# Explanation: 

This experiment focuses on designing a Personal Productivity Assistant using prompt engineering.
The assistant should:

 ! Manage and organize daily tasks
 
 ! Set and schedule reminders
 
 ! Suggest wellness and productivity tips
 
 ! Answer general user queries
 
 ! Adapt to user preferences over time through feedback

## Prompt:
```
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
```
## Procedure:

### Step 1: Define Core Requirements
Identify the main functions of the assistant:


-> Task management

-> Scheduling and reminders

-> Wellness tips

-> General query answering

-> Preference adaptation


### Step 2: Construct Appropriate Prompts


| **Feature**                 | **Sample Prompt**                                                            | **Example Output**                                                                   |
| --------------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Task Manager**            | “Add ‘Finish AI report by 5 PM’ to my task list and show all pending tasks.” | Task List: <br> 1️⃣ Finish AI report – Due: 5 PM <br> 2️⃣ Attend team meeting – 3 PM |
| **Smart Scheduler**         | “Schedule a 30-min workout in the morning and show my free time slots.”      | 🗓 Free Time: 7–8 AM, 6–7 PM <br> ✅ Workout scheduled for 7:00–7:30 AM               |
| **Wellness Tips Generator** | “Give me today’s wellness advice.”                                           | 💡 Tip: Drink 2L of water and take a 10-min screen break every 2 hours.              |
| **General Query**           | “What’s the best way to improve focus while studying?”                       | 🧠 Response: Use the Pomodoro technique – study 25 mins, rest 5 mins.                |
| **Adaptive Behavior**       | “I prefer evening workouts. Update my schedule accordingly.”                 | 🔄 Acknowledged. Future workouts will be planned for 6:30–7:00 PM.                   |


### Step 3: Simulate Natural Interaction

Users interact conversationally:

```
User: Add “Submit project report” to my to-do list.  
Assistant: Added successfully. Deadline?  
User: Tomorrow 5 PM.  
Assistant: Task saved — Reminder set for 4:30 PM tomorrow.
```


### Step 4: Collect Feedback and Adapt

The assistant records user choices:


! Learns user’s preferred working hours

! Adapts wellness suggestions

! Prioritizes recurring activities


### Step 5 (Optional): Add Basic Memory (Simulated)

Simple data structure or JSON can be used to store preferences like:

```
{
  "preferred_workout_time": "evening",
  "reminder_style": "notifications",
  "favorite_wellness_tips": ["hydration", "stretching"]
}
```

# Expected Output (Example Response by LLM):

## Personal Productivity Assistant Features

### 1. Daily Task Manager

Accepts tasks via natural language (e.g., “Remind me to call mom at 6 PM”).

Organizes tasks by priority, deadline, and status.

Provides daily summaries and pending item lists.

### 2. Smart Scheduler

Understands context and schedules events automatically.

Detects overlapping events and suggests adjustments.

Provides available time slots.

### 3. Wellness Tips Generator

Suggests daily tips on hydration, exercise, and mental breaks.

Learns from past feedback and user preferences.

### 4. Adaptive Interaction

Learns from the user’s corrections or updates.

Changes tone and schedule preferences automatically.

# Sample Output (Simulated ChatGPT Response):

```
Hello 👋  
Here’s your plan for today:

🗓 9:00 AM – Team Meeting (Work)  
📘 11:00 AM – Write AI Report (Study)  
💪 6:30 PM – Workout (Personal)  
📞 8:00 PM – Call Parents (Reminder Set)

💡 Wellness Tip: Take a 10-minute walk after lunch to refresh your mind.
✅ You have 2 pending tasks from yesterday.
```

# Result: 

### The lab exercise successfully demonstrated how a prompt-based personal assistant can be built using ChatGPT.

Students were able to:


-> Understand how to tailor LLM prompts for real-life use cases.

-> Foster creativity by designing assistant features suited to personal or academic life.

-> Learn prompt engineering techniques for dynamic, natural conversations.

-> Experience the practical utility of generative AI in solving daily productivity challenges.



# Conclusion:

A prototype of a personal productivity assistant was created using prompt engineering. The application showcases how large language models like ChatGPT can simulate intelligent, context-aware personal assistants that adapt to user needs and improve efficiency in everyday life.
