# Enlyft MCP Server Demo Script
## OKR Meeting Presentation

### Demo Overview
**Duration:** 5-7 minutes
**Persona:** Sales Account Executive preparing for a high-value account meeting
**Value Proposition:** Show how Claude Desktop + MCP servers automate research, insights, and outreach

---

## Pre-Demo Setup Checklist

- [ ] Claude Desktop running with MCP servers configured (Enlyft, Email, HubSpot)
- [ ] Select a real target account (suggestion: use a well-known company like "Salesforce" or "Snowflake")
- [ ] Have your email client ready
- [ ] Clear Claude Desktop chat history for a clean demo
- [ ] Test MCP server connections before presenting

---

## Demo Script

### Introduction (30 seconds)

**SAY:**
> "Today I'm going to show you how we're revolutionizing account research and outreach using our Enlyft MCP server integrated with Claude Desktop. What used to take hours of manual research across multiple tools now happens in a single conversation."

---

### STEP 1: Initiate Account Research (Start the scenario)

**SAY:**
> "Let's say I'm an AE preparing for a meeting with [TARGET COMPANY]. I need to understand their tech stack, recent activities, and find the right decision makers. Instead of jumping between tools, I simply ask Claude."

**TYPE IN CLAUDE DESKTOP:**
```
I have an upcoming sales meeting with [TARGET COMPANY]. Can you help me prepare by:
1. Getting their company overview and tech stack insights from Enlyft
2. Checking if we have any existing engagement history in HubSpot
3. Finding key decision makers I should reach out to
4. Drafting a personalized outreach email

Let's start with the company research.
```

**PAUSE & SAY:**
> "Notice I'm requesting data from multiple systems - Enlyft, HubSpot - all in one request."

---

### STEP 2: Claude Retrieves Context from MCP Servers

**EXPECTED OUTCOME:**
Claude will automatically:
- Call Enlyft MCP server to get company data, tech stack, firmographics
- Call HubSpot MCP server to check existing contacts/deals
- Present synthesized information

**SAY (while Claude is working):**
> "Behind the scenes, Claude is now querying our Enlyft database for technographic and firmographic data, checking HubSpot for any existing relationships, and synthesizing this information in real-time."

**WHEN RESULTS APPEAR, HIGHLIGHT:**
> "Look at this - in seconds we have:
> - Company size, industry, and location
> - Their complete tech stack - what they're using today
> - Recent technology adoptions or changes
> - Existing engagement history from HubSpot
>
> This would normally require logging into 3+ different tools."

---

### STEP 3: Generate Meeting Insights

**TYPE IN CLAUDE DESKTOP:**
```
Based on this research, what are the top 3 insights I should bring to the meeting? Focus on opportunities where our product could help them.
```

**EXPECTED OUTCOME:**
Claude generates tailored insights based on:
- Tech stack gaps or opportunities
- Industry trends affecting the account
- Potential pain points based on their current tools

**SAY:**
> "Claude is now analyzing all this data to surface actionable insights - not just facts, but strategic talking points I can use in the meeting. It's identifying gaps in their tech stack, potential pain points, and how our solution fits their needs."

**WHEN INSIGHTS APPEAR:**
> "These insights are gold. They're specific, data-driven, and give me immediate credibility in the conversation."

---

### STEP 4: Find Key Decision Makers

**TYPE IN CLAUDE DESKTOP:**
```
Now find the key decision makers at [TARGET COMPANY] that I should connect with - specifically those involved in [relevant department like "data engineering", "sales operations", "marketing technology"].
```

**EXPECTED OUTCOME:**
Claude uses Enlyft MCP server to retrieve:
- Contact names and titles
- Departments
- Seniority levels
- Contact information if available

**SAY:**
> "Now let's find who we need to talk to. Claude is querying Enlyft's contact database to identify decision makers."

**WHEN CONTACTS APPEAR:**
> "Perfect - we have names, titles, and roles. These are the exact people who would evaluate and purchase our solution."

---

### STEP 5: Generate Personalized Email Outreach

**TYPE IN CLAUDE DESKTOP:**
```
Draft a personalized email to [SELECT ONE DECISION MAKER] that:
- References the insights we discovered
- Mentions their specific tech stack
- Proposes a brief call to discuss how we can help
- Keep it concise and value-focused (under 150 words)
```

**EXPECTED OUTCOME:**
Claude drafts a highly personalized email incorporating:
- Specific company details from Enlyft
- Relevant tech stack mentions
- Tailored value proposition
- Professional tone

