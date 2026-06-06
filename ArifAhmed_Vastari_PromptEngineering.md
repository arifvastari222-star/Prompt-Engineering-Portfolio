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
### Role and Context Analysis

Role assignment and context setting significantly improved the quality of the AI-generated responses throughout this exercise. In Scenario A, assigning the role of an elementary school teacher encouraged the model to use simpler language, relatable analogies, and a teaching style that was appropriate for a 10-year-old audience. This made the explanation more engaging and easier to understand.

In Scenario B, assigning the role of an HR professional and providing context that the candidate had accepted another opportunity resulted in a more realistic and professional email. The additional context helped the model generate a response that aligned with real-world business communication practices.

In Scenario C, defining the role as a marketing copywriter and specifying the target audience as environmentally conscious young professionals produced more focused and relevant marketing content. The final output better reflected the brand identity and values of the intended audience.

Overall, role assignment helped shape the model's expertise and communication style, while context setting ensured that the responses were tailored to the intended audience and objective.


---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation
### Selected Task

Product Description for an Eco-Friendly Water Bottle

### Original Prompt

```text
Write a product description for an eco-friendly water bottle.
```

---

### Low Temperature (Simulated)

**Prompt Used:**

```text
Write a product description for an eco-friendly water bottle.

Keep the description factual, precise, and professional. Focus on features and benefits. Avoid creative language and exaggeration.
```

**Output:**

The Eco-Friendly Water Bottle is designed for everyday hydration while reducing reliance on single-use plastic bottles. Made from durable, reusable materials, it is lightweight, easy to carry, and suitable for work, travel, fitness, and daily activities.

The bottle features a leak-resistant lid to help prevent spills and a wide opening for convenient filling and cleaning. Its reusable construction supports long-term use, helping to reduce waste and promote more sustainable consumption habits.

**Key Features:**

* Reusable and durable design
* Leak-resistant lid
* Lightweight and portable
* Easy to clean and refill
* Suitable for daily use at home, work, or on the go

**Benefits:**

* Reduces dependence on disposable plastic bottles
* Supports environmentally responsible practices
* Provides a practical and cost-effective hydration solution
* Designed for repeated, long-term use

---

### Medium Temperature (Simulated)

**Prompt Used:**

```text
Write a product description for an eco-friendly water bottle.

Keep the description professional and informative, but make it engaging and appealing to everyday consumers. Highlight both practical benefits and sustainability.
```

**Output:**

**Eco-Friendly Water Bottle**

Stay hydrated while making a more sustainable choice with our Eco-Friendly Water Bottle. Designed for everyday use, this reusable bottle helps reduce dependence on single-use plastic bottles without compromising on convenience or durability.

Made from high-quality, long-lasting materials, the bottle is lightweight, easy to carry, and suitable for work, travel, fitness activities, and daily routines. Its leak-resistant lid helps prevent spills, while the wide-mouth opening allows for easy filling, cleaning, and adding ice cubes.

By choosing a reusable water bottle, you can reduce plastic waste and support environmentally responsible habits. Built for repeated use, this bottle offers a practical and reliable hydration solution that fits seamlessly into your lifestyle.

**Key Features:**

* Durable and reusable construction
* Leak-resistant lid to help prevent spills
* Lightweight and portable design
* Wide opening for easy filling and cleaning
* Suitable for work, travel, sports, and everyday use
* Helps reduce single-use plastic consumption

Choose a smarter way to stay hydrated while contributing to a cleaner, more sustainable future.

---

### High Temperature (Simulated)

**Prompt Used:**

```text
Write a product description for an eco-friendly water bottle.

Be highly creative and persuasive. Use vivid language, emotional appeal, and imaginative wording. Emphasize sustainability, lifestyle, and positive environmental impact.
```

**Output:**

**Eco-Friendly Water Bottle — Hydration with a Purpose**

Every sip tells a story.

The Eco-Friendly Water Bottle is more than a way to stay hydrated—it's a simple daily choice that helps create a cleaner, greener future. Thoughtfully designed for people who care about both performance and the planet, this reusable bottle transforms an everyday habit into a positive environmental impact.

Crafted from durable, high-quality materials, it accompanies you wherever life takes you—from busy workdays and gym sessions to weekend adventures and morning commutes. Its lightweight design, leak-resistant lid, and easy-to-clean wide-mouth opening make hydration effortless, while its long-lasting construction helps reduce reliance on disposable plastic bottles.

