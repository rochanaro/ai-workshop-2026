# LLM Prompting Guide for Business & Finance Faculty
## Practical Examples for Claude, Gemini, and Image Generation

---

## Table of Contents

1. [Introduction to LLM Prompting](#introduction)
2. [General Prompting Best Practices](#best-practices)
3. [Claude Prompting Examples](#claude-examples)
4. [Gemini Prompting Examples](#gemini-examples)
5. [Image Generation Prompts](#image-generation)
6. [Everyday Productivity Tasks](#productivity-tasks)
7. [Advanced Business Use Cases](#advanced-use-cases)
8. [Common Pitfalls and How to Avoid Them](#pitfalls)

---

## 1. Introduction to LLM Prompting {#introduction}

### What is Prompting?

**Prompting** is the art and science of communicating with Large Language Models (LLMs) to get the best possible outputs. Think of it as giving clear instructions to a highly capable assistant.

### Why Different Models?

- **Claude (Anthropic)**: Excellent for long documents, detailed analysis, coding, ethical reasoning
- **Gemini (Google)**: Multimodal (handles text + images), integrated with Google Workspace
- **ChatGPT/GPT-5 (OpenAI)**: Versatile, widely integrated, strong creative capabilities

### Key Principle:
**Garbage In = Garbage Out** | **Quality In = Quality Out**

The better your prompt, the better the response!

---

## 2. General Prompting Best Practices {#best-practices}

### ✅ The CLEAR Framework:

| Letter | Stands For | Meaning |
|---|---|---|
| **C** | Context | Provide background information |
| **L** | Length | Specify desired output length |
| **E** | Examples | Give examples when possible |
| **A** | Audience | Define who the output is for |
| **R** | Role | Assign a role to the AI |

### Basic Prompt Structure:

```
[Role] + [Context] + [Task] + [Format] + [Constraints]
```

### Example:

**Poor Prompt:**
```
Write about finance
```

**Good Prompt:**
```
You are a financial analyst writing for MBA students. 
Create a 500-word explanation of the Time Value of Money concept. 
Include 2 practical examples from business scenarios. 
Use simple language and avoid jargon where possible.
```

---

## 3. Claude Prompting Examples {#claude-examples}

https://claude.ai/chat/

### 3.1 Financial Analysis

#### Task: Analyzing Company Financials

**Prompt:**
```
You are a senior financial analyst. I'm going to share excerpts from Apple's 
latest 10-K filing. Please analyze the following aspects:

1. Revenue trends and growth patterns
2. Operating margin analysis
3. Key risks mentioned
4. Capital allocation strategy

Present your analysis in a structured format with clear sections. 
Highlight 3 key insights that would be most relevant for potential investors.

[Paste relevant sections of 10-K]
```

**Why This Works:**
- Defines role (financial analyst)
- Specifies analysis dimensions
- Requests structured output
- Asks for actionable insights

---

#### Task: Creating Financial Models

**Prompt:**
```
I need to create a 5-year DCF model for a mid-sized retail company.

Company Details:
- Current Revenue: $50M
- Expected growth: 8% annually years 1-3, then 5% years 4-5
- Operating margin: 12%
- Tax rate: 25%
- WACC: 9%

Please help me:
1. Calculate projected free cash flows for each year
2. Calculate terminal value using perpetuity growth of 3%
3. Discount all cash flows to present value
4. Provide the enterprise value

Show your work step by step, and explain any assumptions made.
```

**Claude's Strength**: Shows detailed calculations with explanations

---

### 3.2 Business Writing

#### Task: Executive Summary

**Prompt:**
```
You are an executive communications specialist. I need to transform 
this detailed market research report into a 1-page executive summary 
for our CEO.

Target audience: C-suite executives with limited time
Tone: Professional, action-oriented
Format: Bullet points with clear headers
Focus on: Key findings, strategic implications, recommended actions

Here's the full report:
[Paste report]

The summary should answer:
- What did we learn?
- Why does it matter?
- What should we do?
```

---

#### Task: Professional Email Drafting

**Prompt:**
```
Help me draft a professional email with the following situation:

Context: I'm a department head who needs to inform faculty that 
budget cuts require reducing conference travel funding by 30%.

Requirements:
- Start with empathy and acknowledgment of impact
- Explain the business rationale clearly
- Offer alternative solutions (virtual conferences, shared funding)
- End on a positive/forward-looking note
- Keep it under 200 words
- Maintain professional but warm tone

Draft this email for me.
```

---

### 3.3 Teaching & Course Design

#### Task: Case Study Creation

**Prompt:**
```
Create a business case study for my MBA course on "Strategic Decision Making."

Scenario: A traditional bookstore chain facing Amazon competition (2010-2015)

Requirements:
- 800-1000 words
- Include: company background, market dynamics, strategic options
- Present 3 viable strategic alternatives (with pros/cons)
- Add discussion questions for students
- End with "what would you do?" decision point

Make it realistic but keep company/details fictionalized.
Ensure it has enough complexity for 45-minute class discussion.
```

---

#### Task: Creating Assessment Rubrics

**Prompt:**
```
Design a detailed grading rubric for a financial analysis project 
in my Corporate Finance course.

Project: Students analyze a public company and make investment recommendation

Grading Criteria to Include:
1. Financial ratio analysis (25%)
2. Industry comparison (20%)
3. Valuation quality (25%)
4. Recommendation clarity (15%)
5. Presentation quality (15%)

For each criterion, provide:
- Excellent (A): specific expectations
- Good (B): specific expectations
- Satisfactory (C): specific expectations
- Needs Improvement (D/F): specific expectations

Make criteria measurable and objective where possible.
```

---

### 3.4 Research Assistance

#### Task: Literature Review

**Prompt:**
```
I'm researching "ESG investing impact on portfolio performance."

Help me structure a literature review by:

1. Identifying key themes I should cover
2. Suggesting seminal papers I should definitely include
3. Outlining potential structure for the review
4. Identifying gaps in current research
5. Suggesting research questions that remain unexplored

Assume this is for a top-tier journal submission in finance.
```

---

#### Task: Data Analysis Interpretation

**Prompt:**
```
I've run a regression analysis on factors affecting customer retention.

Results:
- Price sensitivity: β = -0.45 (p < 0.01)
- Service quality: β = 0.62 (p < 0.001)
- Brand loyalty: β = 0.38 (p < 0.05)
- R² = 0.67

Please help me:
1. Interpret these findings in plain business language
2. Assess the practical significance (not just statistical)
3. Suggest managerial implications
4. Identify limitations of this analysis
5. Recommend next steps for deeper analysis

Write as if explaining to non-technical business executives.
```

---

## 4. Gemini Prompting Examples {#gemini-examples}

https://gemini.google.com/

### 4.1 Multimodal Analysis (Text + Images)

#### Task: Analyzing Charts and Graphs

**Prompt:**

example image: https://www.geekwire.com/2025/amazons-quarterly-profits-soar-to-a-record-20-billion-but-cloud-growth-comes-up-short/
```
[Upload/paste image of financial chart]

Analyze this quarterly revenue chart and:
1. Identify key trends and patterns
2. Point out any anomalies or unexpected changes
3. Compare Q2 vs Q4 performance
4. Suggest 3 questions we should investigate based on this data

Provide insights that would be valuable for a board presentation.
```

**Gemini's Strength**: Can directly "see" and analyze visual content

---

#### Task: Presentation Slide Review

**Prompt:**
```
[Upload image of PowerPoint slide]

Review this presentation slide for a client pitch and provide feedback on:

1. Visual design effectiveness
2. Information clarity
3. Message hierarchy
4. Suggestions for improvement
5. Any elements that might confuse the audience

Audience: CFOs and financial decision-makers
```

---

### 4.2 Google Workspace Integration

#### Task: Gmail Draft Assistance

**Prompt:**
```
I need to respond to this email from a potential client:

[Forward/paste email]

Help me craft a response that:
- Acknowledges their concerns about pricing
- Emphasizes value proposition without being defensive
- Proposes a meeting to discuss customized solutions
- Maintains professional and consultative tone
- Ends with clear call-to-action

Keep it concise (under 150 words).
```

---

#### Task: Google Sheets Formula Creation

**Prompt:**
```
I have a Google Sheet with student grades and need formulas:

Column A: Student names
Column B-E: Exam scores (4 exams)
Column F: Attendance percentage

I need formulas to:
1. Calculate weighted average (exams 70%, attendance 30%)
2. Assign letter grades (A: 90+, B: 80-89, C: 70-79, D: 60-69, F: <60)
3. Count how many students got each grade
4. Find the class average

Provide the exact formulas I should use.
```

---

### 4.3 Research and Information Gathering

#### Task: Competitive Intelligence

**Prompt:**
```
Research and summarize the following about Tesla's business model:

1. Primary revenue streams
2. Key competitive advantages
3. Main competitors and how Tesla differentiates
4. Recent strategic initiatives (last 12 months)
5. Major challenges or risks

Format as a 2-page brief suitable for an MBA case discussion.
Use current information (as of your knowledge cutoff).
```

---

#### Task: Market Trend Analysis

**Prompt:**
```
Analyze the current state of the cryptocurrency market focusing on:

1. Major developments in the past year
2. Regulatory landscape changes
3. Institutional adoption trends
4. Key risks and opportunities
5. Implications for traditional financial institutions

Target audience: Traditional bank executives considering crypto strategy.
Keep it balanced - neither overly bullish nor bearish.
```

---

## 5. Image Generation Prompts {#image-generation}

https://gemini.google.com/ (free for ODU faculty and students - login using ODU email)

https://chatgpt.com/

https://openai.com/index/dall-e-3/


### 5.1 Business Presentation Graphics

#### Concept Illustrations

**Prompt for Nano-Banana/DALL-E/Midjourney/Stable Diffusion:**
```
Create a professional business illustration showing:

"Digital transformation in traditional banking"

Style: Modern, clean, corporate
Elements: Bank building transitioning to digital/cloud elements
Color scheme: Blue and white (trust/professionalism)
Mood: Progressive, optimistic
Composition: Left-to-right progression
Format: Horizontal, suitable for presentation slide
No text/labels in the image
```

---

#### Infographic Elements

**Prompt:**
```
Design a simple icon set for financial concepts:

1. Revenue Growth (upward arrow with coins)
2. Cost Reduction (downward arrow with dollar sign)
3. Market Expansion (globe with network)
4. Innovation (lightbulb with gear)

Style: Minimalist, flat design, single color (navy blue)
Format: Set of 4 icons, same size
Background: Transparent
Usage: PowerPoint presentation
```

---

### 5.2 Marketing and Branding

#### Social Media Graphics

**Prompt:**
```
Create a LinkedIn post image for:

Topic: "5 Financial Planning Tips for Small Business Owners"

Style: Professional yet approachable
Layout: Text-friendly (leave space for overlay text)
Colors: Navy blue, gold, white
Mood: Trustworthy, expert
Include: Subtle financial imagery (charts, growth concepts)
Avoid: Stock photo clichés, overly corporate look
Format: 1200x628px (LinkedIn optimal)
```

---

#### Event Promotional Material

**Prompt:**
```
Design a header image for a business school webinar:

Event: "AI in Finance: Opportunities and Challenges"
Theme: Intersection of technology and finance
Style: Modern, tech-forward but not sci-fi
Elements: Abstract representation of AI + financial symbols
Colors: Deep blue, silver, accent of bright blue
Mood: Innovative, educational, forward-thinking
Text space: Leave center area clear for event details
Format: 1920x1080px (web banner)
```

---

### 5.3 Educational Materials

#### Concept Diagrams

**Prompt:**
```
Create a visual diagram showing:

"The Product Lifecycle Stages"

Stages: Introduction, Growth, Maturity, Decline
Style: Clean, educational, textbook-quality
Format: Curve graph with labeled stages
Colors: Gradient from green (growth) to red (decline)
Include: Small icons representing each stage
Layout: Horizontal flow, left to right
Background: White/light gray
Usage: Classroom presentation and handouts
```

---

#### Case Study Illustrations

**Prompt:**
```
Illustrate a business scenario:

"A retail store implementing omnichannel strategy"

Show: Physical store + online platform + mobile app integration
Style: Isometric business illustration
Colors: Warm, approachable (orange, teal, white)
Elements: Customer shopping across multiple channels
Mood: Modern, seamless, customer-centric
Perspective: Slightly elevated view showing all channels
No people faces (use simplified figures)
Format: Square (1080x1080px)
```

---

## 6. Everyday Productivity Tasks {#productivity-tasks}

### 6.1 Meeting Assistance

#### Meeting Agenda Creation

**Prompt:**
```
Create a structured agenda for our department meeting:

Purpose: Discuss Q1 budget review and Q2 planning
Duration: 90 minutes
Attendees: 8 faculty members + department head
Key topics to cover:
- Q1 budget performance review
- Resource allocation for Q2
- New hiring priorities
- Upcoming conference opportunities

Format the agenda with:
- Time allocations for each topic
- Expected outcomes
- Who should prepare what
- Decision points that need resolution
```

---

#### Meeting Notes Summary

**Prompt:**
```
I've just come out of a 2-hour strategy meeting. Here are my rough notes:

[Paste messy meeting notes]

Please organize these into:
1. Key decisions made
2. Action items (with owners)
3. Open questions/follow-up needed
4. Important discussion points

Make it suitable for distribution to attendees.
```

---

### 6.2 Email Management

#### Email Triage and Response Templates

**Prompt:**
```
Help me create response templates for common student emails:

1. Extension request (granted)
2. Extension request (denied)
3. Grade dispute acknowledgment
4. Recommendation letter request (yes)
5. Recommendation letter request (no)

For each, provide:
- Professional but warm tone
- Key points to cover
- Appropriate closing
- ~100 words each

Make them adaptable to specific situations.
```

---

#### Newsletter Creation

**Prompt:**
```
Create a monthly department newsletter outline:

Audience: Alumni and current students
Sections needed:
- Faculty achievements/publications
- Student accomplishments
- Upcoming events
- Industry news relevant to our programs
- Featured alumnus spotlight

Suggest:
1. Catchy section titles
2. Content structure for each section
3. Optimal length for each
4. Tone/voice guidelines
5. Call-to-action ideas
```

---

### 6.3 Course Management

#### Syllabus Generation

**Prompt:**
```
Help me create a comprehensive syllabus for:

Course: Financial Markets and Institutions
Level: Undergraduate, junior/senior level
Duration: 15 weeks, 3 credit hours
Class meetings: Tuesday/Thursday, 75 minutes each

Include:
1. Course description and objectives
2. Weekly topic outline (15 weeks)
3. Assessment structure (exams, projects, participation)
4. Required textbook and readings
5. Grading breakdown
6. Course policies (attendance, late work, academic integrity)

Make it comprehensive but student-friendly in tone.
```

---

#### Discussion Question Generation

**Prompt:**
```
Generate 5 thought-provoking discussion questions for each of these topics 
in my Business Ethics course:

Topics:
1. Corporate social responsibility
2. Ethical leadership
3. Stakeholder vs shareholder theory
4. Environmental sustainability in business

Requirements for each question:
- Open-ended (no yes/no answers)
- Encourages critical thinking
- Relates to current business events
- Appropriate for 30-minute discussion
- Mix of applied and theoretical
```

---

### 6.4 Research Support

#### Grant Proposal Outline

**Prompt:**
```
I'm applying for a research grant to study "Impact of fintech on 
traditional banking customer behavior."

Help me create an outline for the proposal with these sections:

1. Executive Summary
2. Background and Significance
3. Research Questions
4. Methodology
5. Expected Outcomes
6. Budget Justification
7. Timeline

For each section, provide:
- Key points to address
- Suggested length
- Tone and emphasis
- Common pitfalls to avoid

Total proposal length: 15 pages
```

---

#### Literature Gap Analysis

**Prompt:**
```
I'm researching "blockchain applications in supply chain management."

Based on the current state of research, help me:

1. Identify what's been well-researched already
2. Find gaps or under-explored areas
3. Suggest novel research questions
4. Identify methodological approaches not yet tried
5. Propose interdisciplinary angles

Frame this as potential research opportunities for publication 
in top-tier journals.
```

---

## 7. Advanced Business Use Cases {#advanced-use-cases}

### 7.1 Strategic Analysis

#### SWOT Analysis

**Prompt:**
```
Conduct a comprehensive SWOT analysis for a university business school 
in the current higher education landscape.

Consider:
- Online education competition
- Changing student demographics
- Technology integration
- Employer expectations
- Funding challenges
- Accreditation requirements

For each category (Strengths, Weaknesses, Opportunities, Threats):
- List 5-7 specific items
- Explain why each is significant
- Suggest strategic implications

Make it actionable for strategic planning purposes.
```

---

#### Scenario Planning

**Prompt:**
```
Create 3 distinct future scenarios for the accounting profession 
in 2030, considering AI and automation:

Scenario 1: "Automation Dominant" - AI handles most routine work
Scenario 2: "Augmented Professional" - Human-AI collaboration
Scenario 3: "Human Premium" - Specialized high-value human work

For each scenario:
1. Describe the key characteristics
2. Identify drivers that would lead to this outcome
3. Implications for education and training
4. Skills that would be most valuable
5. Business model changes

Make each scenario plausible and distinct.
```

---

### 7.2 Data Interpretation

#### Survey Results Analysis

**Prompt:**
```
I conducted a student satisfaction survey (n=150) with these results:

[Paste survey data summary]

Help me:
1. Identify the most significant findings
2. Find patterns and correlations
3. Compare to previous year (if provided)
4. Suggest root causes for low-scoring areas
5. Recommend specific improvement actions
6. Create a summary for presentation to administration

Make insights actionable and prioritized.
```

---

#### Financial Ratio Analysis

**Prompt:**
```
Analyze these financial ratios for a retail company:

Current Ratio: 1.2
Quick Ratio: 0.8
Debt-to-Equity: 1.5
ROE: 12%
ROA: 6%
Gross Margin: 35%
Net Margin: 4%
Inventory Turnover: 6x

Compare to industry averages:
Current Ratio: 1.5
Quick Ratio: 1.0
Debt-to-Equity: 1.0
ROE: 15%
ROA: 8%
Gross Margin: 38%
Net Margin: 6%
Inventory Turnover: 8x

Provide:
1. Assessment of financial health
2. Areas of concern
3. Positive indicators
4. Recommendations for management
5. Investment perspective (buy/hold/sell reasoning)
```

---

### 7.3 Content Creation

#### Case Competition Prep

**Prompt:**
```
Our students are preparing for a case competition. 
The case is about a struggling department store chain.

Help me create practice materials:

1. List of strategic questions judges typically ask
2. Framework for analyzing retail turnaround situations
3. Key metrics to focus on
4. Common pitfalls in presentation
5. Sample executive summary structure

Make it aligned with how top business schools evaluate 
case competition performance.
```

---

#### Workshop Content Development

**Prompt:**
```
Design a 3-hour workshop on "Personal Financial Planning 
for Early Career Professionals"

Target audience: Recent graduates, ages 22-27

Outline should include:
1. Module topics (6 modules, 30 min each)
2. Learning objectives for each module
3. Interactive activities
4. Key takeaways
5. Resource materials to provide
6. Assessment/practice exercises

Make it practical and immediately actionable.
Balance education with engagement.
```

---

## 8. Common Pitfalls and How to Avoid Them {#pitfalls}

### ❌ Pitfall #1: Vague Prompts

**Bad Example:**
```
Tell me about marketing
```

**Why It Fails:** Too broad, no context, unclear goal

**✅ Better:**
```
Explain the 4 Ps of marketing (Product, Price, Place, Promotion) 
with modern examples from tech companies. Target audience is 
undergraduate business students with no prior marketing knowledge.
Aim for 500 words with 2 examples per P.
```

---

### ❌ Pitfall #2: No Context or Background

**Bad Example:**
```
Is this a good investment?
```

**Why It Fails:** AI doesn't know what "this" is, your goals, risk tolerance

**✅ Better:**
```
I'm considering investing in Company X stock. 

Context:
- Investment horizon: 5 years
- Risk tolerance: Moderate
- Portfolio: Currently 60% stocks, 40% bonds
- Goal: Retirement savings

Company X details:
- P/E ratio: 25
- Dividend yield: 2%
- 5-year growth: 15% annually
- Sector: Technology
- Market cap: $50B

Analyze whether this fits my investment profile and goals.
```

---

### ❌ Pitfall #3: Asking for Absolute Answers to Subjective Questions

**Bad Example:**
```
What's the best business strategy?
```

**Why It Fails:** There's no universal "best" - it depends on many factors

**✅ Better:**
```
I'm consulting for a mid-sized manufacturing company facing 
increased competition from low-cost imports.

Company profile:
- Revenue: $50M annually
- Employees: 200
- Profit margin: 8%
- Strengths: Quality, customer relationships, customization
- Weaknesses: Higher costs, limited marketing

Suggest 3 strategic options they should consider, with pros 
and cons of each. Consider their specific circumstances.
```

---

### ❌ Pitfall #4: Not Specifying Format or Length

**Bad Example:**
```
Summarize this article
[Long article text]
```

**Why It Fails:** You might get 2 sentences or 5 pages

**✅ Better:**
```
Summarize this article in exactly 3 paragraphs:
- Paragraph 1: Main argument (100 words)
- Paragraph 2: Supporting evidence (100 words)
- Paragraph 3: Implications and conclusions (100 words)

Total length: ~300 words

Target audience: Busy executives who need key takeaways

[Article text]
```

---

### ❌ Pitfall #5: One-Shot Prompting (Not Iterating)

**Better Approach - Iterative:**

```
First prompt:
"Create an outline for a presentation on cryptocurrency 
for traditional finance professionals"

Review output, then:
"Expand section 3 on blockchain technology - make it more 
accessible to non-technical audience"

After review:
"Add 3 case studies of real-world applications in banking"

After review:
"Create speaker notes for slides 5-10, focusing on potential 
objections from traditional bankers"
```

**Key Insight:** The first output is rarely perfect. Iterate!

---

### ❌ Pitfall #6: Ignoring Token Limits

**Problem:** Very long prompts or expecting very long outputs

**Solutions:**

1. **Break into chunks:**
```
"I have a 50-page report to summarize. I'll feed it to you 
in 5 sections. After each section, provide a summary. 
At the end, I'll ask for an overall synthesis.

Section 1:
[Text]
```

2. **Use follow-ups:**
```
First: "Summarize the key findings"
Then: "Now elaborate on finding #3"
Then: "Provide recommendations based on finding #3"
```

---

### ❌ Pitfall #7: Not Providing Examples

**Bad Example:**
```
Write in a professional tone
```

**✅ Better:**
```
Write in a professional tone. Here's an example of the style I want:

"The quarterly results demonstrate sustained momentum across 
core business segments. While macroeconomic headwinds persist, 
our diversified portfolio and operational efficiency initiatives 
position us well for continued value creation."

Now apply this style to:
[Your content]
```

---

### ❌ Pitfall #8: Expecting Real-Time Data

**Problem:**
```
What's Apple's stock price right now?
```

**Why It Fails:** LLMs don't have real-time data access (unless connected to search)

**✅ Better Approach:**
```
Based on historical patterns and the company's fundamentals, 
what factors should I monitor when evaluating Apple stock?

Create a checklist of:
- Financial metrics to track
- Industry trends to watch
- Competitive dynamics to consider
- Macroeconomic indicators relevant to Apple
```

---

## 9. Pro Tips for Maximum Effectiveness

### 🎯 Tip 1: Use "Acts As" Framing

Start prompts with a role definition:
- "Act as a financial advisor..."
- "You are a marketing consultant..."
- "Take the role of a skeptical CFO..."

This sets the perspective and expertise level.

---

### 🎯 Tip 2: Request Alternative Perspectives

```
Analyze this decision from three perspectives:
1. As a risk-averse CFO
2. As a growth-focused CEO
3. As a shareholder

Show how each would view it differently.
```

---

### 🎯 Tip 3: Use Constraints Creatively

```
Explain portfolio diversification using ONLY food analogies.
Make it memorable for students.
```

Constraints force creativity and clarity!

---

### 🎯 Tip 4: Ask for Citations/Sources

```
Explain the Efficient Market Hypothesis. 
Cite the original sources and key researchers who developed it.
Include at least 3 seminal papers.
```

Helps verify accuracy and provides learning resources.

---

### 🎯 Tip 5: Request Self-Critique

```
[Provide your draft analysis]

Now critique this analysis:
1. What assumptions might be flawed?
2. What alternatives weren't considered?
3. What data would strengthen it?
4. What would a skeptic challenge?
```

---

### 🎯 Tip 6: Use Temperature Metaphors for Creativity

When you want:
- **Very creative/diverse outputs**: "Be creative and suggest unusual approaches"
- **Precise/consistent outputs**: "Be precise and follow standard frameworks"

---

### 🎯 Tip 7: Chain of Thought

For complex problems:
```
Solve this step by step:

1. First, identify the key variables
2. Then, determine what data we need
3. Next, outline the analysis approach
4. Finally, work through the calculations

Show your reasoning at each step.
```

---

### 🎯 Tip 8: Specify Output Structure

```
Format your response as:

**Summary** (2-3 sentences)

**Analysis**
- Point 1: ...
- Point 2: ...
- Point 3: ...

**Recommendation** (bold, 1 sentence)

**Next Steps**
1. ...
2. ...
3. ...
```

---

## 10. Quick Reference: Prompt Templates

### Template 1: Analysis Request
```
Analyze [TOPIC] focusing on:
1. [Aspect 1]
2. [Aspect 2]
3. [Aspect 3]

Context: [Your situation]
Audience: [Who will read this]
Length: [Word/page count]
Format: [How to structure]
```

### Template 2: Content Creation
```
Create [TYPE OF CONTENT] about [TOPIC]

Purpose: [Why this is needed]
Audience: [Who will use it]
Tone: [Professional/casual/academic]
Length: [Specific]
Must include: [Required elements]
Avoid: [What not to do]
```

### Template 3: Problem-Solving
```
I'm facing this challenge: [DESCRIPTION]

Context:
- Constraint 1: ...
- Constraint 2: ...
- Goal: ...

Please suggest:
1. 3 possible approaches
2. Pros and cons of each
3. Your recommended path forward with rationale
```

### Template 4: Learning/Explanation
```
Explain [CONCEPT] to [AUDIENCE]

Use:
- Simple language
- Real-world examples
- Analogies where helpful
- Visual descriptions

Avoid:
- Jargon (unless explained)
- Assumptions about prior knowledge

Structure: [Specify sections]
Length: [Word count]
```

### Template 5: Review/Feedback
```
Review this [DOCUMENT TYPE]:

[Paste content]

Provide feedback on:
1. [Aspect 1]
2. [Aspect 2]
3. [Aspect 3]

Format feedback as:
- Strengths (what works)
- Improvements (specific suggestions)
- Critical issues (must fix)
```

---

## 11. Conclusion: Your LLM Journey

### Remember:

1. **Start Simple**: Don't overthink it. Begin with clear, direct prompts.

2. **Iterate**: Your first prompt won't be perfect. Refine based on results.

3. **Experiment**: Try different models for different tasks. Each has strengths.

4. **Learn from Examples**: Save prompts that work well. Build your library.

5. **Stay Ethical**: Don't use LLMs to do your core intellectual work, use them to enhance it.

### The New Skill:

Prompt engineering is becoming as important as:
- Excel proficiency in the 2000s
- Email communication in the 1990s
- Computer literacy in the 1980s

**Master it now, and you'll have a significant advantage in the AI-augmented workplace.**

---

### Additional Resources:

- **OpenAI Prompt Engineering Guide**: https://platform.openai.com/docs/guides/prompt-engineering
- **Anthropic Claude Best Practices**: https://docs.anthropic.com/claude/docs/
- **Google Skills**: https://www.skills.google/paths/2337/course_templates/1229

---



**Instructor**: [Rochana R. Obadage](https://rochanaro.github.io/)  
**Last Updated**: April 17, 2026
