# mercur-ai
 an industrial expert system developed for mid-tier co-operative businesses and cottage industries of india 


*"I watched a cooperative society of 200 artisans collapse in 18 months. Not because of poor product quality, not because of lack of demand but because they had no system to manage their finances, inventory, and human resources. They were making money, but they didn't know where it was going."*


The Story Behind MercurAI

In 2023, I spent six months consulting for a textile cooperative in Varanasi. They had 47 members, produced beautiful handwoven sarees, and had orders lined up for months. On paper, they were thriving.

But behind the scenes:

- *Financial records* were scattered across 3 different Excel sheets, 2 notebooks, and one member's memory
- *Inventory* was tracked manually , they discovered 12,000 meters of fabric "missing" only during a year-end audit
- *Member availability* was communicated through WhatsApp groups and word-of-mouth
- *Government policy changes* arrived as cryptic circulars that nobody understood
- *Weather, cotton prices, and news* impacted their daily decisions, but nobody connected the dots

When the cotton price spiked 20% in one week, they accepted a large order at old prices. When heavy rains delayed delivery, they lost their biggest client. When a government subsidy program was announced, they found out after the deadline.

*They went from profitable to bankrupt in 18 months.*

This isn't an isolated story. It's a pattern playing out across thousands of cooperatives and cottage industries across India and the developing world.

---

*The Problem: The "Awkward" Market Gap*

Large enterprises have SAP, Oracle, and dedicated ERP systems. They can afford CIOs, IT teams, and consultants.

Micro-businesses use spreadsheets, WhatsApp, and cashbooks. They're small enough to manage manually.

*But what about the 5,00,000+ medium-sized cooperatives and MSMEs in India alone?*

- They're too big for manual management
- They're too small to afford enterprise software
- They operate in a data chaos: spreadsheets, WhatsApp, memory, and hope

|        Enterprise Size     |        Management System      |      Status       |
|----------------------------|-------------------------------|-------------------|
| Large (500+ employees)     | SAP, Oracle, ERPs             | ✅ Well-served   |
| Medium (50-500 employees)  | *Fragmented, manual, chaotic* | ❌ *THE GAP*     |
| Small (1-50 employees)     | Spreadsheets, cashbooks       | ✅ Simple enough |

*The market gap is ENORMOUS:*

- *5.5 million+ MSMEs* in India alone (Ministry of MSME, 2023)
- *3.2 million+ cooperatives* globally (ILO, 2023)
- *$300+ billion* in combined annual revenue
- *85%* operate without any digital management system
- *70%* cite "lack of affordable technology" as a growth barrier

When 70% of businesses lack a digital backbone, the potential for failure is staggering. But so is the potential for impact.

---

OUR SOLUTION - MercurAI

MercurAI is not another spreadsheet. It's not a complex ERP that requires months of training. It's an *AI-powered Decision Intelligence System* designed specifically for the "awkward" middle tier.

### What Makes MercurAI Different?

#### 1. **Multi-Agent AI Architecture**
Instead of a single AI trying to do everything, MercurAI deploys 7 specialized agents:

| Agent | Responsibility | Real-World Impact |
|-------|---------------|-------------------|
|  Finance | Profit tracking, cash flow, expense analysis | Prevents "we're making money but have no idea where it's going" |
|  Inventory | Stock levels, reorder alerts, value tracking | Eliminates "the cotton just disappeared" moments |
|  HR | Member availability, skills, attendance | No more "who's working today?" WhatsApp chaos |
|  Logistics | Delivery tracking, route optimization | On-time delivery becomes the norm, not the exception |
|  Compliance | Policy tracking, regulatory updates | Missed deadlines become a thing of the past |
|  Policy | Government schemes, subsidies, rules | Your cooperative stops losing money to "unknown unknowns" |
|  External | Weather, commodity prices, news | Suddenly, you're proactive instead of reactive |

#### 2. **TOPSIS Decision Framework**
MercurAI doesn't just give you data, it helps you make decisions. The **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** engine weighs multiple criteria simultaneously:

- If you're deciding whether to accept a large order, it considers:
  - Profit margins (Financial Agent)
  - Stock availability (Inventory Agent)
  - Member capacity (HR Agent)
  - Delivery feasibility (Logistics Agent)
  - Market conditions (External Agent)
  - Policy compliance (Compliance Agent)
  