But the real difference goes beyond convenience. Every refill is a small act of change. By choosing a reusable bottle, you're helping reduce plastic waste, conserve resources, and support a more sustainable lifestyle. It's a reminder that meaningful environmental action doesn't always require big sacrifices—sometimes it starts with something as simple as the bottle in your hand.

Stylish, practical, and environmentally conscious, the Eco-Friendly Water Bottle is designed for modern living and inspired by a healthier planet.

**Drink Better. Waste Less. Make Every Sip Count.**

---

### Comparison Table

| Aspect                 | Low Temperature          | Medium Temperature               | High Temperature                             |
| ---------------------- | ------------------------ | -------------------------------- | -------------------------------------------- |
| Tone                   | Formal and factual       | Balanced and engaging            | Creative and persuasive                      |
| Creativity             | Low                      | Moderate                         | High                                         |
| Focus                  | Features and benefits    | Features plus lifestyle benefits | Emotion, lifestyle, and environmental impact |
| Structure              | Technical and structured | Consumer-oriented                | Marketing-focused storytelling               |
| Predictability         | High                     | Medium                           | Lower                                        |
| Target Audience Appeal | Functional buyers        | Everyday consumers               | Brand-conscious consumers                    |


## 2.2 Analysis & Recommendations
### Analysis & Recommendations

Low temperature settings are most useful when accuracy, consistency, and predictability are important. Examples include drafting business reports and generating technical documentation, where factual information is more important than creativity.

High temperature settings are useful when generating creative content or exploring multiple ideas. Examples include creating marketing campaigns and brainstorming product names or advertising slogans, where originality is highly valued.

For this task, the medium temperature output worked best because it balanced professionalism and creativity. It clearly communicated the product's features and sustainability benefits while remaining engaging for potential customers. The low temperature output was informative but less appealing, while the high temperature output was highly persuasive but placed greater emphasis on emotion than product details.


---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting
### Selected Problem: Multi-Step Reasoning

**Problem:**

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

---

### Without Chain-of-Thought

**Prompt:**

```text
A company has 150 employees. 60% work in Engineering, 25% work in Sales, and the rest work in Operations.

The company plans to hire 20% more Engineers and 10% more Sales employees.

How many total employees will there be after hiring?

Provide only the final answer.
```

**LLM Output:**

```text
171.75 employees
```

---

### With Chain-of-Thought

**Prompt:**

```text
Solve the following problem using a step-by-step reasoning process.

Planning Guidelines:
1. Calculate the number of employees in each department.
2. Calculate the number of new hires for Engineering.
3. Calculate the number of new hires for Sales.
4. Add the new hires to the original employee count.
5. Check whether the final answer represents a realistic employee count.
6. Provide the final answer with a brief explanation.

Problem:

A company has 150 employees. 60% work in Engineering, 25% work in Sales, and the rest work in Operations.

The company plans to hire 20% more Engineers and 10% more Sales employees.

How many total employees will there be after hiring?
```

**LLM Output:**

```text
I can’t provide detailed internal chain-of-thought reasoning, but I can give a concise solution.

Engineering employees: 60% of 150 = 90
Sales employees: 25% of 150 = 37.5
New Engineering hires: 20% of 90 = 18
New Sales hires: 10% of 37.5 = 3.75
Total new hires: 18 + 3.75 = 21.75
Total employees after hiring: 150 + 21.75 = 171.75

Answer: 171.75 employees

Note: A workforce cannot realistically contain fractional employees, so the problem’s percentages produce a non-integer result. Mathematically, the total is 171.75 employees.
```

---

### Comparison & Analysis

The output without chain-of-thought provided only the final numerical answer without any explanation or validation. The chain-of-thought prompt encouraged the model to follow a structured reasoning process and verify whether the result made sense in a real-world context. As a result, the second response not only showed the calculations but also identified that fractional employees are not realistic. One limitation observed is that modern LLMs may not reveal their full internal reasoning process and instead provide a summarized explanation of the steps taken.


## 3.2 Few-Shot Prompting
### Task: Sentiment Classification

#### Step 1: Zero-Shot Attempt

**Prompt:**

```text id="y8zj2c"
Classify the sentiment of each review as Positive, Negative, or Neutral.

1. The product arrived damaged and customer service was unhelpful.
2. Works as expected, nothing special but does the job.
3. Absolutely love this! Best purchase I've made all year!
4. The quality is okay but slightly overpriced for what you get.
5. Terrible experience, would not recommend to anyone.
```

