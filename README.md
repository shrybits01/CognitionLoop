CognitionLoop ∞
AI-Powered Adaptive Learning Graph & Simulator

> Upload your notes. Watch the AI map your knowledge. Quiz your weak spots. Loop until you master it.

Q. What It Is

CognitionLoop is a single-file web app that turns any study material into an interactive adaptive learning session. 
You paste in notes or upload a PDF, the AI extracts topics and scores your baseline mastery, 
then quizzes you with questions targeted at your weakest areas. After each session, 
the knowledge graph updates in real time — showing what you've strengthened and what still needs work. 
Repeat the loop until mastery is complete.

Features 
- AI Knowledge Graph :— Claude automatically detects 5–8 topics from your content and visualizes them as a radar chart, bar chart, and session progress line graph
- Adaptive Quizzing :— Questions are weighted toward your weakest topics; difficulty adjusts per session
- Live Feedback Loop :— Mastery scores update after every quiz using a weighted blend of your old score and new performance
- Before vs After Charts :— See exactly which topics improved each session
- Dark & Light Mode :— Full theme toggle with smooth transitions across all UI and charts
- Interactive UI :— Custom cursor, ripple effects, animated progress rings, streak counter, staggered card animations, and toast notifications
- No backend required :— Runs entirely in the browser; only outbound call is to the Anthropic API

-> How to Use

1. Open `cognition-loop-v2.html` in any modern browser
2. Paste your notes or drop a file into the upload area
3. Choose difficulty and number of questions, then click **Analyze & Build Knowledge Graph**
4. Review your knowledge map — see which topics are strong, developing, or weak
5. Click **Start Quiz** — answer questions, get instant explanations
6. View your **Results** — the graph updates with your new mastery scores
7. Hit **Next Adaptive Round** to loop again with questions re-targeted to your gaps

The Adaptive Loop

```
Upload Content
      ↓
AI Builds Knowledge Graph (baseline scores)
      ↓
Adaptive Quiz (weak areas prioritized)
      ↓
Scores Update (weighted: 60% old + 40% new)
      ↓
Updated Graph → Repeat ↑
```

Each loop narrows in on gaps until all topics reach strong mastery (≥ 70%).

---

## Project Info

Built for **Hackureka II** by **Team SrujanikaQ**  
College: Chandigarh University  
Theme: CognitionLoop — AI-Powered Adaptive Learning Graph & Simulator
