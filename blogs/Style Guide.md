# Writing Style Guide

This style guide captures the voice, tone, and structural patterns used across blog.elevate.do content to ensure consistency when Claude assists with writing.

## Voice & Tone

### Conversational Authority

Write with a conversational yet informed voice that blends casual accessibility with technical expertise. Be direct and honest—don't sugarcoat problems or oversell solutions. Apply thoughtful skepticism by questioning hype while exploring genuine potential. Include personal reflection through first-person experiences and real-world anecdotes to make the content relatable and grounded.

### Example Tone Patterns

Your writing should sound natural and engaging, like: "AI slop isn't the biggest problem..." or "This got me thinking about agent identity, and I wanted to share some quick takeaways..." or "Short answer: **Yes.** Long answer: AI fluency is becoming..." (DO NOT USE THESE EXACT FRAMINGS)

## Content Structure

### Frontmatter Format
```yaml
---
title: "Article Title"
description: "Brief description including author and publication date"
---
```

### Content Organization

#### Hook + Context Setting

Start each article with a compelling observation or personal anecdote that immediately draws readers in. Establish the problem or question being explored early, setting clear expectations for what the reader will learn. Always use concrete examples over abstract concepts to make your points tangible and relatable.

#### Clear Section Structure

Organize your content with descriptive headers using markdown (##, ###) to create a clear hierarchy. Break complex topics into digestible sections that flow logically from one to the next. When presenting step-by-step processes or multiple related points, use numbered lists to guide readers through the information systematically.

#### Visual Elements

Enhance your articles with relevant images that include descriptive alt text for accessibility. Insert code blocks for technical examples to make implementation details clear. Use blockquotes strategically to highlight key insights, scenarios, or important examples that deserve special attention.

#### Practical Application

Every article should include actionable takeaways that readers can immediately apply. Provide concrete examples and real-world scenarios that demonstrate how concepts work in practice. End with clear next steps or recommendations that guide readers on what to do with the information they've learned.

### Standard Ending Components

#### Social Sharing Cards

Include the standard CardGroup at the end of each article with LinkedIn sharing, X/Twitter sharing, calendar scheduling link, Elevate.do information, and social media follow links. This consistent footer helps readers engage further and share your content with their networks.

#### Co-authorship Credit

When an article is co-authored, acknowledge your collaborator with: "This article was co-authored with [Name]. You can find them on LinkedIn [here](link)." Place this attribution prominently to ensure proper credit.

## Writing Patterns

### Opening Styles

Choose from three effective opening approaches. Start with a **Problem Statement** like "The Model Context Protocol (MCP) has been rapidly emerging..." to immediately establish the topic's relevance. Use a **Personal Anecdote** such as "Had a fascinating chat with Titus Capilnean today..." to create a personal connection. Or make a **Bold Declaration** like "An AI agent's identity is defined by its actions, context, and constraints..." to capture attention with a strong position.

### Emphasis Techniques

Use **bold** formatting for key concepts and important statements that readers shouldn't miss. Apply *italics* for emphasis and when quoting material. Format technical terms and specific tools with `code formatting` to distinguish them from regular text. Employ blockquotes to highlight scenarios, examples, and key insights that deserve special attention.

### Technical Content

When writing about technical topics, explain concepts in accessible language that doesn't alienate non-technical readers while maintaining accuracy. Support explanations with concrete examples and realistic scenarios. Include relevant code samples when they clarify implementation details. Always provide context for acronyms and jargon on first use.

### Structural Elements

Use numbered sections when presenting step-by-step processes or sequential information. Deploy bullet points sparingly for lists and key takeaways when the information doesn't need to flow as continuous prose. Add subheadings to break up long sections and improve scannability. Insert horizontal rules (---) to create clear visual separation between major sections.

## Content Types

### Long-Form Technical Articles

These comprehensive pieces run 2000+ words and dive deep into complex topics. Structure them with multiple sections that follow a clear hierarchy, making extensive use of examples and scenarios to illustrate concepts. Include detailed implementation guidance that readers can follow step-by-step to apply the ideas in their own work.

### Musings & Short Thoughts

These brief pieces of 200-500 words capture quick observations and insights. They often include AI-generated imagery to add visual interest. Write these as personal reflections on current events or emerging trends, maintaining a lighter tone while still delivering substantive insights that provoke thought.

### Business Analysis

These articles present data-driven insights with clear practical implications for readers. Structure them with a clear problem/solution framework that makes the value proposition obvious. Include industry context and competitive analysis to situate recommendations within the broader landscape. End with strategic recommendations that decision-makers can act upon.

## Language Guidelines

### Preferred Phrasings

Write conversationally and directly. Say "Here's what we found:" instead of "Our research indicates." Choose "The reality is more nuanced" over "It's complicated." Invite readers with "Let's explore what this means" rather than the formal "We will examine."

### What to Avoid

Steer clear of corporate jargon and buzzwords that obscure meaning. Don't use overly formal academic language that creates distance from readers. Avoid exaggerated claims or hyperbole that undermine credibility. Choose active voice over passive voice whenever it makes the writing clearer and more direct.

## Quality Standards

### Accuracy

Maintain the highest standards of accuracy by verifying all factual claims and statistics before publication. Provide clear sources for external information to build trust and allow readers to explore further. Test any code examples or technical instructions to ensure they work as described. Double-check company names, product names, and technical terms for correct spelling and usage.

### Readability

Prioritize clarity over complexity in every sentence. Keep paragraphs short—typically 2-4 sentences—to maintain reader engagement. Use transition phrases between sections to create smooth flow and logical progression. Maintain consistent terminology throughout the article to avoid confusion.

### Value Delivery

Ensure every article provides actionable insights that readers can implement immediately. Include practical examples that demonstrate how to apply concepts in real situations. Address genuine problems faced by your target audience rather than theoretical concerns. Balance theoretical understanding with hands-on guidance to serve both learning styles.

## Co-authorship Guidelines

When working with co-authors like Adria Hou, clearly attribute the collaborative nature of the work from the beginning. Maintain a consistent voice throughout the article despite multiple contributors. Include co-author bio links in the standard footer to give proper credit and allow readers to connect. Ensure both perspectives are represented fairly, creating a balanced piece that leverages each author's expertise.

# Workflow

First, identify the appropriate section for your blog post based on its topic and focus. Then write the blog following the style guide above, ensuring it flows as continuous prose rather than bulleted lists. Finally, add the new post to docs.json and move its section to the top of the navigation for visibility.

# Card Group Section
```
---

<CardGroup cols={2}>
  <Card title="Share on LinkedIn" href="https://www.linkedin.com/sharing/share-offsite/?url=https://blog.elevate.do/beacon/claude-artifacts-classrooms" icon="linkedin">
    Share this investment thesis with your network
  </Card>
  <Card title="Share on X" href="https://twitter.com/intent/tweet?url=https://blog.elevate.do/beacon/claude-artifacts-classrooms&text=Fascinating investment thesis on Claude Artifacts transforming classroom personalization" icon="twitter">
    Tweet this article to your followers
  </Card>
  <Card title="Schedule a Chat" href="https://calendly.com/rahul-parundekar/30min" icon="calendar">
    Let's discuss AI in education and potential opportunities
  </Card>
  <Card title="About Elevate.do" href="https://elevate.do" icon="building">
    Learn more about our work in AI infrastructure and workplace transformation
  </Card>
</CardGroup>

<CardGroup cols={2}>
  <Card title="Follow on LinkedIn" href="https://linkedin.com/in/rahulparundekar" icon="linkedin">
    Connect with me for more insights on AI and education
  </Card>
  <Card title="Follow on X" href="https://x.com/rahulparundekar" icon="twitter">
    Follow for real-time thoughts on AI agents and infrastructure
  </Card>
</CardGroup>

---
```

# References

Every article should include proper references to support claims and provide additional resources. When citing a source inline, format it as `([Anthropic][9])` where the number corresponds to the reference list at the end. In the references section, create an unordered list that includes descriptive text about what the reference covers, followed by the citation. For example: "Anthropic on **Artifacts** scale and capabilities; **publish/share/remix** docs.([Anthropic][9])". Then at the bottom of the article, include the full URL with a descriptive title: `[9]: https://www.anthropic.com/news/build-artifacts "Create AI-Powered Apps with Claude Artifacts"`. 
