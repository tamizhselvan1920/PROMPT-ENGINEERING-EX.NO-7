# Exno.7 
-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Name: 
THAMIZH SELVAN R
# Register no.
212222230158
# Aim: 
To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

# Algorithm:
Develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

# Key Concepts Involved:  <br>
Prompt Engineering <br>
Natural Language Processing (NLP) <br>
Task Management <br>
API Integration<br>
Progressive AI Design Thinking <br> 

# Basic Instruction: <br> 
This is the most straightforward way to prompt an AI. You give it a list of tasks and ask it to organize or structure them, assuming it has the context or general knowledge to do so. <br> 

# Prompt: <br>
"Organize the following tasks for today: Buy groceries, Finish project report, Call the dentist, Workout, Check emails." <br> 

# Output: <br>
Finish project report <br>
Call the dentist <br>
Check emails <br>
Buy groceries <br> 
Workout <br>

# Use: <br> 
Simple to-do list generation with default prioritization logic. <br> 

# Behavior: <br> 
Assumes general rules: deadlines > appointments > routines. <br>
Doesn’t adapt to personal user preferences unless pre-trained. <br> 

# Real-World Value: <br> 
Quick, frictionless task prioritization. <br> 
Good for first-time users or simple apps. <br> 

# Example-Based Instruction: <br> 
Provide a few input-output examples before asking the model to perform a similar task. It helps the model infer your logic or preferences. <br>

# Prompt: <br> 
"Here is how I like my tasks organized: <br> 

Tasks: [Pay electricity bill, Read 1 chapter, Jog]

# Output: <br> 
Jog <br>
Pay electricity bill <br>
Read 1 chapter <br>
Now organize: [Buy groceries, Finish project report, Call dentist, Workout, Check emails]" <br> 

# Output: <br> 
Workout <br>
Call dentist <br>
Finish project report <br> 
Check emails <br> 
Buy groceries <br>

# Use: <br>
Learning user preferences and customizing routines accordingly. <br>

# Behavior: <br>
Learns that time-sensitive tasks come first. <br>
May mimic specific phrasing or order. <br>

# Real-World Value: <br>
Allows your app to "learn" from user-provided habits. <br>
Supports recurring task routines (e.g., “Always meditate first”). <br> 

# Step-by-Step Reasoning: <br>
Asks the model to explain its logic before giving the final output. This makes the decision-making transparent and often more accurate. <br>

# Prompt: <br> 
"Organize these tasks for today and explain your reasoning: <br> 
[Buy groceries, Finish project report, Call dentist, Workout, Check emails]"

# Output: <br>
First, high-priority and time-sensitive tasks: <br>
Finish project report (deadline-driven) <br>
Call dentist (appointment windows) <br>

Then, medium-priority: <br> 
Check emails (flexible timing but necessary) <br> 

Finally, flexible tasks: <br>
Buy groceries <br>
Workout <br>

Final Order: <br>
Finish project report <br>
Call dentist <br>
Check emails <br>
Buy groceries <br>
Workout <br>

# Use: <br>
AI explains task reasoning, giving users transparency and trust. <br>

# Behavior: <br>
Gives detailed reasoning. <br> 
Builds trust and lets users modify based on logic. <br>
Real-World Value: <br>
Useful in productivity coaching or mental wellness apps. <br>
Users appreciate transparent AI. <br>

# Personalized Assistant: <br>
Define the AI's role or personality—like a coach, executive assistant, or productivity expert—and have it respond accordingly. <br>

# Prompt: <br>
"You are my personal productivity coach. Organize my daily tasks with priorities and include time estimates: <br>
[Buy groceries, Finish project report, Call dentist, Workout, Check emails]" <br>

# Output: <br>
Daily Schedule: <br>
9:00 AM - Finish project report (2 hrs) <br>
11:00 AM - Call dentist (15 min) <br>
11:15 AM - Check emails (30 min) <br>
12:00 PM - Buy groceries (1 hr) <br>
1:00 PM - Workout (1 hr) <br>

# Behavior: <br>
Adds context, breaks, personality. <br> 
Suggests wellness tips, routines, even motivational comments. <br>

# Real-World Value: <br>
Great for wellness apps or coaching platforms. <br>
Gives a human-like feeling to the interaction. <br>

With Voice/Image Inputs: <br>
Use non-textual input—voice, handwriting, screenshots—to extract tasks and structure them intelligently. <br> 

Voice Input Example: <br> 
User: "I need to drop off the package, email my boss, do the laundry, and book my vaccine appointment." <br>

Prompt (internally transcribed): <br>
"Organize these tasks from voice input: Drop off package, Email boss, Do laundry, Book vaccine appointment." <br> 

# Image Input Example: <br>
Image: A whiteboard with handwritten tasks: <br>
“Dentist 3PM, Fix resume, Clean desk, Meds refill” <br>

Prompt (internally OCR’d): <br>
"Organize tasks from this list: Dentist 3PM, Fix resume, Clean desk, Meds refill." <br>

Expected Output: <br>
Dentist 3PM <br>
Fix resume <br>
Meds refill <br>
Clean desk <br>

Behavior: <br> 
Parses raw input (voice/image) into a structured plan. <br>
Supports accessibility and natural user input. <br>

Real-World Value: <br>
Great for mobile productivity tools. <br>
Helps users avoid typing and stay hands-free. <br> 

Table:

<img width="1136" height="391" alt="Screenshot 2025-12-20 194542" src="https://github.com/user-attachments/assets/aabe9379-b6a9-4f00-8a73-623f2721cc4a" /> <br>

Final Recommendation: <br>
To create a scalable and intelligent task app, combine all five techniques: <br>
Start with zero-shot for new users. <br>
Let users train it with a few-shot example set. <br>
Offer reasoning for trust and insight. ,br>
Add role-based personas for advanced planning. <br>
Use voice/image inputs for convenience and accessibility. <br> 

# Result: 
The Prompt is executed successfully. 
