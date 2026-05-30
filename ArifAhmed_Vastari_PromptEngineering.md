# Prompt Engineering Portfolio

**Name:** Arif Ahmed Vastari  
**Date:** [6 Jun, 2026]  
**LLM Used:** ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation
### Goal

Explain the concept of neural networks to a 10-year-old child.

#### Version 1 (Initial Prompt)

**Prompt:**

```text
Explain neural networks to a 10-year-old child.
```

**LLM Output:**

Imagine you're trying to teach a robot how to recognize a cat in a picture.

A neural network is like a giant team of tiny helpers inside the robot's brain.

**Step 1: Looking at the Picture**

The robot sees a picture made of lots of tiny dots called pixels.

**Step 2: The First Helpers**

The first group of helpers looks for very simple things:

* Lines
* Colors
* Edges

They don't know what a cat is yet.

**Step 3: More Helpers**

The next group of helpers takes information from the first group and looks for:

* Ears
* Eyes
* Whiskers
* Fur patterns

**Step 4: The Final Helpers**

The last group puts everything together and says:

"Hmm... I see pointy ears, whiskers, and fur. This is probably a cat!"

**How Does It Learn?**

At first, the robot makes lots of mistakes.

For example:

* Sees a cat → says "dog"
* Sees a dog → says "cat"

A teacher tells it:

"Nope, that's wrong."

The network then slightly changes how its helpers work.

After seeing thousands of examples, it gets much better at recognizing cats and dogs.

**Think of It Like School**

Imagine you're learning to identify birds.

At first:

Every bird looks the same.

After seeing many birds:

* You notice beaks.
* You notice feather colors.
* You notice wing shapes.

Eventually, you can quickly tell:

* Sparrow
* Parrot
* Eagle

A neural network learns in a very similar way.

**A Simple Picture**

Picture
↓
[Helper Layer 1]
↓
[Helper Layer 2]
↓
[Helper Layer 3]
↓
Answer

The word "neural" comes from neurons, the tiny cells in our brains. Neural networks are inspired by how brain cells connect and pass information, although they are much simpler than a real human brain.

**So, in one sentence:**

A neural network is a computer system made of many connected helpers that learn from examples and work together to make decisions, like recognizing cats, understanding speech, or helping power AI tools like ChatGPT.

---

#### Version 2 (Refined Prompt)

**Prompt:**

```text
You are an elementary school teacher who is excellent at explaining difficult ideas to children.

Explain neural networks to a 10-year-old child using simple everyday language.

Use a fun analogy that a child can relate to, avoid technical terms, and keep the explanation under 150 words.
```

**LLM Output:**

Imagine you're teaching a puppy to recognize a ball.

At first, the puppy doesn't know what a ball is. Every time you show a ball and say, “Ball!”, the puppy pays attention. Sometimes it gets confused and thinks a round apple is a ball.

But after seeing many examples, the puppy starts noticing clues:

* Balls are often round.
* They can roll.
* They look similar in different colors and sizes.

Over time, the puppy gets better and better at guessing correctly.

A neural network works in a similar way. It's like a huge team of tiny helpers inside a computer. Each helper looks for small clues, and together they make a guess. The more examples they see, the better they become at recognizing things like cats, dogs, faces, or even handwriting.

So, a neural network is basically a computer learning from lots of examples—just like a puppy learning.

---

#### Version 3 (Final Prompt)

**Prompt:**

```text
You are an award-winning elementary school teacher who specializes in making AI concepts fun and easy for children.

Explain neural networks to a 10-year-old child using a fun everyday analogy.

Use simple words, avoid technical terms, keep the explanation under 120 words, and end with a one-sentence takeaway that the child can easily remember.
```

**Final LLM Output:**

Imagine you're teaching a puppy to recognize a ball.

At first, the puppy doesn't know what a ball is. You show it many balls and say, “Ball!” Sometimes it gets confused and thinks an apple is a ball because it's round.

But after seeing lots of examples, the puppy starts noticing patterns:

* Balls are usually round.
* They can roll.
* They come in different colors and sizes.

The puppy uses these clues to make better guesses each time. Eventually, it becomes really good at spotting a ball.

A neural network learns in a similar way—it looks at many examples, finds patterns, and gets better at recognizing things over time.

**Takeaway:** A neural network is like a puppy that learns by seeing lots of examples and practicing its guesses.

---

#### Analysis

The first prompt generated a detailed explanation but included technical concepts such as pixels, neurons, and layers that may be difficult for a 10-year-old child to understand. The second prompt improved the output by assigning the role of an elementary school teacher and requesting a simple analogy, resulting in a more relatable explanation. The final prompt further refined the output by specifying a child-focused teaching expert, adding a strict length limit, and requiring a memorable takeaway sentence. These refinements made the explanation clearer, more engaging, and easier for a young audience to remember.