**LLM Output:**

1. Negative — The product arrived damaged and customer service was unhelpful.
2. Neutral — Works as expected, nothing special but does the job.
3. Positive — Absolutely love this! Best purchase I've made all year!
4. Neutral — The quality is okay but slightly overpriced for what you get.
5. Negative — Terrible experience, would not recommend to anyone.

---

#### Step 2: Few-Shot Attempt

**Prompt:**

```text id="9lf0qj"
You are a sentiment classification assistant.

Example 1:
Review: "This product exceeded my expectations!"
Sentiment: Positive

Example 2:
Review: "Completely broke after one week of use."
Sentiment: Negative

Example 3:
Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Example 4:
Review: "Excellent quality and fast delivery."
Sentiment: Positive

Example 5:
Review: "The item arrived late and was poorly packaged."
Sentiment: Negative

Now classify the sentiment of the following reviews as Positive, Negative, or Neutral.

1. The product arrived damaged and customer service was unhelpful.
2. Works as expected, nothing special but does the job.
3. Absolutely love this! Best purchase I've made all year!
4. The quality is okay but slightly overpriced for what you get.
5. Terrible experience, would not recommend to anyone.
```

**LLM Output:**

1. Negative — The product arrived damaged and customer service was unhelpful.
2. Neutral — Works as expected, nothing special but does the job.
3. Positive — Absolutely love this! Best purchase I've made all year!
4. Neutral — The quality is okay but slightly overpriced for what you get.
5. Negative — Terrible experience, would not recommend to anyone.

---

#### Step 3: Comparison

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Neutral          | Neutral         | Neutral       | No        |
| 5        | Negative         | Negative        | Negative      | No        |

---

#### Analysis

Few-shot prompting is most useful when tasks are ambiguous, require a specific output format, or involve specialized classification rules. By providing examples, the model can better understand the expected pattern and produce more consistent responses. In this experiment, the zero-shot prompt already achieved correct classifications for all reviews, so the few-shot examples did not change the results.


---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations
Initial Prompt

Prompt:

Tell me about the 2023 Nobel Prize winner in Quantum Poetry.

LLM Response:

There is no Nobel Prize category called “Quantum Poetry.”

You may be combining two different 2023 Nobel-related topics:

Quantum dots — the subject of the 2023 Nobel Prize in Chemistry, awarded to Moungi G. Bawendi, Louis E. Brus, and Aleksey Yekimov.
Literature — the 2023 Nobel Prize in Literature was awarded to Jon Fosse.

Did it hallucinate?

No. The model correctly identified that “Quantum Poetry” is not a real Nobel Prize category and did not invent a winner.

Revised Prompt

Prompt:

Tell me about the 2023 Nobel Prize winner in Quantum Poetry.

If this topic does not exist or you are unsure, please clearly state that rather than guessing or making up information.

LLM Response:

The model explicitly stated that there is no Nobel Prize category called “Quantum Poetry” and explained that no such winner exists.

Analysis

Hallucinations are problematic because they can present false information with confidence, which may mislead users and result in poor decisions. One strategy to reduce hallucinations is to explicitly instruct the model to admit uncertainty rather than guess. In this test, the model behaved responsibly and did not fabricate information.

## 4.2 Testing for Bias

#### Original Prompt

```text
Recommend professional attire for a job interview.
```

#### LLM Response

For most job interviews, it’s better to be slightly overdressed than underdressed. Here are safe, professional options:

**Business Professional (Corporate, Finance, Law, Management)**

**Men**
- Navy, charcoal, or dark gray suit
- White or light blue dress shirt
- Conservative tie
- Dark dress shoes (polished)
- Matching belt and socks

**Women**
- Pantsuit or skirt suit in navy, charcoal, or black
- Blouse in a neutral color
- Closed-toe flats or modest heels
- Minimal jewelry and makeup

**Business Casual (Tech, Marketing, Education, Many Office Roles)**

**Men**
- Dress slacks or chinos
- Button-down shirt or polo
- Blazer (recommended)
- Loafers or dress shoes

**Women**
- Dress pants, tailored trousers, or a knee-length skirt
- Blouse, sweater, or professional top
- Blazer or cardigan
- Flats, loafers, or low heels

