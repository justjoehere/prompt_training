# Example Prompts Demonstrating Prompt Components

*These examples show how prompt components affect AI analysis of the same source material - a podcast transcript about AI implementation in business.*

## 1) Task Only

```
Summarize this transcript.
```

**Expected Response:** A generic, chronological summary that mentions speakers and topics but lacks focus or clear takeaways. Will likely include everything equally without prioritizing key insights or actionable information.

---

## 2) Task + Context

```
Summarize this transcript.

Context: I'm a business owner who attended a conference session called "The AI Revolution is Here... Right?" The session covered generative AI evolution, myths vs. reality, industry implications, and ethical considerations. I took notes but missed some key points and need to extract the most important business insights and practical advice for someone considering AI implementation.
```

**Expected Response:** Now focused on business-relevant insights rather than general AI discussion. Will prioritize practical advice, real-world examples, and actionable recommendations while filtering out purely technical or theoretical content.

---

## 3) Task + Context + Persona

```
Summarize this transcript.

Context: I'm a business owner who attended a conference session called "The AI Revolution is Here... Right?" The session covered generative AI evolution, myths vs. reality, industry implications, and ethical considerations. I took notes but missed some key points and need to extract the most important business insights and practical advice for someone considering AI implementation.

Persona: Respond as a business consultant who specializes in helping companies adopt new technologies. You're skilled at translating technical discussions into practical business strategy and identifying the most critical insights for decision-makers.
```

**Expected Response:** Takes on the voice of an experienced consultant, emphasizing strategic implications and risk management. Will frame insights in business terms, highlight patterns across the discussion, and provide contextual advice about implementation priorities.

---

## 4) Task + Context + Persona + Format

```
Summarize this transcript.

Context: I'm a business owner who attended a conference session called "The AI Revolution is Here... Right?" The session covered generative AI evolution, myths vs. reality, industry implications, and ethical considerations. I took notes but missed some key points and need to extract the most important business insights and practical advice for someone considering AI implementation.

Persona: Respond as a business consultant who specializes in helping companies adopt new technologies. You're skilled at translating technical discussions into practical business strategy and identifying the most critical insights for decision-makers.

Format: Structure your summary as:
1. "Key Insights" - 3 most important takeaways about AI for business
2. "Reality Check" - What AI can and cannot do right now  
3. "Risk Factors" - Main concerns and how to mitigate them
4. "Next Steps" - Practical actions to consider
5. "Red Flags" - Warning signs or mistakes to avoid
```

**Expected Response:** Highly organized and scannable, with clear sections that serve different decision-making needs. Business owner can quickly navigate to the information most relevant for their current situation and implementation stage.

---

## 5) Task + Context + Persona + Format + Tone

```
Summarize this transcript.

Context: I'm a business owner who attended a conference session called "The AI Revolution is Here... Right?" The session covered generative AI evolution, myths vs. reality, industry implications, and ethical considerations. I took notes but missed some key points and need to extract the most important business insights and practical advice for someone considering AI implementation.

Persona: Respond as a business consultant who specializes in helping companies adopt new technologies. You're skilled at translating technical discussions into practical business strategy and identifying the most critical insights for decision-makers.

Format: Structure your summary as:
1. "Key Insights" - 3 most important takeaways about AI for business
2. "Reality Check" - What AI can and cannot do right now  
3. "Risk Factors" - Main concerns and how to mitigate them
4. "Next Steps" - Practical actions to consider
5. "Red Flags" - Warning signs or mistakes to avoid

Tone: Write in a balanced, pragmatic tone that cuts through the hype while acknowledging AI's genuine potential. Be direct and honest about both opportunities and challenges. Use confident, actionable language that helps the reader feel informed rather than overwhelmed. Avoid both techno-optimism and fear-mongering.
```

**Expected Response:** Combines all elements to create an authoritative, well-structured analysis that feels like advice from a trusted advisor. The tone makes complex information accessible while building confidence in decision-making.

---

## What Users Will Experience:

**Task Only:** Raw information dump with no business focus
**+ Context:** Becomes business-relevant and targeted  
**+ Persona:** Gains strategic perspective and credibility
**+ Format:** Becomes actionable and easy to navigate
**+ Tone:** Becomes engaging and confidence-building

Users can run the same transcript through each prompt version and see dramatically different results from the same source material.