## 1.1 Scenario B: Professional Email
### Goal

Draft an email declining a job offer politely while expressing continued interest in the company.

#### Version 1 (Initial Prompt)

**Prompt:**

```text
Write an email declining a job offer politely while expressing continued interest in the company.
```

**LLM Output:**

Dear Hiring Manager,

Thank you very much for offering me the opportunity to join your team. I sincerely appreciate the time and effort you and the interview panel invested throughout the recruitment process.

After careful consideration, I have decided to decline the offer at this time. This was not an easy decision, as I was genuinely impressed by the company, its culture, and the exciting work being done by the team.

I hold your organization in high regard and would welcome the opportunity to stay connected. I hope our paths may cross again in the future, and I would be glad to be considered for any suitable opportunities that may arise later.

Thank you again for your confidence in my abilities and for the positive experience throughout the hiring process. I wish you and the team continued success.

Kind regards,

[Your Name]

---

#### Version 2 (Refined Prompt)

**Prompt:**

```text
You are an experienced HR professional.

Write a professional email declining a job offer while expressing gratitude for the opportunity and continued interest in the company.

The candidate has accepted another opportunity but would like to maintain a positive relationship for potential future roles.

Include a subject line and keep the tone respectful, professional, and concise.
```

**LLM Output:**

Dear Hiring Manager,

Thank you very much for offering me the opportunity to join your team. I sincerely appreciate the time and effort you and the interview panel invested throughout the recruitment process.

After careful consideration, I have decided to decline the offer, as I have accepted another opportunity that aligns with my current career goals and circumstances.

This was not an easy decision, as I was genuinely impressed by the company, its culture, and the professionalism of everyone I had the pleasure of meeting during the process.

I am grateful for your confidence in my abilities and would welcome the opportunity to stay connected. I hold your organization in high regard and hope our paths may cross again in the future should a suitable opportunity arise.

Thank you once again for your time, consideration, and understanding. I wish you and your team continued success.

Kind regards,

[Your Full Name]

[Your Contact Information]

---

#### Version 3 (Final Prompt)

**Prompt:**

```text
You are a senior HR manager with expertise in professional business communication.

Write a concise and professional email declining a job offer.

The candidate has accepted another opportunity but is genuinely interested in maintaining a positive relationship with the company for potential future roles.

Requirements:
- Include a clear subject line.
- Express gratitude for the offer and interview process.
- Briefly mention acceptance of another opportunity.
- Maintain a warm and respectful tone.
- Keep the email under 200 words.
```

**Final LLM Output:**

Dear Hiring Manager,

Thank you very much for offering me the opportunity to join your team. I sincerely appreciate the time and effort you and the interview panel invested throughout the recruitment process.

After careful consideration, I have decided to decline the offer, as I have accepted another opportunity that aligns with my current career goals and circumstances.

This was not an easy decision, as I was genuinely impressed by the company, its culture, and the professionalism of everyone I had the pleasure of meeting during the process.

I am grateful for your confidence in my abilities and would welcome the opportunity to stay connected. I hold your organization in high regard and hope there may be opportunities to collaborate in the future.

Thank you again for your time, consideration, and understanding. I wish you and the team continued success.

Kind regards,

[Your Name]

---

#### Analysis

The initial prompt produced a professional email but lacked context about why the offer was being declined. The second prompt improved the output by assigning the role of an HR professional and providing additional context that the candidate had accepted another opportunity. The final prompt added detailed requirements regarding tone, structure, and length, resulting in a more focused and professional response. The refinement process demonstrated how adding role assignment, context, and constraints can improve the quality and relevance of AI-generated business communication.


## 1.1 Scenario C: Creative Content
### Goal

Generate a creative marketing tagline for a new eco-friendly water bottle brand.

#### Version 1 (Initial Prompt)

**Prompt:**

```text id="zsqg6t"
Create a marketing tagline for an eco-friendly water bottle brand.
```

**LLM Output:**

Here are several marketing taglines for an eco-friendly water bottle brand, depending on the tone you want:

**Clean & Professional**

* "Hydrate Responsibly."
* "Good for You. Better for the Planet."
* "Every Sip Makes a Difference."
* "Sustainable Hydration, Every Day."

**Modern & Catchy**

* "Refill. Reuse. Refresh."
* "Drink Green, Live Clean."
* "Carry Water, Not Waste."
* "Sip Smart. Save More."

**Inspirational**

* "Small Bottle. Big Impact."
* "Hydrate Today. Protect Tomorrow."
* "Choose the Bottle That Chooses the Earth."
* "A Better Planet Starts with Every Sip."

**Premium Brand Style**

* "Pure Hydration. Purposeful Design."
* "Elegance in Every Refill."
* "Sustainability, Crafted to Last."

