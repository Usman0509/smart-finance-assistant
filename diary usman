Developer Diary
Smart Finance Assistant: Budget Buddy

This diary explains how I used AI while working on my Smart Finance Assistant project. My project is called Budget Buddy. It helps users understand their spending by analysing transaction data from a CSV file. It can clean the data, show spending by category, give simple financial recommendations, answer finance questions, use a savings calculator, and show everything through a Gradio interface.

Entry 1 – Understanding the Assignment

Artifact: ChatGPT conversation where I asked for help understanding the assignment and the starter notebook.

Context: I was confused about the whole assignment structure and did not know where to start.

My Prompt: “Explain the Smart Finance Assistant assignment in simple terms and tell me how to start using the starter notebook.”

AI Response Summary: AI explained that the starter notebook was not a finished project, but a template that I had to edit and fill in. It explained that I should use the notebook as the main assignment file and complete it step by step.

My Critique/Improvement: I asked AI to explain it more simply because I was overwhelmed by the notebook, GitHub, README, diary, and all the different sections.

Result: I understood that I did not need to create everything from scratch. I had to work inside the starter notebook, replace the empty parts, and build the project slowly.

Reflection: This helped me because before this I was looking at the assignment as one huge confusing task. After breaking it down, I understood that the project is made of smaller parts that connect together.

Entry 2 – Planning the Finance Problem

Artifact: ChatGPT conversation where I asked for help with the six-step methodology.

Context: I needed help writing the planning sections before coding, like the problem statement, inputs and outputs, manual example, and pseudocode.

My Prompt: “Help me write the six-step methodology sections for a Smart Finance Assistant that analyses transaction CSV data.”

AI Response Summary: AI helped me write a simple finance problem, explain the inputs and outputs, create a manual example, and write pseudocode for how the project should work.

My Critique/Improvement: I changed some of the wording so it sounded more like my own explanation and matched my project idea better.

Result: I added the planning sections into the notebook. These sections explain that Budget Buddy helps users understand spending habits by analysing CSV transaction data.

Reflection: I learned that planning the logic in normal English before coding makes the project easier. It helped me understand what the code was supposed to do before I started writing functions.

Entry 3 – Loading and Cleaning Transaction Data

Artifact: Code snippet from the load_and_clean_transaction_data() function.

Context: I needed to create a function that loads a CSV file and cleans the transaction data.

My Prompt: “Help me write a Python function that loads transaction CSV data, checks required columns, removes dollar signs from Amount, converts values to numbers, converts Date values, and handles missing data.”

AI Response Summary: AI helped create a pandas function that reads the CSV file, checks if the required columns exist, removes dollar signs from the Amount column, converts Amount to numbers, converts Date values, and removes invalid rows.

My Critique/Improvement: When I tested the function, I got an error because df_sample was not defined. I asked for help and fixed it by creating the sample data inside the test cell.

Result: The function worked and printed a cleaned table. The Amount column changed from text like $45.50 into proper number values.

Reflection: I learned that raw data is not always ready to use. It has to be cleaned before analysis. I also learned that checking columns is important because the program should handle wrong files properly.

Entry 4 – Spending Analysis Function

Artifact: Code snippet from the analyze_spending_patterns() function.

Context: I needed to analyse the cleaned transaction data and calculate useful spending information.

My Prompt: “Help me create a function that analyses spending by category, calculates total spending, average transaction amount, category percentages, and identifies the top spending category.”

AI Response Summary: AI helped create a function that uses pandas to calculate total spending, average transaction amount, spending by category, category percentages, and the highest spending category.

My Critique/Improvement: I kept the part where it only counts positive amounts for spending analysis, because refunds and negative values should not be counted as normal spending.

Result: The function worked and showed total spending, average transaction amount, top category, category totals, and category percentages.

Reflection: I learned that pandas groupby() is useful for summarising data by category. It made the spending analysis much easier than manually going through every transaction.

Entry 5 – Financial Recommendations

Artifact: Code snippet from the generate_financial_recommendations() function.

Context: I wanted the assistant to turn the spending analysis into simple advice that a user could understand.

My Prompt: “Help me create a business insights function that turns spending analysis results into simple financial recommendations for a personal finance app user.”

AI Response Summary: AI helped create a function that formats the spending analysis into a readable report. It includes total spending, average transaction amount, spending breakdown, highest category, and a recommendation.

My Critique/Improvement: I checked that the advice was based on the actual analysis results and not just random general finance advice.

Result: The function created a financial recommendations report based on the user’s spending data.

Reflection: I learned that showing numbers is not enough. A finance assistant should explain what the numbers mean and give the user something useful to think about.

Entry 6 – Hands-on-AI Chatbot Setup

Artifact: Code snippet showing the Hands-on-AI connection and chatbot response.

Context: I needed to connect the notebook to the AI server and create a finance chatbot personality.

My Prompt: “Help me create a friendly finance chatbot personality that gives simple educational advice based on transaction analysis.”