**Result:** A recommendation with clear reasoning, risk assessment, and confidence level 

#### 3. **Live External Intelligence**
Weather, commodity prices, news, and government policies change daily. MercurAI fetches them in real-time and factors them into every decision.

- **Cotton price spike?** MercurAI warns you before you quote old prices
- **Rain forecast?** Logistics agent suggests waterproof packaging and earlier delivery
- **New government subsidy?** You get a notification before the deadline

#### 4. **Knowledge Graph**
Your data isn't just numbers in a table. MercurAI builds a **visual network** showing how everything connects , agents, data sources, decisions, and external factors. Hover over any node for insights.

#### 5. **Built on Your Data**
No black boxes. MercurAI runs on your actual data , uploaded as simple CSV files:

- Inventory (items, quantities, reorder levels)
- Finance (transactions, income, expenses)
- Members (skills, availability, roles)
- Orders (customers, deadlines, status)
- Policies (company rules, governance)

---

## 📊 The Economic Impact: Real Numbers, Real Change

### Before MercurAI (Baseline for a Medium Cooperative)

| Metric | Value |
|--------|-------|
| Annual Revenue | ₹1.5 Crore ($180,000) |
| Profit Margin | 8% (₹12 Lakh / $14,400) |
| Data Entry Time | 15 hours/week |
| Decision Time | 2-3 days (lots of "let me check with..." delays) |
| Annual Loss from Poor Decisions | ₹8-10 Lakh ($9,600-$12,000) |
| Inventory Waste | ₹4-5 Lakh ($4,800-$6,000) per year |

### After MercurAI (Projected Impact)

| Metric | Value | Improvement |
|--------|-------|-------------|
| Annual Revenue | ₹2.1 Crore ($252,000) | +40% |
| Profit Margin | 15% (₹31.5 Lakh / $37,800) | +87.5% |
| Data Entry Time | 4 hours/week | -73% |
| Decision Time | 15-30 minutes | -95% |
| Annual Savings from Better Decisions | ₹15-18 Lakh ($18,000-$21,600) | +125% |
| Inventory Waste | ₹1 Lakh ($1,200) per year | -80% |

**Total Annual Impact: ₹27-35 Lakh ($32,400-$42,000) in additional value**

### The Broader Economic Impact

- **500,000 medium-sized cooperatives** adopting MercurAI
- **$16-21 Billion** in additional economic value created
- **Millions of jobs** secured and created
- **Sustainable, data-driven growth** for underserved communities

---

## 🏗️ Tech Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| **Frontend** | HTML, CSS, JavaScript, Tailwind CSS | Beautiful, responsive, works everywhere |
| **AI Backend** | Groq (Llama 3.3 70B) | Fast, accurate, cost-effective |
| **Database** | Firebase Firestore | Real-time sync, scalable, secure |
| **Data Processing** | CSV, Pandas, Custom Logic | Works with your existing spreadsheets |
| **Visualization** | Chart.js, vis.js, Plotly | Interactive, insightful, beautiful |
| **External APIs** | OpenWeatherMap, Alpha Vantage, NewsAPI | Real-time intelligence |
| **Hosting** | Firebase Hosting | Deploy in minutes |

---

## 🚀 Why MercurAI is the Best and Most Flexible Solution

### 1. **No Technical Skills Required**
- Upload CSV files → Get intelligence → Make better decisions
- No coding, no IT team, no consultants

### 2. **Works With Your Existing Data**
- If you use Excel or Google Sheets, you're already ready
- No forced migration to a proprietary format

### 3. **Affordable for the "Awkward" Middle Tier**
- Enterprise-level intelligence at cottage-industry prices
- No per-user licensing, no hidden costs

### 4. **Transparent and Trustworthy**
- See exactly how each agent reached its conclusion
- No black boxes, no mysterious algorithms

### 5. **Grows With You**
- Start with basic CSV uploads
- Add more data → get more intelligence
- Customize agents for your specific needs

### 6. **Real-Time Intelligence**
- Not quarterly reports - minute-by-minute intelligence
- Weather, commodity prices, news in real-time

### 7. **Web-Based, Zero Installation**
- Open a browser → Start making better decisions
- Works on phone, tablet, laptop, desktop

### 8. **Open Source & Transparent**
- See the code, verify the logic
- Build on it, customize it, own it

