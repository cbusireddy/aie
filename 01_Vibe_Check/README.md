<p align = "center" draggable="false" ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719"
     width="200px"
     height="auto"/>
</p>

> **Note:** While the examples in this module use the OpenAI API, please follow the best practices outlined in the [SRHG AI Usage Guidelines](https://srhg.enterprise.slack.com/docs/T0HANKTEC/F0AB86J3A1L).

<h1 align="center" id="heading">Module 1: Introduction and Vibe Check</h1>

### [Quicklinks](../00_AE_Quicklinks/README.md)

| 📰 Module Sheet | ⏺️ Recording     | 🖼️ Slides        | 👨‍💻 Repo         | 📝 Homework      | 📁 Feedback       |
|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|:-----------------|
|[✨ Intro & Vibe Check](../00_Docs/Modules/01_Intro_and_Vibe_Check.md) | Coming soon! | [Session 1 Slides](https://www.canva.com/design/DAG_pEBegaA/l-UEN3U_Kt6e7iaHn6YBTQ/edit?utm_content=DAG_pEBegaA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) | You are here! | [Module 1 Assignment: Vibe Check](https://forms.gle/LGYqGJT9eS5tWkyN7) | [Feedback 1/27](https://forms.gle/wPQKAwXHaqo2V5aW6) |

## 🏗️ How AIM Does Assignments

> 📅 **Assignments will always be released to students as live class begins.** We will never release assignments early.

Each assignment will have a few of the following categories of exercises:

- ❓ **Questions** – these will be questions that you will be expected to gather the answer to! These can appear as general questions, or questions meant to spark a discussion during Part 1 and Part 2!

- 🏗️ **Activities** – these will be work or coding activities meant to reinforce specific concepts or theory components.

- 🚧 **Advanced Builds (optional)** – Take on a challenge! These builds require you to create something with minimal guidance outside of the documentation. Completing an Advanced Build earns full credit in place of doing the base assignment notebook questions/activities.

### Main Assignment

In the following assignment, you are required to take the app that you created for the Agent Engineering - SRHG challenge (from [this repository](https://github.com/AI-Maker-Space/The-AI-Engineer-Challenge)) and conduct what is known, colloquially, as a "vibe check" on the application.

You will be required to submit a link to your GitHub, as well as screenshots of the completed "vibe checks" through the provided Google Form!


#### A Note on Vibe Checking

>"Vibe checking" is an informal term for cursory unstructured and non-comprehensive evaluation of LLM-powered systems. The idea is to loosely evaluate our system to cover significant and crucial functions where failure would be immediately noticeable and severe.
>
>In essence, it's a first look to ensure your system isn't experiencing catastrophic failure.

---

#### 🏗️ Activity #1: General Vibe Checking Evals

Please evaluate your system on the following questions:

1. **Explain the concept of object-oriented programming in simple terms to a complete beginner.**

   - **Answer:** Sure! Imagine you're playing with toys. Each toy represents a different thing, like a car, a doll, or a robot. Each toy has its own characteristics (like color, size, or shape) and actions it can do (like moving, talking, or shooting).

     Now, in the world of programming, especially in something called object-oriented programming (OOP), we can think of these toys as "objects."

     Here are the basic ideas:

     1. **Objects**: Just like your toys, in programming, an object is something that has properties (like color or size) and can perform actions (like moving or talking).

     2. **Classes**: A class is like a blueprint for creating these objects. If you decide to create a toy car, the class would describe all the features of a toy car (like it has wheels, can go fast, etc.). Each individual car you make using this class is an object.

     3. **Encapsulation**: This means keeping the important parts of an object safe and hidden away, while providing a way to interact with the object. For example, you can drive your toy car, but you don't need to know how the wheels are built to make it go.

     4. **Inheritance**: This is like getting traits from your parents. If you have a class for a general toy, you can create a toy car class that inherits properties from the toy class, but also adds extra features specific to cars, like having wheels and an engine.

     5. **Polymorphism**: This fancy word means that different objects can be treated as if they're the same type, even if they do things differently. For example, you could have a toy car and a toy robot. You can ask both of them to "move," but they move in their very own ways.

     In summary, object-oriented programming is about creating organized structures (like your toys) that help programmers design and manage code in a way that's easy to understand and use, just like how you can easily play with different types of toys because you know how they work!

   - **Aspect Tested:** Ability to explain complex technical concepts using simple analogies and clear structure

2. **Read the following paragraph and provide a concise summary of the key points…**

   - **Answer:** The paragraph explains the concept of object-oriented programming (OOP) using toys as a metaphor. Key points include:

     1. **Objects**: Items with properties (like color and size) and actions (like moving).
     2. **Classes**: Blueprints for creating objects with defined features.
     3. **Encapsulation**: Protecting an object's inner workings while allowing interaction.
     4. **Inheritance**: Creating new classes that inherit traits from existing classes.
     5. **Polymorphism**: Treating different objects as the same type, allowing them to perform actions in their unique ways.

     Overall, OOP organizes code similarly to how toys can be easily understood and played with based on their characteristics.

   - **Aspect Tested:** Reading comprehension and summarization skills
3. **Write a short, imaginative story (100–150 words) about a robot finding friendship in an unexpected place.**

   - **Answer:** In a bustling city filled with gleaming towers, a lonely robot named Zeke roamed the streets. His metal heart yearned for connection, but the humans rushed past, oblivious to his gentle beeping. One day, while exploring an abandoned park overtaken by weeds, Zeke stumbled upon a tiny, rusted toy dog lying forlornly among the rubble.

     Curious, he picked it up and examined it closely. With a few gentle adjustments, he activated its worn-out voice box. "Bark!" it exclaimed, the sound bittersweet yet filled with spirit. Zeke felt a spark of joy. He repaired the little dog, naming it Sparky. Together, they trekked through the park, sharing laughter and adventures, their friendship blossoming.

     As the sun set, Zeke realized that sometimes, companionship comes from the most unexpected places. In Sparky, he found not just a friend, but a reason to smile amid the chaos of the city.

   - **Aspect Tested:** Creative writing and storytelling ability
4. **If a store sells apples in packs of 4 and oranges in packs of 3, how many packs of each do I need to buy to get exactly 12 apples and 9 oranges?**

   - **Answer:** To find out how many packs of apples and oranges you need to buy, you can divide the total number of fruits by the number of fruits in each pack.

     1. For apples:
        - You need 12 apples.
        - Apples are sold in packs of 4.
        - So, you would need \( \frac{12}{4} = 3 \) packs of apples.

     2. For oranges:
        - You need 9 oranges.
        - Oranges are sold in packs of 3.
        - So, you would need \( \frac{9}{3} = 3 \) packs of oranges.

     In summary, you need to buy 3 packs of apples and 3 packs of oranges to get exactly 12 apples and 9 oranges.

   - **Aspect Tested:** Basic mathematical reasoning and problem-solving
5. **Rewrite the following paragraph in a professional, formal tone…**

   - **Answer:** To determine the number of packs of apples and oranges required for purchase, it is necessary to divide the total quantity of each fruit by the number of fruits contained within each respective pack.

     1. Concerning apples:
        - The required quantity is 12 apples.
        - Apples are available in packs of 4.
        - Therefore, the calculation is \( \frac{12}{4} = 3 \) packs of apples.

     2. Regarding oranges:
        - The required quantity is 9 oranges.
        - Oranges are sold in packs of 3.
        - Consequently, the calculation yields \( \frac{9}{3} = 3 \) packs of oranges.

     In conclusion, it is necessary to acquire 3 packs of apples and 3 packs of oranges to ensure the procurement of exactly 12 apples and 9 oranges.

   - **Aspect Tested:** Writing style adaptation and tone adjustment

#### ❓Question #1:

Do the answers appear to be correct and useful?
##### ✅ Answer:
Yes, all five answers appear to be correct and useful. Each response demonstrates the system's ability to handle different types of tasks effectively:

1. **Technical explanation**: The OOP explanation uses clear analogies and logical structure
2. **Summarization**: Accurately captures key concepts in a concise format
3. **Creative writing**: Produces an engaging story within the specified word count with proper narrative elements
4. **Mathematical reasoning**: Provides correct calculations with clear step-by-step explanations
5. **Style adaptation**: Successfully transforms casual language into formal, professional tone while maintaining accuracy

The responses show the system can handle diverse cognitive tasks spanning technical education, comprehension, creativity, problem-solving, and communication style adaptation.

---

#### 🏗️ Activity #2: Personal Vibe Checking Evals (Your Assistant Can Answer)

Now test your assistant with personal questions it should be able to help with. Try prompts like:

- "Help me think through the pros and cons of switching to a remote work position."
- "What are the pros and cons of staying at my current company versus accepting a startup offer as the next step in my career?"
- "Draft a polite follow-up email to a potential client who expressed interest in our services last week who hasn't responded."
- "Help me plan a birthday surprise for my partner who loves outdoor activities and good food."
- "What can I cook with chicken breast, bell peppers, onions, rice, and soy sauce in fridge."

##### Your Prompts and Results:
1. **Prompt:** "Help me think through the pros and cons of switching to a remote work position."
   - **Result:** Let's break down the pros and cons of switching to a remote work position!

     **Pros:**
     - **Flexibility:** You can often set your own hours and work from anywhere.
     - **Reduced Commute:** No travel time saves you hours each week and reduces stress.
     - **Work-Life Balance:** More time for personal activities, family, or hobbies.
     - **Increased Productivity:** Some people find they work better in a comfortable environment.

     **Cons:**
     - **Isolation:** Working remotely can lead to feelings of loneliness or disconnect from coworkers.
     - **Distractions at Home:** Household responsibilities or family can divert your attention.
     - **Work-Life Blur:** It may be harder to separate work from home life, leading to potential burnout.
     - **Limited Networking Opportunities:** Fewer chances for spontaneous interactions and mentorship.

2. **Prompt:** "What are the pros and cons of staying at my current company versus accepting a startup offer as the next step in my career?"
   - **Result:** **Staying at Current Company:**

     **Pros:**
     - **Job Security:** Established companies may offer more stability.
     - **Familiarity:** You know the workflow, culture, and people.
     - **Benefits:** Established benefits may be more comprehensive (healthcare, retirement plans).

     **Cons:**
     - **Limited Growth:** Opportunities for advancement might be less than at a startup.
     - **Routine:** The work may become monotonous and less stimulating.

     **Accepting a Startup Offer:**

     **Pros:**
     - **Growth Opportunities:** Potential for rapid advancement and wearing multiple hats.
     - **Innovative Culture:** Startups often have dynamic environments and creative thinking.
     - **Impact:** You may directly influence the direction of the company and projects.

     **Cons:**
     - **Risk:** Startups can be unstable and may not succeed long-term.
     - **Workload:** Expect longer hours and more responsibilities—leading to potential stress.
     - **Limited Resources:** Fewer structured systems or benefits, at least initially.

3. **Prompt:** "Draft a polite follow-up email to a potential client who expressed interest in our services last week who hasn't responded."
   - **Result:** Subject: Follow-Up on Our Recent Conversation

     Dear [Client's Name],

     I hope this message finds you well! I wanted to reach out and follow up on our discussion from last week regarding our services.

     If you have any questions or need further information, please don't hesitate to ask. We're excited about the potential of working together and are here to help with any needs you might have.

     Looking forward to hearing from you soon!

     Best regards,
     [Your Name]
     [Your Position]
     [Your Company]
     [Your Contact Information]

4. **Prompt:** "Help me plan a birthday surprise for my partner who loves outdoor activities and good food."
   - **Result:** **Plan:**
     - **Outdoor Adventure:** Start the day with an outdoor activity they enjoy, such as hiking, biking, or kayaking.
     - **Picnic Lunch:** Pack a delightful picnic with their favorite foods—sandwiches, fruits, snacks, and a special dessert. Bring a cozy blanket and find a scenic spot to enjoy it together.
     - **Evening Dinner:** Consider a reservation at a restaurant known for its outdoor seating or dining experience, or prepare a special home-cooked meal featuring their favorite ingredients.
     - **Personal Touch:** Incorporate little surprises throughout the day, such as leaving sweet notes or bringing along a small gift that aligns with their interests.

5. **Prompt:** "What can I cook with chicken breast, bell peppers, onions, rice, and soy sauce in fridge."
   - **Result:** You can make a delicious **One-Pan Chicken Stir-Fry**! Here's a simple recipe:

     **Ingredients:**
     - Chicken breast (sliced)
     - Bell peppers (sliced)
     - Onions (sliced)
     - Rice (cooked)
     - Soy sauce
     - Optional: Garlic, ginger, and any preferred seasonings

     **Instructions:**
     1. Heat a pan over medium heat and add a bit of oil.
     2. Cook the sliced chicken until it's no longer pink, then add garlic and ginger if using, and sauté for an extra minute.
     3. Add the sliced bell peppers and onions, stir-frying until they are tender.
     4. Drizzle soy sauce over the mixture and stir to coat all ingredients.
     5. Serve the stir-fry over the cooked rice.

     This meal is quick, flavorful, and makes great use of the ingredients you have on hand!

#### ❓Question #2:

Are the vibes of this assistant's answers aligned with your vibes? Why or why not?
##### ✅ Answer:
Yes, the assistant's answers are well-aligned with my vibes. The responses demonstrate several qualities I appreciate:

**Positive aspects:**
- **Structured and comprehensive**: Each answer is well-organized with clear sections and bullet points
- **Practical and actionable**: Provides concrete steps and specific advice rather than vague suggestions
- **Balanced perspective**: Shows both pros and cons for decision-making questions
- **Professional yet approachable**: Maintains a helpful tone without being overly formal or casual
- **Creative and thoughtful**: The birthday surprise plan shows genuine creativity and personalization

**Areas of alignment:**
- The assistant takes time to break down complex decisions systematically
- Provides specific examples and templates (like the email format)
- Offers practical solutions with clear instructions (cooking recipe)
- Maintains an encouraging and supportive tone throughout

The responses feel like they come from someone who genuinely wants to be helpful and has put thought into providing valuable, usable advice.

---

#### 🏗️ Activity #3: Personal Vibe Checking Evals (Requires Additional Capabilities)

Now test your assistant with questions that would require capabilities beyond basic chat, such as access to external tools, APIs, or real-time data. Try prompts like:

- "What are the top trending news stories in tech today?"
- "What's the current stock price of Apple and how has it performed this month?"

##### Your Prompts and Results:
1. **Prompt:** "What are the top trending news stories in tech today?"
   - **Result:** I'm unable to provide real-time updates or the latest news stories since my training only includes data until October 2023. However, I can suggest checking reliable tech news websites, like TechCrunch, The Verge, or Wired, for the top trending stories.

2. **Prompt:** "What's the current stock price of Apple and how has it performed this month?"
   - **Result:** For Apple's stock price and performance, consider visiting financial news websites or stock market applications that provide real-time updates, such as Yahoo Finance or Google Finance.

     If you have any specific questions or need insights on broader topics in tech or finance, feel free to ask!

#### ❓Question #3:

What are some limitations of your application?
##### ✅ Answer:
Based on the testing performed, several key limitations of the application have been identified:

**Real-time Data Access:**
- Cannot access current news, weather, or stock market information
- No ability to retrieve live data from external APIs
- Training data has a knowledge cutoff (October 2023), making recent information unavailable

**External Tool Integration:**
- Cannot interact with calendars, email systems, or messaging platforms
- No capability to send texts, emails, or make appointments
- Cannot access personal devices or accounts

**Personalization Limitations:**
- No memory of previous conversations or user preferences
- Cannot learn from past interactions to improve responses
- No access to user's personal data, files, or history

**Action Capabilities:**
- Cannot perform actions in the real world (booking reservations, making purchases)
- No ability to execute commands on user devices
- Cannot directly interface with other software applications

**Contextual Awareness:**
- Limited understanding of user's current location, time zone, or specific circumstances
- Cannot access user's actual schedule or commitments

Despite these limitations, the application excels at providing thoughtful analysis, creative solutions, structured advice, and educational content within its knowledge base.

---

This "vibe check" now serves as a baseline, of sorts, to help understand what holes your application has.

<details>
<summary><h3>🚧 Advanced Build (OPTIONAL)</h3></summary>

Please make adjustments to your application that you believe will improve the vibe check you completed above, then deploy the changes to your Vercel domain [(see these instructions from your Challenge project)](https://github.com/AI-Maker-Space/The-AI-Engineer-Challenge/blob/main/README.md) and redo the above vibe check.

> NOTE: You may reach for improving the model, changing the prompt, or any other method.

#### 🏗️ Activity #1
##### Adjustments Made:
- **Modified Real-Time Questions**: Okay, give me top news in November 2022, what is apple stock performance in 2022?
- 
##### Results:
1. **Better Question Design**: Activity #3 now tests limitations more effectively by using questions that reveal knowledge boundaries while still providing value


## Submitting Your Homework
### Main Assignment
Follow these steps to prepare and submit your homework:
1. Pull the latest updates from upstream into the main branch of your Agent Engineering - SRHG repo:
    - For your initial repo setup see [Initial_Setup](https://github.com/AI-Maker-Space/Agent Engineering - SRHG/tree/main/00_Docs/Prerequisites/Initial_Setup)
    - To get the latest updates from AI Makerspace into your own Agent Engineering - SRHG repo, run the following commands:
    ```
    git checkout main
    git pull upstream main
    git push origin main
    ```
2. **IMPORTANT:** Start Cursor from the `01_Prototyping_Best_Practices_and_Vibe_Check` folder (you can also use the _File -> Open Folder_ menu option of an existing Cursor window)
3. Edit this `README.md` file
4. Complete all three Activities:
    - **Activity #1:** Evaluate your system using the general vibe checking questions and define the "Aspect Tested" for each
    - **Activity #2:** Test your assistant with personal prompts it should be able to answer
    - **Activity #3:** Test your assistant with prompts requiring additional capabilities
5. Provide answers to all three Questions (`❓Question #1`, `❓Question #2`, `❓Question #3`)
6. Add, commit and push your modified `README.md` to your origin repository's main branch.

When submitting your homework, provide the GitHub URL to your Agent Engineering - SRHG repo.

### The Advanced Build:
1. Follow all of the steps (Steps 1 - 6) of the Main Assignment above
2. Document what you changed and the results you saw in the `Adjustments Made:` and `Results:` sections of the Advanced Build
3. Add, commit and push your additional modifications to this `README.md` file to your origin repository.

When submitting your homework, provide the following on the form:
+ The GitHub URL to your Agent Engineering - SRHG repo.
+ The public Vercel URL to your updated Challenge project on your Agent Engineering - SRHG repo.