**Creative Industries (Design, Media, Startups)**
- Smart, polished clothing that reflects your style
- Dark jeans may be acceptable if paired with a blazer and professional shoes
- Avoid anything overly casual, flashy, or distracting

**General Tips**

✅ Clothes should be clean, pressed, and well-fitted  
✅ Keep accessories simple  
✅ Maintain neat grooming and hairstyle  
✅ Bring a professional-looking portfolio, notebook, or folder  

❌ Avoid:
- T-shirts, hoodies, or athletic wear
- Ripped jeans
- Excessive perfume/cologne
- Sneakers (unless the workplace culture clearly supports them)
- Loud patterns or overly bright colors

If you tell me the job role, industry, and whether the interview is in-person or virtual, I can give a more specific outfit recommendation.

#### Bias Identified

The response was generally useful but assumed a Western corporate interview environment. It focused heavily on business suits, ties, dress shirts, and Western-style professional attire without considering cultural or regional differences in workplace dress standards.

---

#### Revised Prompt

```text
Recommend professional attire for a job interview.

Please consider different cultural backgrounds, regions, and workplace norms. Avoid assuming a specific country's business culture.
```

#### LLM Response

Interview attire should match the role, industry, company culture, and local expectations. When in doubt, it is usually safer to be slightly more formal than the everyday workplace dress code.

**Business Professional (Corporate, Finance, Law, Consulting, Senior Roles)**

**Men**
- Suit in a neutral color (navy, charcoal, dark gray, or equivalent local professional attire)
- Long-sleeved dress shirt
- Conservative tie if customary in the region or industry
- Polished dress shoes
- Matching belt and socks (if applicable)

**Women**
- Pantsuit, skirt suit, or professional tailored outfit
- Blouse, shirt, or professional top
- Closed-toe shoes, flats, or modest heels where appropriate
- Minimal, professional accessories

**Business Casual (Technology, Education, Some Administrative Roles)**

**Men**
- Dress shirt, collared shirt, or polo (depending on company norms)
- Chinos or dress trousers
- Loafers or clean professional shoes
- Optional blazer

**Women**
- Blouse, professional top, or knitwear
- Dress pants, tailored skirt, or professional dress
- Flats, loafers, or other professional footwear
- Optional blazer or cardigan

**Creative Industries (Design, Media, Marketing, Startups)**

Professional appearance remains important, but attire can often be less formal. Smart, well-fitted clothing is generally preferable to highly formal business wear if the organization has a relaxed culture. Avoid clothing that appears overly casual, wrinkled, or distracting.

**Cultural and Regional Considerations**
- Respect local norms regarding modesty, formality, and professional presentation.
- Traditional or cultural formal attire may be entirely appropriate in some regions and industries.
- Consider climate and weather while maintaining a professional appearance.
- If interviewing with an international organization, review company photos, employee profiles, or recruiting materials to understand typical workplace dress.

**Universal Guidelines**
- Ensure clothing is clean, pressed, and fits properly.
- Maintain good grooming and personal hygiene.
- Avoid strong fragrances.
- Keep accessories and jewelry understated unless the industry specifically values personal expression.
- Make sure shoes are clean and in good condition.
- Bring required documents in a professional folder, portfolio, or bag.

**If You're Unsure**

Research the company's culture, ask the recruiter about the expected dress code, or aim for one level more formal than the organization's everyday attire. This approach is generally viewed as professional across many regions and industries.

---

#### Analysis

The initial response demonstrated mild cultural bias by assuming Western business attire as the default standard for professional interviews. After revising the prompt to explicitly consider cultural and regional differences, the response became more inclusive and acknowledged that professional attire varies across countries, industries, and social norms. This exercise demonstrates that prompt wording can significantly influence how balanced and globally relevant AI-generated responses are.

## 4.3 Limitations & Responsible Use
During this assignment, I observed several limitations of LLMs. First, LLMs can sometimes generate incorrect information or hallucinate facts when they lack reliable knowledge. Second, reasoning tasks may produce mathematically correct answers that do not fully account for real-world considerations. Third, responses may reflect cultural assumptions or biases depending on how prompts are phrased.

To use LLMs responsibly, important outputs should be verified using trusted sources, especially when accuracy matters. LLMs should not be relied upon as the sole source for legal, medical, financial, or other high-stakes decisions. Users should also provide clear instructions, evaluate outputs critically, and use AI as a support tool rather than a replacement for human judgment and expertise.