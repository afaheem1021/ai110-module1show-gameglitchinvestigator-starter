# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?


- What did the game look like the first time you ran it?

when I started the application, Streamlit opened in a new browser tab and showed the Game Glitch Investigator game


- List at least two concrete bugs you noticed at the start  

The hints lied, who when my guess was too high the game said go higher while it was suppose to tell me to go lower
and, the game does not reset



**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
| 50    |    go lower       |      GO HIGHER  |  none
| 10    |    go higher      |    GO LOWER!    |  none                   
| new game |  starts new game|  you already won|  none 

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?

I used Cursor AI extension for this project.

- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).

The AI corrected the wrong behavior of the hints, it saw that and fixed the hints so now after running it the hints display correctly, it also perfeclty fixed the starting a new game. 

- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

  The AI gave me strong code, and understood my project and was able to make the correct propper changes.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?

I manually ran the application in my browser, and tried different numbers to see if the hints were displaying correctly and they were, and the new game button also worked

- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.

py test was ran after moving check_guess into logic_utils.py. All four tests passed, 

- Did AI help you design or understand any tests? How?

Yes, the AI did desgin the tests and made the changes, it passed all 4 tests. 

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

everytime user interacts with the app, streamlit reruns the whole app.py file again which is refered as a rerun, st.session_state helps to keep the memory so it doesnt reset each time. 

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.

Learning to use Git, still learning as this is my first time, used AI to help with that but I do plan on watching Tutorials later to learn it as its very important


- What is one thing you would do differently next time you work with AI on a coding task?

Trying to debug and read the code myself before delegating it to AI, developing an understanding before relying on AI

- In one or two sentences, describe how this project changed the way you think about AI generated code.

I was extremely impressed by how good AI was able to code and understand the project as a whole. AI models are continuing to get better so its important to learn how to prompt to them well.
