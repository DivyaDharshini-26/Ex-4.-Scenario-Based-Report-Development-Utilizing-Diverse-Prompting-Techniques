# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.
## Aim: 
To design and develop an AI-powered chatbot using diverse prompting
techniques that can handle customer inquiries, provide support, and
enhance customer experience in a retail environment.
## Algorithm: 
Step 1: Problem Definition

• Identify the retail environment scenario (e.g., an online clothing
store).

• Define customer needs (product inquiries, order status, returns,
complaints).

Step 2: Data Collection

• Gather frequently asked questions (FAQs), support scripts, and
product data.

Step 3: Prompting Techniques Selection

• Choose diverse AI prompting methods (zero-shot, few-shot, chainof-thought, role prompting, persona-based, self-consistency).

Step 4: Prompt Design & Experimentation

• Construct different prompts for the same scenario using each
technique.

• Collect chatbot outputs.

Step 5: Evaluation

• Compare outputs for correctness, coherence, personalization, and
customer satisfaction.

Step 6: Report Generation

• Document the process, results, and analysis.

<img width="866" height="587" alt="image" src="https://github.com/user-attachments/assets/dd3829a4-a13e-49b2-9ab0-1e491cc95026" />

## Prompt:
“Develop a scenario-based report on designing and implementing an AIpowered chatbot for retail customer support. Apply diverse prompting
techniques (Zero-shot, Few-shot, Role-based, Chain-of-Thought, Personabased, Instruction-based, and Scenario-based)"

<img width="1109" height="638" alt="image" src="https://github.com/user-attachments/assets/68c3e77e-e39c-425f-9d1b-6f98b9e63b8c" />

## Output:
Prompts, Outputs, and Results
1. Zero-Shot Prompting
Prompt:
"You are a chatbot for a retail clothing store. A customer asks: 'Where is my
order?' Respond politely."

Output:
"Hello! Could you please provide your order ID so that I can check the
status for you?"

Result:
Zero-shot prompting works well for simple queries but may lack
personalization.

2. Few-Shot Prompting
Prompt:
"Example 1: Customer: 'Do you have size M in blue shirt?' → Chatbot: 'Yes,
size M in blue is available.'

Example 2: Customer: 'When will my delivery arrive?' → Chatbot: 'Your
delivery will arrive in 2–3 business days.'
Now, Customer: 'Can I return a product I bought last week?'"

Output:
"Yes, you can return your product within 30 days of purchase. Would you
like me to guide you through the return process?"

Result:
Few-shot improves accuracy and aligns responses with company policy.

3. Chain-of-Thought Prompting
 
Prompt:
"Step-by-step, think about how a chatbot should answer a customer
asking: 'I want to buy shoes under $50.'"

Output:
"First, check product database. Filter items under $50. Provide top options.
Response: 'Sure! Here are some shoes under $50: Casual Sneakers ($45),
Running Shoes ($48), and Sandals ($39). Would you like to see more?'"

Result:
Chain-of-thought ensures structured, logical answers for complex queries.

4. Role Prompting
 
Prompt:
"Act as a customer service representative of TrendyWear Store. A customer
asks: 'How do I track my order?'"

Output:
"Hello, thank you for shopping with TrendyWear. To track your order, please
visit our website and enter your tracking ID on the 'Track My Order' page.
Would you like me to send you the link?"

Result:
Role prompting improves empathy, professionalism, and tone.

5. Persona-Based Prompting
Prompt:
"You are a friendly fashion advisor chatbot. A customer asks: 'What should I
wear for a beach party?'"

Output:
"For a beach party, I recommend light and airy clothes. A floral shirt with
shorts or a sundress would be perfect. Don’t forget sunglasses and flipflops for comfort!

Result:
Persona-based prompting improves engagement and adds personality.

6.Self-Consistency Prompting
    
Prompt:
"Suggest the best product return policy explanation. Generate multiple
responses and choose the most helpful one."

Output:
1. "You can return products within 30 days with the receipt."
2. "We accept returns within 30 days of purchase for unused items. You
can request a refund or exchange."
3. "Products can be returned within 30 days. Please keep the receipt
and original packaging."

Final Response

"We accept returns within 30 days for unused items with the receipt and
packaging. You can request a refund or exchange."
Outputs of Chatbot using Diverse Prompting Techniques

1. Zero-Shot Prompting Output
Customer Query: "Where is my order?"
Chatbot Response:
"Hello! Could you please provide your order ID so I can check the status for
you? Once I have that, I can give you the exact delivery update."

2. Few-Shot Prompting Output
Customer Query: "Can I return a product I bought last week?"
Chatbot Response:
"Yes, you can return your product within 30 days of purchase. Please make
sure the item is unused and in its original packaging. Would you like me to
share the return request link with you?"

3. Chain-of-Thought Prompting Output
Customer Query: "I want to buy shoes under $50."
Chatbot Response:
"Sure! Let me check. Filtering shoes under $50... Here are a few options:
Casual Sneakers – $45, Running Shoes – $48, Sandals – $39. Would you like
me to show you more designs in this price range?"

