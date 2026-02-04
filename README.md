# Clarity Lite - Gamified Edition 🎮

A **lightweight, gamified version** of Clarity with XP, achievements, and interactive decision scenarios using synthetic personas.

## ✨ What Makes This Special

### 🎯 Gamification Features
- **XP System**: Earn experience points for every action
- **Level Progression**: Start at Level 1, reach Level 10
- **9 Achievements**: From "First Steps" to "Master Planner"
- **Real-time Notifications**: +XP popups and level-up celebrations
- **Progress Tracking**: Visual XP bar and stats dashboard

### 🎭 Synthetic Personas
Experience 3 complete student journeys:

1. **Alex Chen** 👨‍💻 - CS student targeting AI product management
2. **Maria Garcia** 👩‍🎓 - MBA student pivoting to climate consulting  
3. **Raj Patel** 👨‍🔬 - Financial Engineering student aiming for quant trading

Each persona includes:
- Pre-built course plans (2 semesters)
- Curated event recommendations
- Real decision scenarios with analysis
- Unlocked achievements and XP progress

### 🎪 Interactive Experience
- **Smart Recommendations**: See WHY each course/event matches the persona
- **Decision Validation**: Real scenarios with trade-off analysis
- **Event Quests**: Save events to complete quests and earn XP
- **Achievement Hunting**: Track progress toward unlocking all 9 badges

## 🚀 Quick Start

```bash
# 1. Install dependencies
npm install

# 2. Run the app
npm run dev

# 3. Open browser
# http://localhost:3000
```

That's it! No database, no configuration.

## 🎮 How to Play

### Step 1: Choose Your Character
Select one of 3 personas to explore their journey:
- Each has different interests, goals, and course plans
- See their current level and unlocked achievements

### Step 2: Explore Tabs

**📚 Courses Tab**
- View AI-recommended courses with match scores
- Click "Add to Plan" to earn +50 XP
- See why each course fits the persona

**🎪 Events Tab**
- Browse curated networking events and workshops
- Save events as "quests" to earn +30 XP
- Complete event quests to level up faster

**🤔 Decisions Tab**
- Explore real decision scenarios
- See trade-off analysis (prerequisites, workload, career fit)
- Validate decisions to earn +25 XP
- Learn decision-making strategies

**🏆 Achievements Tab**
- Track 9 unlockable achievements
- See progress bars for multi-step achievements
- Earn bonus XP when unlocking

### Step 3: Level Up!
- Complete actions to earn XP
- Watch the XP bar fill up
- Get celebratory notifications when you level up
- Try to reach Level 10!

## 📊 Gamification System

### XP Awards
| Action | XP Earned |
|--------|-----------|
| Add Course to Plan | +50 XP |
| Save Event | +30 XP |
| Validate Decision | +25 XP |
| Unlock Achievement | Varies (50-500 XP) |

### Achievements

1. **First Steps** 🎯 (50 XP) - Complete profile
2. **Course Explorer** 📚 (100 XP) - Add first course
3. **Planner Pro** 🎓 (200 XP) - Plan 4+ courses
4. **Event Hunter** 🎪 (150 XP) - Save 5 events
5. **Risk Aware** ⚠️ (100 XP) - Review risk flags
6. **Decision Maker** ✅ (250 XP) - Validate 10 decisions
7. **Networker** 🤝 (100 XP) - Explore 3 clubs
8. **Streak Starter** 🔥 (200 XP) - Use app 3 days
9. **Master Planner** 🏆 (500 XP) - Plan 2 semesters

### Level Requirements
- Level 1: 0 XP
- Level 2: 100 XP
- Level 3: 250 XP
- Level 4: 500 XP
- Level 5: 1000 XP
- Level 6: 2000 XP
- Level 7: 3500 XP
- Level 8: 5500 XP
- Level 9: 8000 XP
- Level 10: 12000 XP

## 📚 Data Included

### Personas
All 3 personas have complete journeys mapped out:
- **Alex**: AI/ML focus, 7 courses planned, Level 4, 650 XP
- **Maria**: Climate consulting, 7 courses, Level 3, 450 XP
- **Raj**: Quant finance, 7 courses, Level 5, 1100 XP

### Courses (20 total)
- AI/ML: Machine Learning, Deep Learning, NLP, Computer Vision
- Finance: Financial Engineering, Corporate Finance, Trading
- Climate: Climate Economics, Energy Policy
- Business: Consulting, Entrepreneurship, Management

