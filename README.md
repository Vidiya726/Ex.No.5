

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: 
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 
he primary AI tool required for this comparative analysis is ChatGPT. To ensure consistency and enable a fair comparison across all test scenarios, the experiment should be conducted using the same version of the model (e.g., GPT-4) throughout the entire testing process.

# Explanation: 
Define the Two Prompt Types:
Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT
# I. Introduction
### 1.1 Background: The Role of Prompt Engineering in Large Language Models (LLMs)
The emergence of Large Language Models (LLMs), such as ChatGPT, has revolutionized how we interact with artificial intelligence, making them powerful tools for tasks ranging from creative content generation to complex data summarization. These models operate based on the input they receive, known as a prompt. The quality of the output is profoundly influenced by the quality of the input. This relationship has given rise to the discipline of Prompt Engineering, which is the art and science of designing effective prompts to steer an LLM toward a desired result. This experiment seeks to demonstrate empirically how different levels of prompt structure directly impact the practical utility and reliability of LLM outputs.

### 1.2 Aim: Comparative Analysis of Prompt Clarity on Response Quality
The primary objective of this experiment is to systematically test and compare the generated responses of an LLM (specifically ChatGPT) when presented with two distinct patterns of prompting: naïve (broad/unstructured) and basic (clear/refined).

The experiment aims to:
 1. Quantify the differences in output quality, accuracy, and depth across multiple, varied test scenarios.
 2. Determine if a structured, refined prompt consistently yields superior results compared to a vague or general prompt.
 3. Analyze the scenarios where prompt clarity offers the most significant performance advantage.

### 1.3 Key Definitions: Defining the Prompt Types
To maintain clarity throughout this report, we define the two prompting patterns used in this study:

  1. Naïve/Broad Prompt: This pattern is characterized by its unstructured nature, minimal context, and general instruction. It often leaves the model to make significant assumptions regarding the user's intent,       the desired format, or the scope of the information required. (e.g., "Write about dogs.")
  2. Basic/Refined Prompt: This pattern is defined by its clarity, detail, and specific structure. It typically includes elements such as the desired role for the AI, the specific task to be performed, necessary       context, required format, and any important constraints. This approach minimizes ambiguity and effectively guides the model's focus. (e.g., "Act as a professional veterinarian. Write a 500-word informative        article for a pet owner blog post on the proper diet for an adult Labrador, ensuring all facts are scientifically accurate and sourced.")

# II. Methodology:
### 2.1 AI Tool Used
The experiment will exclusively utilize ChatGPT (specifically, specifying the version, e.g., GPT-4 or GPT-3.5-Turbo, accessed via the user interface). Using a single, commercially available LLM is a conscious choice to isolate the variable under study: the prompting pattern. To ensure the experiment is conducted fairly:

   1. All prompts for a specific scenario will be submitted in a fresh chat session to prevent the model from carrying over context or bias from previous interactions.
   2. The temperature and other model parameters will be kept at their default settings (or the lowest available setting to reduce randomness).

### 2.2 Test Scenarios Selection and Rationale
A minimum of four distinct scenarios will be employed. This diversity is essential to test the LLM's capabilities across different domains, ensuring the findings are not limited to a single task type. The chosen scenarios are:
  1. Creative Generation (Divergent Task): This task (e.g., writing a story or poem) tests how well a structured prompt can guide style, tone, and specific narrative elements, which the model tends to vary             widely on its own.
  2. Factual Query (Convergent/Knowledge Task): This task (e.g., explaining a scientific concept) tests accuracy and the model's ability to efficiently retrieve and synthesize specific, verifiable information          when given clear boundaries.
  3. Content Transformation/Summarization (Analytical Task): This task requires the model to process external information (e.g., a provided paragraph) and restructure it. It tests the adherence to explicit             constraints like length or target audience.
  4. Advice/Recommendation (Judgmental/Contextual Task): This task requires empathy and judgment (e.g., providing career advice). It tests the prompt's ability to enforce a specific persona/role and maintain an appropriate, helpful tone.

### 2.3 Prompt Design and Construction
For each of the four scenarios, two corresponding prompts will be created, ensuring they target the exact same output goal:
<img width="862" height="283" alt="image" src="https://github.com/user-attachments/assets/0494adda-b157-4989-be79-57dd9b85094c" />

The precise wording of all eight prompts will be documented and included in the Results section of the final report.

