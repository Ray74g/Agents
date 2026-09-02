# Agents
Agentic AI Course
AI Agents and Prompt Engineering

1. What Is an Agent?

An AI agent is a system that can understand a goal, make decisions, use available tools, and take actions to complete a task.

Unlike a simple chatbot that only responds to a user's message, an agent can work through multiple steps and interact with its environment or external tools.

Basic Agent Workflow

User Input
    ↓
Understand the Goal
    ↓
Reason / Decide
    ↓
Choose an Action or Tool
    ↓
Execute the Action
    ↓
Observe the Result
    ↓
Continue or Give Final Response

Main Components of an AI Agent

- AI Model: Understands the input and generates decisions or responses.
- Instructions: Define what the agent should do and how it should behave.
- Tools: Allow the agent to perform actions such as searching the web, using APIs, calculating values, or accessing databases.
- Memory / Context: Provides information from previous interactions or the current task.
- Environment: The system or outside world in which the agent operates.
- Action: The result produced by the agent, such as answering a question or performing a task.

Example

Suppose a user asks:

«"What is the weather in Delhi today?"»

A simple chatbot may answer based on information already available to it.

An agent can:

1. Understand that the user wants current weather information.
2. Select a weather tool.
3. Send Delhi as the location.
4. Receive the current weather data.
5. Interpret the result.
6. Give the user the final answer.

Therefore, an agent is not only about generating text. It is about understanding a goal, deciding what to do, using tools when necessary, and taking actions to achieve the goal.

---

2. How to Write a Good Prompt: How Input Influences Output

A prompt is the instruction or input given to an AI model. The quality and structure of the input strongly influence the quality and usefulness of the output.

A vague prompt can produce a vague or incomplete answer, while a clear and specific prompt gives the model better guidance.

Example of a Poor Prompt

Write about AI.

This does not specify:

- What aspect of AI is required
- The intended audience
- The desired length
- The format
- The purpose

Example of a Better Prompt

Explain artificial intelligence to a Class 8 student.
Use simple language, give three real-life examples,
and keep the explanation within 300 words.

The second prompt provides much more useful information, so the expected output is more focused.

Elements of a Good Prompt

1. Role

Tell the AI what role it should take.

Example:

Act as a Python programming tutor.

2. Task

Clearly state what you want the AI to do.

Example:

Explain how a Python function works.

3. Context

Provide relevant background information.

Example:

The learner knows basic Python but has never used functions.

4. Constraints

Specify limitations or requirements.

Example:

Use simple language and avoid advanced programming concepts.

5. Output Format

Tell the AI how you want the answer presented.

Example:

Give the explanation using headings, bullet points, and one code example.

A Useful Prompt Structure

Role + Task + Context + Constraints + Output Format

For example:

Act as a statistics tutor.

Explain the concept of hypothesis testing to a beginner.

The student understands mean, variance, and probability
but has not studied hypothesis testing before.

Use simple language and give one practical example.

Present the answer using headings and bullet points.

How Input Influences Output

The output of an AI model is influenced by the information and instructions provided in the input.

Input Quality| Expected Output
Vague prompt| General or unfocused response
Clear task| More relevant response
More context| Better understanding of the situation
Specific constraints| More controlled response
Examples provided| Output is more likely to follow the desired pattern
Specified format| Output follows the requested structure

Key Idea

Better input generally leads to more useful and controlled output.

However, a good prompt does not guarantee that an AI model will always produce a correct answer. The output should still be checked and verified, especially when accuracy is important.

---

Key Takeaways

1. An AI agent can understand goals, reason, use tools, take actions, and work through multiple steps.
2. A prompt provides instructions and context to an AI model.
3. Clear and specific prompts generally produce more relevant and controlled outputs.
4. A good prompt can include role, task, context, constraints, and output format.
5. The quality of the input has a strong influence on the quality and usefulness of the output.
6. AI outputs should still be reviewed and verified when accuracy matters.