**SAY:**
> "Instead of a generic template, Claude is writing a personalized email using all the context we just gathered - their tech stack, company situation, and specific pain points."

**WHEN EMAIL APPEARS:**
> "Look how specific this is - it mentions their actual tools, references real insights, and provides clear value. This isn't a spray-and-pray email."

---

### STEP 6: Send the Email

**TYPE IN CLAUDE DESKTOP:**
```
Send this email to [DECISION MAKER EMAIL] with subject: "Quick question about [RELEVANT TOPIC]"
```

**EXPECTED OUTCOME:**
Claude uses Email MCP server to send the email directly

**SAY:**
> "And now, without leaving this conversation, I can send the email directly."

**AFTER SENDING:**
> "Done. Email sent. Let me show you what we just accomplished in under 5 minutes."

---

## Closing Impact Statement (30 seconds)

**SAY:**
> "Let's recap what just happened:
>
> **Traditional Process:**
> - Log into Enlyft (5 min)
> - Research tech stack and firmographics (10 min)
> - Switch to HubSpot to check history (5 min)
> - Find decision makers across LinkedIn, ZoomInfo (15 min)
> - Draft personalized email (10 min)
> - Copy/paste into email client and send (2 min)
> - **Total: ~45 minutes, 6 different tools**
>
> **With Enlyft MCP + Claude Desktop:**
> - Single conversation, one interface
> - All data retrieved automatically
> - AI-generated insights and personalization
> - **Total: Under 5 minutes**
>
> That's a **9x productivity gain** - and the quality is actually better because we're leveraging AI to analyze and synthesize the data, not just presenting it."

---

## Potential Questions & Answers

**Q: "Is this data real-time?"**
A: "Yes, Claude is querying our live Enlyft database, so the information is as current as our data sync schedule."

**Q: "Can it work with other CRMs besides HubSpot?"**
A: "Absolutely. The MCP architecture is extensible - we can build connectors for Salesforce, any CRM, or internal tools."

**Q: "What about data security?"**
A: "MCP servers run locally and enforce our existing access controls. Claude Desktop doesn't store the data - it's all retrieved on-demand through secure API calls."

**Q: "How hard is it to set up?"**
A: "For end users, it's just a configuration file in Claude Desktop. We handle the MCP server deployment centrally."

---

## Demo Tips

### Before You Start:
1. Practice the flow 2-3 times
2. Have a backup account name ready
3. Test all MCP connections 10 minutes before
4. Clear your Claude Desktop history for a clean demo

### During the Demo:
1. Speak while Claude is processing - don't just wait in silence
2. Highlight when Claude is calling different MCP servers
3. Show enthusiasm about the insights generated
4. Keep the pace moving - this should feel fast and seamless

### If Something Goes Wrong:
- **MCP server timeout:** "Let me retry that query" (usually works on second try)
- **Unexpected response:** Adapt your narrative - "Even better, Claude found..."
- **Technical failure:** Have screenshots of a successful run as backup

---

## Alternative Demo Scenarios

### Scenario A: Competitive Displacement
Target company using a competitor's product (visible in tech stack)
- Highlight competitive intelligence
- Draft email addressing competitor's limitations

### Scenario B: Tech Stack Expansion
Target company already using complementary tools
- Position as natural extension
- Reference existing tools in outreach

### Scenario C: New Market Entry
Target company in industry you're expanding into
- Show industry-specific insights
- Demonstrate research depth

---

## Success Metrics to Mention

If you have data, share:
- "Sales teams using this have reduced research time by X%"
- "Email response rates increased by X% with AI-personalized outreach"
- "Reps can now reach out to X more accounts per day"

---

## Call to Action

**END WITH:**
> "We're rolling this out to the sales team next quarter. If you're interested in early access or want to explore MCP servers for your team, let's connect after this meeting."

---

## Technical Appendix (For Reference)

### MCP Servers Used:
1. **Enlyft MCP Server** - Company intelligence, tech stack data, contact discovery
2. **HubSpot MCP Server** - CRM data, engagement history
3. **Email MCP Server** - Email sending capabilities

### Claude Desktop Configuration:
```json
{
  "mcpServers": {
    "enlyft": {
      "command": "node",
      "args": ["/path/to/enlyft-mcp-server/index.js"]
    },
    "hubspot": {
      "command": "node",
      "args": ["/path/to/hubspot-mcp-server/index.js"]
    },
    "email": {
      "command": "node",
      "args": ["/path/to/email-mcp-server/index.js"]
    }
  }
}
```

---

**Good luck with your demo! 🚀**