### 2.4 Execution Protocol
The data collection will follow a strict, systematic process:

  1. Preparation: Define the four test scenarios and write the eight corresponding prompts (four Naïve, four Basic).
  2. Input & Collection: Execute the experiment by inputting the prompts into ChatGPT, ensuring the correct prompt type is used for each new chat session.
  3. Data Capture: The entire generated response for each of the eight inputs will be copied and saved verbatim to prevent post-hoc editing bias.
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/7d2ef15d-a45a-400e-a242-076a5bcd409e" />

### 2.5 Evaluation Metrics and Scoring
The responses will be evaluated qualitatively and assigned a quantitative score using a 5-point Likert scale (1 = Poor, 5 = Excellent) for each of the three defined metrics:

   1. Quality (Coherence & Structure): Assesses sentence structure, adherence to grammatical rules, overall flow, and the logical organization of the information.
   2. Accuracy (Factual Correctness & Relevance): Measures how true the facts are (for factual tasks) and how completely the response addresses all parts of the original query.
   3. Depth (Detail & Substance): Measures the thoroughness of the explanation, the inclusion of nuanced sub-points, and the level of complexity appropriate for the task.
   4. The scores will be recorded in the final comprehensive results table for direct comparison and subsequent analysis.

# III. Results and Data Presentation
### 3.1 Comprehensive Results Table
This section will feature the central deliverable of the experiment: a fully populated table summarizing the findings across all test scenarios. This table serves as the primary evidence, enabling direct quantitative comparison between the two prompt types.

The table will systematically document the following for each of the eight total inputs (four scenarios × two prompt types):
<img width="868" height="420" alt="image" src="https://github.com/user-attachments/assets/22abe053-9a0c-43a0-af96-0f488f8daf7f" />

The Total Score (sum of the three metrics) will provide an initial, high-level quantitative measure of performance disparity.

### 3.2 Scenario-by-Scenario Comparison
To provide context beyond the numerical scores, this sub-section will offer a brief qualitative presentation of the raw outputs for each task. This allows the reader to visually and textually grasp the differences before diving into the detailed analysis.
   Scenario 1: Creative Generation: Contrast the coherence and adherence to narrative rules. Highlight a critical difference, e.g., "The Naïve prompt yielded a vague, generic plot, while the Basic prompt            delivered a structured story adhering to the specified 3-act structure."

   Scenario 2: Factual Query: Focus on the correctness and precision of the answers. Point out any factual errors or significant omissions in the Naïve response that were corrected or improved in the Basic          response.

   Scenario 3: Content Transformation/Summarization: Compare the adherence to constraints. Demonstrate how the Basic prompt successfully enforced the required length (e.g., 100 words) and tone, which the Naïve      prompt failed to manage.

   Scenario 4: Advice/Recommendation: Evaluate the use of the specified persona/role. Show the difference in tone and practical utility when the model was explicitly instructed to act as an expert versus a          general source.

This structure ensures that the data is first summarized quantitatively, then immediately supported by key qualitative examples, setting the stage for the final discussion and analysis
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/38e6c580-889f-4a87-9e77-5744c17b2123" />

# IV. Comparative Analysis and Discussion
This section moves beyond data presentation to interpret the findings documented in the Comprehensive Results Table (Section 3.1) and the Scenario-by-Scenario Comparison (Section 3.2). The analysis will focus on how prompt clarity consistently influenced the LLM's performance across the defined metrics.

### 4.1 Analysis by Metric: Impact of Prompt Clarity
The core discussion will be framed around how the introduction of structured elements (Role, Task, Context, Constraints) in the Basic Prompt affected each measured outcome:

1. Impact on Quality (Coherence and Structure):
     Finding: Analyze the average Quality score difference. Did the Basic Prompts result in responses that were universally more coherent, better formatted, and easier to read?
     Discussion: Explain this improvement. For instance, the Basic Prompt's explicit instruction on Format (e.g., "Use bullet points," "Write a 3-paragraph summary") likely forces the model out of its default, often meandering, conversational style, resulting in a tighter, higher-quality structure.
2. Impact on Accuracy (Factual Correctness and Relevance):
    nding: Compare the Accuracy scores, particularly in the Factual Query and Summarization scenarios. Did the Naïve Prompt introduce more irrelevant content or verifiable error
    Discussion: Argue that providing Context and Constraints (e.g., "Focus only on the economic impact," or "Ensure facts are cited from Source X") acts as a boundary condition, narrowing the model's search space and reducing the chance of generating tangential or incorrect information.