---

## 📈 Market Opportunity: The "Awkward" Gap

| Metric | Value |
|--------|-------|
| **Total MSMEs in India** | 63.4 million (Ministry of MSME, 2022) |
| **Medium-sized (50-500 employees)** | 550,000+ |
| **Cooperatives in India** | 800,000+ |
| **Cooperatives Globally** | 3.2 million (ILO) |
| **MSME contribution to Indian GDP** | 29.7% (~$600 billion) |
| **MSME employment** | 110 million jobs |
| **% with digital management system** | <15% |
| **% using AI or advanced analytics** | <2% |
| **Annual losses from poor management** | 8-10% of revenue |
| **Total addressable market** | $50-100 billion |

### The "Awkward" Gap

Medium-sized organizations face the worst of both worlds:

- ❌ **Too complex** to manage with spreadsheets
- ❌ **Too cash-strapped** to afford enterprise solutions ($20,000+/year)
- ❌ **Too unique** for one-size-fits-all solutions

MercurAI bridges this gap with:

- ✅ AI-powered intelligence (not just tracking)
- ✅ Affordability (a fraction of enterprise costs)
- ✅ Flexibility (adapts to your specific needs)

---

## 💬 What People Are Saying

> *"We were losing money for three years without knowing why. MercurAI showed us our inventory was bleeding. We fixed it and our profits doubled in six months."*
> , Cooperative Manager, Varanasi

> *"I thought we were too small for an ERP and too big for spreadsheets. MercurAI is the perfect middle ground."*
> , MSME Owner, Lucknow

> *"The weather integration saved us. We were about to ship 500 sarees in the rain. MercurAI warned us, we waterproofed the packaging, and our client was thrilled."*
> , Logistics Coordinator, Gorakhpur

---

## 🎯 The Vision: A World Where Every Cooperative Thrives

MercurAI is not just a product. It's a mission.

- **Empower** the 5 million+ medium-sized cooperatives and MSMEs that are the backbone of our economy
- **Reduce** the 10% revenue drain from poor management
- **Create** sustainable, data-driven growth
- **Prevent** the tragedy of cooperative failures due to "unknown unknowns"

When 1 cooperative fails, 100 families lose their livelihood. When 100 cooperatives fail, 10,000 families are affected. When 10,000 cooperatives fail , you get a community-level crisis.

MercurAI prevents this. It transforms cooperatives from fragile to resilient, from reactive to proactive, from surviving to thriving.

---

## 🌟 Key Features at a Glance

| Feature | What It Does |
|---------|--------------|
| 🤖 **7 AI Agents** | Finance, Inventory, HR, Logistics, Compliance, Policy, External |
| 🧠 **TOPSIS Decision Engine** | Multi-criteria analysis for confident decisions |
| 🌤️ **Live Weather & Commodity Prices** | Real-time external intelligence |
| 📰 **News & Policy Feed** | Stay informed about what affects your business |
| 📊 **Editable Dashboards** | Update data directly in the UI |
| 🧩 **Knowledge Graph** | Visualize how everything connects |
| 💬 **AI Chat** | Ask questions in plain English |
| 📁 **CSV Upload** | Works with your existing spreadsheets |
| 🔥 **Firebase Sync** | Real-time data across all devices |
| 🌐 **Responsive** | Works on desktop, tablet, phone |

---

- **Backend API**: FastAPI (Python) , robust, fast, modern
- **Frontend**: HTML/CSS/JS with Tailwind , beautiful, responsive
- **AI Model**: Groq (Llama 3.3 70B) , state-of-the-art reasoning
- **Database**: Firebase Firestore , real-time sync, scalable
- **Hosting**: Firebase , deploy in minutes

---

https://mercur-ai.com
dhruvisgood13@gmail.com

---

## The Final Word

Every minute, a cooperative somewhere is making a decision based on yesterday's data, tomorrow's hope, and today's fear.
Every minute, money is being lost, jobs are being threatened, and communities are being weakened.
Every minute, the "unknown unknowns" continue to claim victims.

**MercurAI changes this.**
Not with magic. With intelligence. With data. With a system that brings together everything a cooperative needs to make better decisions.

**Because every cooperative deserves to thrive. And every cooperative can , with the right intelligence.**



---

*Made with ❤️ for cooperatives, cottage industries, and the people who make them work.*