### Events (15 total)
- Career: Google Tech Talk, McKinsey Workshop, Goldman Info Session
- Networking: International Mixer, Alumni Night
- Learning: LLM Workshop, Excel Bootcamp
- Innovation: Climate Showcase, Startup Founders Panel

### Decision Scenarios
Each persona has 1+ decision scenarios with:
- Real course selection dilemmas
- Multi-factor analysis (prerequisites, workload, career fit)
- Confidence scores (70-90%)
- Actionable recommendations

## 🎨 UI/UX Features

### Visual Design
- **Glass morphism effects**: Frosted glass cards
- **Gradient backgrounds**: Purple/blue/pink color scheme
- **Smooth animations**: Hover effects, bounce animations
- **Responsive layout**: Mobile-friendly design

### Interactive Elements
- **Real-time notifications**: XP popups and level-up celebrations
- **Progress bars**: Visual XP tracking
- **Hover effects**: Cards scale up on hover
- **Tab navigation**: Clean, icon-based tabs

## 🛠️ Technical Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **State**: localStorage (no database)
- **Data**: In-memory JSON

## 📁 Project Structure

```
clarity-lite/
├── src/
│   ├── app/
│   │   ├── page.tsx          # Persona selector
│   │   ├── play/page.tsx     # Main game interface
│   │   ├── layout.tsx        # Root layout
│   │   └── globals.css       # Tailwind + custom styles
│   └── lib/
│       ├── data.ts           # 20 courses, 15 events, 6 clubs
│       ├── gamification.ts   # XP, levels, achievements
│       └── personas.ts       # 3 synthetic personas + journeys
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── README.md
```

## 🎯 Learning Outcomes

By exploring different personas, you'll see:

1. **How different students approach planning**
   - AI-focused vs. business-focused vs. quant-focused

2. **Trade-offs in course selection**
   - Prerequisites vs. career relevance
   - Workload vs. interest
   - Cross-school approval requirements

3. **Event selection strategies**
   - Career-focused vs. skill-building
   - Networking vs. learning

4. **Decision-making patterns**
   - Balancing multiple factors
   - Confidence scoring
   - Risk awareness

## 🎮 Play Strategies

### To Maximize XP:
1. Complete all decision validations first (+25 XP each)
2. Save all recommended events (+30 XP each)
3. Add courses to plan (+50 XP each)
4. Focus on multi-step achievements (Planner Pro, Event Hunter)

### To Unlock All Achievements:
- Switch between personas to see different achievement paths
- Each persona pre-unlocks 4 achievements
- Add more courses to unlock "Planner Pro"
- Save events to unlock "Event Hunter"

### To Reach Level 10:
- Complete all actions for all 3 personas
- Total possible XP: ~15,000+
- Requires ~2,500 XP to go from Level 5 to Level 10

## 🔮 What This Demonstrates

### For Product Design:
- Gamification increases engagement
- Progress visualization motivates users
- Real-time feedback feels rewarding
- Personas help users explore without commitment

### For EdTech:
- Decision support > deterministic answers
- Show reasoning, not just recommendations
- Multi-factor analysis teaches critical thinking
- Synthetic data enables safe exploration

### For Student Experience:
- Compare different career paths
- Learn from others' journeys
- Understand trade-offs before committing
- Build confidence through practice

## 💡 Differences from Full Clarity

| Feature | Full Clarity | Clarity Lite |
|---------|--------------|--------------|
| Data | 30 courses, 40 events | 20 courses, 15 events |
| User Model | Custom profile | Pre-built personas |
| Interface | Professional | Gamified |
| Focus | Planning tool | Learning experience |
| Achievements | None | 9 achievements |
| XP System | None | Full system |
| Decision Scenarios | Risk flags only | Full analysis + recommendations |

## 🚀 Future Ideas

- **Multiplayer**: Compare progress with friends
- **Daily Quests**: Log in daily for bonus XP
- **Leaderboards**: Top planners by XP
- **Custom Personas**: Build your own character
- **More Scenarios**: 20+ decision examples
- **Skill Trees**: Unlock advanced planning features

## 📝 Notes

- All data is **synthetic** for demonstration purposes
- Personas are **fictional** but based on real student patterns
- Recommendations are **heuristic-based**, not ML
- Progress is saved to **localStorage** (per persona)
- No database or authentication required

## 🎓 Perfect For

- **Demo/Portfolio**: Show gamification in action
- **User Research**: Test engagement with different personas
- **Educational Tool**: Teach course planning strategies
- **Design Exploration**: Experiment with game mechanics

---

**Built with ❤️ and 🎮 for demonstrating gamified decision support**

Ready to level up? Run `npm run dev` and choose your character!
