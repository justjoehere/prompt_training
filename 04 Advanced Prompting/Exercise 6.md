# Advanced Prompting Techniques Exercises

## Exercise 1: Prompt Chaining

**Business Scenario:** Create a comprehensive competitive analysis report for your industry.

### Single Prompt Approach (Baseline)
```
Create a competitive analysis report comparing our company to our top 3 competitors, including market positioning, strengths/weaknesses, and strategic recommendations.
```

### Linear Chain Approach
**Chain Step 1: Data Gathering**
```
Identify and list the top 3 competitors in [your industry]. For each competitor, gather basic information about:
- Company size and market share
- Primary products/services
- Target customer segments
- Recent major announcements or changes

Output this as a structured data summary.
```

**Chain Step 2: Analysis** 
```
Using the competitor data below, analyze each competitor's positioning relative to our company:

[Insert output from Step 1]

For each competitor, identify:
- 2-3 key strengths that differentiate them
- 2-3 notable weaknesses or gaps
- Their apparent strategic focus or direction

Format as a comparison table.
```

**Chain Step 3: Strategic Synthesis**
```
Based on the competitive analysis below, develop 3-5 strategic recommendations for our company:

[Insert output from Step 2]

Each recommendation should:
- Address a specific competitive gap or opportunity
- Be actionable within 6-12 months
- Include potential risks or challenges
- Estimate resource requirements (High/Medium/Low)

Format as prioritized action items.
```

**Chain Step 4: Executive Summary**
```
Create a 1-page executive summary combining the analysis and recommendations below into a cohesive report suitable for C-level presentation:

[Insert outputs from Steps 1-3]

Include: Key competitive insights, top 3 strategic priorities, and immediate next steps.
```

### Lab Activity (15 minutes)
1. **Choose your approach:** Single prompt OR 4-step chain
2. **Pick an industry:** Use your own or select: SaaS software, consulting services, or e-commerce retail
3. **Test your chosen approach**
4. **Compare results:** Which approach gave you more usable insights?

---

## Exercise 2: Chain of Thought

**Business Scenario:** Analyze whether your company should adopt a 4-day work week policy.

### Direct Approach (Baseline)
```
Should our company adopt a 4-day work week policy? Provide a recommendation with supporting rationale.
```

### Chain of Thought Approach
```
Should our company adopt a 4-day work week policy? Walk through your analysis step-by-step:

Step 1: First, examine the potential benefits of a 4-day work week for our company type and industry. Consider employee satisfaction, productivity, and competitive advantages.

Step 2: Then, analyze the potential risks and challenges. Consider operational requirements, customer service impact, and implementation difficulties.

Step 3: Next, evaluate the financial implications. Consider costs (potential productivity loss, implementation) versus savings (reduced overhead, lower turnover).

Step 4: Consider our specific company context. Think about our current culture, employee demographics, client expectations, and industry norms.

Step 5: Finally, weigh all factors and provide a clear recommendation with 2-3 key implementation considerations.

For each step, clearly explain your reasoning before moving to the next step.
```

### Lab Activity (10 minutes)
1. **Test both approaches** with the 4-day work week scenario
2. **Evaluate the reasoning:** Which approach gave you more confidence in the recommendation?
3. **Identify decision factors:** Which approach helped you consider more relevant variables?

---

## Exercise 3: Tree of Thought

**Business Scenario:** Develop a strategy for entering a new market segment.

### Single Path Approach (Baseline)
```
Our software company wants to expand from serving small businesses to also serving enterprise clients. Develop a market entry strategy.
```

### Tree of Thought Approach
```
Our software company wants to expand from serving small businesses to also serving enterprise clients. Explore multiple strategic approaches:

**Path A - Product-First Strategy:**
Analyze the approach of first developing enterprise-grade features, then marketing to enterprise clients. Consider: required product changes, development timeline, resource allocation, and go-to-market strategy.

**Path B - Partnership Strategy:**
Explore entering the enterprise market through strategic partnerships with established enterprise vendors or consultants. Consider: potential partners, partnership models, revenue sharing, and market access benefits.

**Path C - Acquisition Strategy:**
Examine acquiring an existing enterprise-focused company or product. Consider: acquisition targets, integration challenges, cost analysis, and accelerated market entry benefits.

For each path:
1. Outline the key steps and timeline
2. Identify major risks and mitigation strategies  
3. Estimate resource requirements and ROI potential
4. Assess alignment with company strengths

Finally, compare all three approaches and recommend the most viable path with supporting rationale.
```

### Lab Activity (15 minutes)
1. **Choose a business expansion scenario:**
   - Software company → Enterprise market (provided)
   - Consulting firm → New service offering
   - Retail business → Online sales channel
2. **Test both approaches**
3. **Compare strategic options:** Which approach revealed more strategic alternatives?

---

## Quick Comparison Exercise

After completing 1-2 exercises above, fill out this comparison:

| Technique | Best Use Case | Key Benefit | Time Investment |
|-----------|---------------|-------------|-----------------|
| **Single Prompt** | Simple, straightforward tasks | Speed | ⭐ |
| **Prompt Chaining** | Complex, multi-part deliverables | Comprehensive results | ⭐⭐⭐ |
| **Chain of Thought** | Decision analysis requiring reasoning | Transparent logic | ⭐⭐ |
| **Tree of Thought** | Strategic choices with multiple options | Explores alternatives | ⭐⭐⭐⭐ |

---

## Discussion Questions (5 minutes)

1. **When would you use Prompt Chaining?** What types of business documents or analyses benefit from this approach?

2. **How does Chain of Thought help with decision-making?** When do you need to see the reasoning process?

3. **What strategic decisions would benefit from Tree of Thought?** When is exploring multiple paths worth the extra time?

4. **Resource Trade-offs:** How do you decide when advanced techniques are worth the additional time investment?

---

## Key Takeaways

**Prompt Chaining:** Break complex deliverables into specialized steps
- Best for: Reports, analyses, multi-section documents
- Trade-off: More setup time for higher quality, comprehensive results

**Chain of Thought:** Make reasoning explicit and transparent  
- Best for: Decisions requiring justification, risk analysis, strategic choices
- Trade-off: Longer responses for more trustworthy recommendations

**Tree of Thought:** Explore multiple strategic approaches simultaneously
- Best for: High-stakes decisions, strategic planning, option evaluation
- Trade-off: Significant time investment for comprehensive option analysis

**The Decision Framework:** Choose based on output importance and complexity, not just speed.