AI Response Summary: AI helped create a chatbot function using get_response(). The chatbot was given a Budget Buddy personality and was told to give simple financial advice.

My Critique/Improvement: At first, the AI connection did not work because the server, model, and key were wrong. I compared it with my friend’s working setup and changed the settings.

Result: The chatbot worked and answered a finance question using the spending recommendations.

Reflection: I learned that AI tools need the correct server, model, and API key to work. I also learned that the prompt controls how the chatbot behaves and what kind of answer it gives.

Entry 7 – RAG-Style Transaction Context

Artifact: Code snippet from the setup_financial_rag() function.

Context: I needed to add a RAG-style feature so the chatbot could use transaction data when answering questions.

My Prompt: “Help me create a simple RAG-style function that retrieves transaction context from spending analysis and uses it to answer user finance questions.”

AI Response Summary: AI explained that I could use the spending recommendations as the retrieved context. The function creates an analysis from the transaction data and includes that information in the AI prompt.

My Critique/Improvement: I kept the RAG system simple because I did not want to overcomplicate it with a full document database. I used the transaction summary as the retrieved information.

Result: The chatbot could answer a finance question using the user’s transaction summary as context.

Reflection: I learned that RAG basically means giving AI useful information before asking it to answer. In my project, the useful information is the user’s spending summary.

Entry 8 – Custom Savings Goal Tool

Artifact: Code snippet from the savings_goal_calculator() function.

Context: I needed to add one custom financial tool for the project.

My Prompt: “Create a savings goal calculator function that takes current savings, target amount, and monthly contribution, then calculates time to reach the goal.”

AI Response Summary: AI helped create a savings calculator that checks the user’s inputs and calculates how many months it will take to reach a target savings amount.

My Critique/Improvement: I included checks for negative savings, zero monthly contribution, and cases where the savings goal has already been reached.

Result: The savings calculator worked and correctly calculated that saving from $500 to $2000 with $250 per month would take about 6 months.

Reflection: I learned that a custom tool does not have to be complicated. It can be a simple Python function that solves one useful finance problem.

Entry 9 – Gradio User Interface

Artifact: Screenshot or code snippet of the Gradio interface running in the notebook.

Context: I needed to create a simple app interface so the assistant could be used without manually running every code cell.

My Prompt: “Help me design a Gradio interface that combines CSV upload, spending analysis, finance questions, and a savings calculator.”

AI Response Summary: AI helped create a Gradio interface with a CSV upload, finance question box, savings inputs, and an output area.

My Critique/Improvement: I tested it by uploading a CSV file and checking that it showed the spending analysis, savings result, and chatbot response.

Result: The Gradio interface worked and made the project feel like a simple finance app.

Reflection: I learned that Gradio is useful because it turns Python code into an interface that normal users can interact with more easily.

Entry 10 – Testing and Integration

Artifact: Code snippets showing the foundation tests and integration tests.

Context: I needed to test that the finance assistant worked properly with normal data and also handled bad data.

My Prompt: “Help me create tests for normal transaction data, refunds, missing values, invalid columns, savings calculator inputs, and full workflow integration.”

AI Response Summary: AI helped create tests using assert statements. The tests checked normal transaction data, refund values, missing values, invalid columns, the savings calculator, no file upload, and the full workflow.

My Critique/Improvement: I ran the tests and checked that the basic tests and integration tests passed. I also checked that invalid columns produced an error message instead of breaking the whole notebook.

Result: The tests passed and showed that the main functions and full workflow were working.

Reflection: I learned that testing is important because it proves the program works in different situations. It also helped me feel more confident that the assistant was not just working for one perfect example.

Overall Reflection

AI helped me build the Smart Finance Assistant step by step. The most useful part was that AI helped me break the project into smaller pieces instead of trying to understand everything at once.

I used AI to help understand the assignment, plan the notebook, write pandas functions, create recommendations, fix errors, set up the chatbot, create a RAG-style function, build the savings calculator, make the Gradio interface, and write tests.

I learned that AI can help generate code and explain ideas, but I still need to test the code and make sure it actually works for my project. The main challenge was understanding how all the parts connected together. Once I broke the project into smaller sections, it became much easier to complete.

This project helped me practise Python functions, pandas data processing, AI prompting, RAG-style context, custom financial tools, Gradio interface design, and testing.
## 📝 Documentation Template for Your Entries

Use this format for consistent diary entries:

```markdown
### Entry [Number] – [Descriptive Title]
**Artifact:** [Screenshot/code snippet/GIF of AI interaction]

**Context:** [One sentence: what you were trying to achieve]

**My Prompt:** "[Your exact prompt to AI]"

**AI Response Summary:** [Brief description of what AI provided]

**My Critique/Improvement:** [How you modified or improved the AI's suggestion]

**Result:** [What you ended up with and why it's better]

**Reflection:** [What you learned about AI collaboration, business programming, or problem-solving]
```

---

✅ **Remember**: Document your AI collaboration throughout your project development. Each entry should show learning and improvement, not just successful interactions. Show how you direct AI like a junior developer to create business-appropriate solutions.

