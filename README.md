# Shadow-Fox-AI-Revolutionize-the-hiring-platform
Shadow Skills AI analyzes real-world skills and maps them using Graph Theory to identify matches and adjacencies. It introduces a Proof-of-Learnability Score (PLS) and predicts Time-to-Productivity, enabling explainable, future-focused hiring beyond traditional resumes.

How it works-
Here's how Shadow Skills AI works, step by step:

Step 1 — Candidate Submits Their Profile
They enter their name, email, GitHub username, current role, years of experience, and a brief resume summary. This raw text becomes the input for everything that follows.

Step 2 — Skill Extraction
The system scans the resume summary and job title against a database of 20+ known technical skills (Python, React, Docker, SQL, etc.) to build the candidate's actual skill list.

Step 3 — Skill Graph Adjacency
Every skill is mapped to its neighbours in a graph. For example, Python connects to Django, Flask, and Machine Learning. Linux connects to Docker and DevOps. This graph is the backbone of the intelligence — it tells the system what a candidate can learn next, not just what they already know.

Step 4 — PLS Computation (Proof-of-Learnability Score)
Two things are measured:

Skill diversity — how many different skills the candidate has
Adjacency richness — how many onward connections their skills have in the graph
These combine into the PLS (0–100%). Evidence lines are pulled directly from the graph — e.g. "Flask mastery bridges directly into: Django, REST APIs" — so the score isn't abstract, it's backed by proof.

Step 5 — Adjacency Score vs. Job Requirements
For each role, the system identifies the gap skills (what's missing) and checks whether the candidate's existing skills are neighbours of those gaps in the graph. A candidate missing Docker but having Linux scores high adjacency because Linux → Docker is a direct edge.

Step 6 — Time-to-Productivity Prediction
Learning velocity, PLS, and adjacency are averaged into a single velocity number:

Above 70% → 15–30 days
40–70% → 30–60 days
Below 40% → 60+ days
Step 7 — Final Match Score
For each role: Final Score = 0.6 × current readiness + 0.4 × future readiness
This intentionally weights future potential almost as heavily as current fit — the core differentiator.

Step 8 — Explainability Layer
The system writes a plain-English reasoning sentence for every candidate and every role match, explaining why the score is what it is — which skills bridge the gap, what the adjacency score means, and what the predicted timeline is.

Step 9 — Recruiter Dashboard

Link to zip file- https://drive.google.com/file/d/1yBE6saHwFnK_mgoirtiHBoG4xmPEH1kG/view?usp=sharing
Everything surfaces visually: the PLS ring, evidence cards, DNA radar, skill heatmap, role matches with per-role reasoning, and AI insight bullets — so a recruiter can make a decision in under 60 seconds