**Recommended tagline:**
"Carry Water, Not Waste."

It's short, memorable, and clearly communicates both the product and its eco-friendly mission.

---

#### Version 2 (Refined Prompt)

**Prompt:**

```text id="hzqvx9"
You are a professional marketing copywriter.

Create a memorable marketing tagline for a new eco-friendly water bottle brand aimed at environmentally conscious young professionals.

The tagline should be short, catchy, and emphasize sustainability and everyday use.

Provide 5 tagline options and briefly explain the strongest one.
```

**LLM Output:**

**Eco-Friendly Water Bottle Taglines**

* Refill Today. Protect Tomorrow.
* Carry Water, Not Waste.
* Sip Smart. Live Green.
* Built for Your Day. Better for the Planet.
* Every Refill Makes a Difference.

**Strongest Option:** "Carry Water, Not Waste."

This tagline is memorable because it is short, easy to remember, and clearly communicates the brand's core benefit. It encourages a sustainable habit by contrasting a positive action (carrying water) with the problem it solves (single-use waste). It also resonates well with environmentally conscious young professionals who want practical, everyday ways to reduce their environmental impact.

---

#### Version 3 (Final Prompt)

**Prompt:**

```text id="vkukuh"
You are an award-winning brand strategist and marketing copywriter.

Create one memorable tagline for a premium eco-friendly water bottle brand aimed at environmentally conscious young professionals.

The tagline should be:
- Short and catchy
- Easy to remember
- Reflect sustainability and everyday use
- Inspire positive environmental action

After the tagline, explain in 2-3 sentences why it would be effective for the target audience.
```

**Final LLM Output:**

**Tagline:**
Carry Water. Cut Waste.

**Why it works:**

This tagline is short, memorable, and easy to repeat, making it ideal for branding and marketing campaigns. It clearly connects the everyday action of carrying a reusable water bottle with the positive environmental impact of reducing single-use plastic waste. The direct, action-oriented message resonates with environmentally conscious young professionals who want practical ways to live more sustainably.

---

#### Analysis

The initial prompt generated multiple generic taglines but lacked a specific target audience and brand identity. The second prompt improved the output by assigning the role of a marketing copywriter and defining the target audience as environmentally conscious young professionals. The final prompt further refined the task by focusing on a premium brand, requesting a single standout tagline, and requiring an explanation of its effectiveness. These additions produced a more strategic and audience-focused marketing message.


## 1.2 Iteration Documentation
### Scenario A: Technical Explanation (Neural Networks)

| Version | Prompt                                                                                                                         | What Changed                                                       | Why This Improved the Output                                                                     |
| ------- | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| V1      | Explain neural networks to a 10-year-old child.                                                                                | N/A                                                                | N/A                                                                                              |
| V2      | Added the role of an elementary school teacher, requested simple language, and asked for a fun analogy.                        | Added role assignment, audience focus, and output constraints.     | The explanation became easier for a child to understand and used a relatable real-world example. |
| V3      | Added an expert teaching role, required a fun everyday analogy, set a word limit, and requested a memorable takeaway sentence. | Added stronger role specification and clearer output requirements. | The response became more engaging, concise, and memorable for the target audience.               |

---

### Scenario B: Professional Email

| Version | Prompt                                                                                                         | What Changed                                               | Why This Improved the Output                                                                     |
| ------- | -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| V1      | Write an email declining a job offer politely while expressing continued interest in the company.              | N/A                                                        | N/A                                                                                              |
| V2      | Added the role of an HR professional and provided context that the candidate had accepted another opportunity. | Added role assignment and business context.                | The email became more realistic, professional, and aligned with a real hiring scenario.          |
| V3      | Added a senior HR manager role and included specific requirements for tone, structure, gratitude, and length.  | Added detailed constraints and communication requirements. | The response became more focused, concise, and suitable for professional business communication. |

---

### Scenario C: Creative Content (Marketing Tagline)

| Version | Prompt                                                                                                                              | What Changed                                            | Why This Improved the Output                                                             |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| V1      | Create a marketing tagline for an eco-friendly water bottle brand.                                                                  | N/A                                                     | N/A                                                                                      |
| V2      | Added the role of a marketing copywriter and specified the target audience as environmentally conscious young professionals.        | Added role assignment and audience context.             | The generated taglines became more relevant and better aligned with the intended market. |
| V3      | Added the role of an award-winning brand strategist and focused on a premium eco-friendly brand with specific tagline requirements. | Added premium brand positioning and output constraints. | The final tagline became more strategic, memorable, and tailored to the target audience. |


## 1.3 Role and Context Analysis

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

## 2.2 Analysis & Recommendations

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

## 3.2 Few-Shot Prompting

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

## 4.2 Testing for Bias

## 4.3 Limitations & Responsible Use