3.  Impact on Depth (Detail and Substance):
Finding: Discuss the differences in the thoroughness of the responses. Did the Basic Prompt consistently provide more substantial, detailed, and insightful output?
Discussion: Attribute the superior depth to the explicit definition of the Role (e.g., "Act as a quantum physics professor"). Assigning a specific, expert role appears to "unlock" deeper levels of the model's knowledge, pushing it to generate specialized terminology and detailed explanations that the generic Naïve Prompt fails to solicit.

### 4.2 General Trends and Model Behavior
This sub-section will address the broader patterns observed across all four test scenarios:

1. Consistency of Superiority: Confirm whether the Basic/Refined Prompt consistently achieved a higher Total Score than the Naïve Prompt, reinforcing the value of structure regardless of the task domain.
2. Handling Ambiguity: Analyze how the model responded to the Naïve Prompts. Discuss the common pitfalls: Did it frequently make incorrect assumptions about the desired Tone or Audience? Did it default to a generic, often verbose, explanatory style? This demonstrates the risk inherent in unstructured prompting.
3. Exceptions and Nuances: Identify any scenarios where the performance difference was minimal. For example, a simple, universally known factual question might have yielded similar results regardless of the prompt type. Discuss why (e.g., the underlying task was so simple it required minimal guidance).
4. The Power of Constraint: Highlight specific instances where the omission of a constraint in the Naïve Prompt led to a poor result (e.g., a story that was too long, advice that was too generic) and the inclusion of that same constraint in the Basic Prompt led to success.

### 4.3 The Value of Structure: A Core Insight
Conclude the discussion with a definitive statement on the experiment's main takeaway. The primary reason structured prompts succeed is that they effectively manage the model's vast potential by reducing ambiguity and enforcing precision. A well-structured prompt serves as a precise algorithm for the LLM, transforming a broad request into a targeted instruction set, which is necessary for optimal performance.


# V. Conclusion and Recommendations
### 5.1 Summary of Findings
This experiment unequivocally demonstrates the critical role of prompt engineering in maximizing the utility and performance of Large Language Models like ChatGPT. Across all tested scenarios (creative generation, factual query, content transformation, and advice), Basic/Refined Prompts consistently outperformed Naïve/Broad Prompts in terms of quality, accuracy, and depth. The structured input provided clearer guidance, reduced ambiguity, and allowed the LLM to leverage its capabilities more effectively. The data clearly indicates that while LLMs possess vast knowledge, their optimal output is heavily contingent upon precise and well-articulated instructions.

### 5.2 Insights for Optimal Prompt Structuring
Based on the empirical evidence gathered, the following best practices are recommended for structuring prompts to achieve optimal results from LLMs:
1. Define the Role: Explicitly assign a persona to the AI (e.g., "Act as a historian," "You are a marketing specialist"). This helps the model adopt an appropriate tone and access specialized knowledge.
2. Specify the Task: Clearly state what you want the AI to do (e.g., "Summarize," "Generate ideas," "Explain"). Avoid vague requests.
3. Provide Context: Offer all necessary background information to inform the AI's response, even if it seems obvious. This helps avoid misinterpretations.
4. Set Constraints: Define limitations and requirements such as length (e.g., "150 words," "three paragraphs"), format (e.g., "bullet points," "table," "JSON"), and style/tone (e.g., "formal," "humorous," "academic").
Give Examples (Few-Shot Prompting): If applicable, providing a single example of the desired input-output format can dramatically improve results for complex tasks.
5. Iterate and Refine: Consider prompt engineering as an iterative process. Initial prompts may need refinement based on the initial output.

### 5.3 Limitations and Future Work
While this experiment provides strong evidence, it has certain limitations:
1. Single LLM: The study was limited to one version of ChatGPT. Future work could compare different LLMs (e.g., Bard, Claude) or different versions of the same model.
2. Subjective Scoring: While clear criteria were established, the evaluation of responses relied on a single researcher's subjective scoring. Future experiments could benefit from inter-rater reliability by involving multiple evaluators.
3. Limited Scenarios: Only four scenarios were tested. Expanding to a wider range of tasks could further validate the findings.
Future research could explore the impact of specific prompt components (e.g., what is the most impactful part: role, format, or context?), the effectiveness of few-shot prompting in greater detail, or the performance of LLMs with dynamically generated prompts

# RESULT: The prompt for the above said problem executed successfully