4. Role Prompting Output
Customer Query: "How do I track my order?"
Chatbot Response:
"Hello, thank you for shopping with TrendyWear! You can easily track your
order by visiting our website and entering your tracking number on the
'Track Order' page. If you share your order ID, I can fetch the status for you
right now."

5. Persona-Based Prompting Output
Customer Query: "What should I wear for a beach party?"
Chatbot Response:
"For a beach party, I’d recommend something stylish yet comfortable! A
floral shirt with shorts or a flowy sundress would be perfect. Don’t forget
your sunglasses, flip-flops, and a light hat to stay cool and trendy!"

6. Self-Consistency Prompting Output
Customer Query: "Can you explain the return policy?"

Generated Responses:
"You can return products within 30 days with the receipt."
 "We accept returns within 30 days of purchase for unused items. You
may request a refund or exchange."
"Products can be returned within 30 days. Please keep the receipt
and original packaging."

Final Optimized Response (Selected):

"Our return policy allows you to return unused items within 30 days of
purchase, provided you have the receipt and original packaging. You may
choose either a refund or an exchange. Would you like me to guide you to
the return page?"

Comparative Analysis Table

<img width="688" height="580" alt="image" src="https://github.com/user-attachments/assets/6402c285-cd3e-4a2c-8d48-e896a26829d6" />


## Result:
1. Zero-Shot Prompting Result
   
Observation:
• The chatbot was able to provide a basic and polite response to the
customer’s query without any prior examples.
• The answer was functional, but lacked personalization (no
estimated delivery details until the order ID was shared).

Strengths:
• Very fast to implement.
• Works well for simple FAQ-like queries.

Weaknesses:
• Lacks contextual depth.
• Cannot adapt easily to complex or ambiguous customer questions.

Overall Result:
Zero-shot prompting is best suited for straightforward inquiries such as
order tracking requests, store hours, or product availability checks.
However, it requires follow-up interactions for more detailed queries.

2.Few-Shot Prompting Result

Observation:
• With examples included, the chatbot produced a policy-compliant,
customer-friendly response.
• The answer was more accurate and aligned with company policy
compared to the zero-shot approach.

Strengths:
• More context-aware than zero-shot.
• Provides consistent answers if examples are relevant.

Weaknesses:
• Relies heavily on the quality of training examples.
• May not generalize well outside the provided examples.

Overall Result:
Few-shot prompting improves accuracy and consistency of responses. It
is particularly effective for policy-related queries (like returns, exchanges,
delivery timelines) where the chatbot must follow predefined rules.

3. Chain-of-Thought Prompting Result
   
Observation:
• The chatbot produced a step-by-step logical answer for a product
recommendation task.
• It first reasoned through the query (“check database → filter items →
suggest top 3”) before providing the customer-facing response.'

Strengths:
• Produces structured, logical answers.
• Useful for complex queries such as recommendations,
troubleshooting, or comparisons.

Weaknesses:
• Slower than zero/few-shot.
• May expose reasoning steps if not properly formatted, which can
confuse end-users.

Overall Result:
Chain-of-thought prompting is highly effective when multi-step reasoning
is required (e.g., filtering products by price, recommending items,
troubleshooting order issues). It makes the chatbot smarter but needs
careful formatting to keep answers user-friendly.

4. Role Prompting Result
   
Observation:
• The chatbot successfully adopted the role of a customer service
representative, providing a professional, empathetic, and branded
tone in its response.
• This made the interaction feel human-like and trustworthy.

Strengths:
• Improves tone, empathy, and professionalism.
• Enhances customer trust and satisfaction.

Weaknesses:
• Risk of sounding repetitive or overly scripted.
• May become rigid if not flexible in style.

Overall Result:
Role prompting is ideal for customer-facing interactions where empathy
and tone are critical. It is best suited for service-related queries (tracking,
complaints, or order assistance).

5. Persona-Based Prompting Result
   
Observation:
• The chatbot responded in the style of a fashion advisor, giving
personalized outfit recommendations for a beach party.
• The conversation felt engaging, friendly, and relatable.

Strengths:
• Makes chatbot engaging and human-like.
• Boosts customer experience and loyalty by adding a personal
touch.

Weaknesses:
• May prioritize friendliness over strict accuracy.
• Not suitable for highly technical or policy-driven queries

Overall Result:
Persona-based prompting works well for advisory or lifestyle queries,
such as styling tips, product suggestions, or personalized shopping
assistance. It enhances brand personality and improves customer
engagement.

6. Self-Consistency Prompting Result
   
Observation:
• Multiple candidate responses were generated for the return policy.
• The chatbot then selected the most complete, accurate, and
customer-friendly version.

Strengths:
• Produces refined, balanced answers.
• Minimizes errors by comparing multiple candidate outputs.

Weaknesses:
• Requires more computational resources.
• May be slower than other methods.

Result:

Self-consistency prompting is best for policy-related or critical queries,
where accuracy is crucial. It ensures that the customer receives a wellrounded and reliable answer

<img width="552" height="738" alt="image" src="https://github.com/user-attachments/assets/b90ec240-3158-42fb-8c21-fe0f0728666d" />

<img width="895" height="605" alt="image" src="https://github.com/user-attachments/assets/119c4b6a-ebd7-496c-a634-b659884c83ab" />


