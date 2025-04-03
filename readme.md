# Flick
**“One Flick to meet, match, move.”**

> *“One Flick to meet, match, move.”*  
> A mobile-first app where college students can find study buddies, join hangouts, discover events, and connect through anonymous or public posts — all in one flick.

---
## [Flick - Market Research](https://docs.google.com/document/d/1zvPC5alQTCWaZ_ZICgUSWKu2GeD0UqT-fHkMU1YDNbQ/edit?tab=t.0)
---

## 🚀 **Core Functionalities**

### 1. 🔁 **FlickMatch (Study Buddy / FriendRoulette)**
- Swipe-style matching interface.
- Match for: study partners, friends, collab projects.
- Filters: major, study style, social energy, location.
- Weekly roulette option (auto-matches you to someone new every week).
- In-app chat with intro prompts.

### 2. 🎉 **FlickEvents**
- Event board for:
  - Parties
  - Study groups
  - Club activities
  - Pop-up hangouts
- Post your own event (with RSVP, location, and privacy settings).
- Invite friends.
- See who's attending.
- **AI-powered suggestions** based on interests and schedule sync.

### 3. 💬 **VibeWall**
- Microblog: post your thoughts, confessions, questions.
- Choose “Anonymous” or “Username mode”.
- Tag moods like: #vent, #celebrate, #needadvice, #memes.
- Comments and reactions (👀🔥💬).
- **AI moderation** for safety, flagging concerning content for peer listeners or resources.

### 4. 📅 **Smart Event Matchmaker**
- Personalized calendar of recommended events.
- Pulls in club calendars, study sessions, and trending events.
- Suggests events based on:
  - Interests
  - Free time
  - Location
  - Past activity
- Option to sync class schedule.

### 5. 📸 **IRL**
*"What are you up to, right now?"*
A once-a-day prompt (like BeReal) or a live photo feed (like Locket) where users:
* Share a snap of where they are or what they’re doing right now
* Get a peek into friends’ lives in real-time
* Can post public to campus, private to friends, or just for matched people
* Name of Page: 'Moments'

**📱 Feature Breakdown**
* Daily Prompt / Reminder
  * 1x/day you get pinged: “Time to flick a pic 📸”
  * Camera opens → take a quick dual pic (front/back)
  * Add mood (emoji) or quick caption
  * Options to post: friends only, study match, campus-wide

**🧭 Feed/Wall Layout**
- Grid view of friends’ Moments
- Sort by: Today | Friends | Dorm | Class Year
- Show small status tags: “Studying 📖” / “Vibing 🎶” / “Burnt out 🔥”

**💬 Interactions**
- Emoji reacts (🔥👀😭❤️)
- Optional comments
- **AI Summary Tag**: Auto-generates a funny caption or vibe check (e.g. “Definitely finals week 😩”)

---

## 🌐 Page Structure (Figma Design Layout)


### 🏠 **1. Home (Dashboard)**
> Where users land after login. A snapshot of everything cool happening right now.

#### 🧩 Components:
- **Top bar**: “Hi, [Zee] 👋” + profile icon
- **Mood of the Day** (emoji + theme color)
- **Quick Buttons**:
  - [🎉 Discover Events]
  - [🔁 FlickMatch]
  - [💬 Vibe Wall]
- **Today’s Picks**:
  - “People You Might Like” (carousel)
  - “Events Happening Tonight” (carousel)
- **Bottom Nav Bar**:
  - Home 🏠 | Match 🔁 | Events 📅 | Vibe 💬 | Profile 👤

---

### 🔁 **2. FlickMatch Page**
> Swipe to match with study buddies, project partners, or new friends.

#### 🔘 Buttons & Interactions:
- [Filter 🎯] → opens modal: match type, major, dorm, energy level
- [Swipe Cards] → includes name, tags, short intro
- [💚] Like | [❌] Skip | [👀] View Full Profile
- [Auto-Roulette Match? 🎲] (Toggle switch)
- Chat CTA if matched → “Say Hi 👋”

---

### 📅 **3. Events Page**
> Discover, join, or post events happening around campus.

#### 🧩 Tabs:
- **Explore Events**: Grid/List view
- **My Events**: RSVP’d + Created

#### 📦 Each Event Card:
- Title, Host, Date/Time, Tags
- [👀 View Details]
- [✅ RSVP] or [Invite Friends]

#### 🔘 Buttons:
- [➕ Create Event] → opens form modal
- [Filter by Type / Time / Mood]
- [Sync Schedule 📆] (optional)

---

### 🧠 **4. Smart Event Matchmaker**
> Personalized feed of events based on your interests and schedule.

#### 🧩 Layout:
- Feed of “Recommended Events for You”
- Time slots (e.g., “Free at 6 PM? Try this 🔥”)
- Icons: Study | Social | Chill | Club | Hype

#### 🔘 Buttons:
- [👍 I'm In] | [👎 Not Now]
- [⭐ Save Event]
- [📅 Add to Calendar]

---

### 💬 **5. Vibe Wall**
> Anonymous OR username-based space for posting, lurking, and reacting.

#### 🧩 Feed:
- Posts with tags: #vent #celebrate #question
- Mood icon (🔥 🧠 😩 🤣)
- Show/hide usernames toggle
- AI Suggested Replies (for lonely/sad posts)

#### 🔘 Buttons:
- [➕ Post a Vibe] → modal w/ “Anon or Username?” toggle
- [💬 Comment] | [🔥 React] | [🔁 Share]

---

### 📈 **6. MoodMate / Tracker (Optional Tab or Home Widget)**
> Check in with your emotions + get small nudges from AI.

#### 🧩 UI:
- Emoji mood tracker slider (😄 😐 😰 😩)
- Daily journaling prompt
- AI feedback: “You seem low today… want to see uplifting events?”

#### 🔘 Buttons:
- [📝 Journal Today]
- [🎧 Play Chill Playlist]
- [📌 Add to Vibe Wall]

---

### 👤 **7. Profile Page**
> User profile for editing interests, viewing stats, managing privacy.

#### 🧩 Sections:
- Avatar / Username / Bio
- Tags: majors, hobbies, sleep schedule, energy level
- Match History / Event Attendance
- Edit Schedule & Preferences
- Notification Toggles

#### 🔘 Buttons:
- [Edit Profile]
- [Link Calendar 📆]
- [Sign Out]
- [Feedback ✉️]

---

### ✅ Optional Popups/Modals
- **Match Confirmation** → “You and Sam matched! Say hi 👋”
- **Post Success** → “Your vibe’s live!”
- **Burnout Alert** → “You’ve RSVP’d to 5 events this week. Need a break?”

---


## 📱 **App Page Breakdown (Mobile/Web)**

### 🏠 Home
- Quick access to FlickMatch, Events, Vibe Wall.
- Current mood color theme.
- “Today’s Pick” event + friend suggestion.

### 🔁 FlickMatch
- Swipe interface.
- Weekly roulette opt-in toggle.
- Matched users section.
- Chat with prompt starter (e.g., “What’s your go-to dining hall meal?”)

### 🎉 Events
- Upcoming events.
- Filter by type (study, party, club).
- Create Event button.
- RSVP, invite, map integration.

### 📅 Matchmaker
- Calendar with suggested events.
- Sync schedule button.
- “Free This Hour?” suggestions.

### 💬 Vibe Wall
- Post feed (toggle: anonymous / username).
- Filter by mood, dorm, or topic.
- New post + quick emoji reactions.

### 🧠 MoodMate (optional tab or embed in homepage)
- Log mood.
- Get support resources.
- Daily reflection prompt.
- AI quote of the day.

### 👤 Profile
- Interests, tags, schedule preferences.
- Match stats (study matches, friends made, events attended).
- Customizable avatar or emoji ID.

---

## 🌐 **Landing Page (For Web / App Store)**

### 🖼 Hero Section:
**Tagline:** *“One flick to meet, match, move.”*  
CTA: **[Download Now]** / **[Join the Waitlist]**

### 🎯 Value Props:
- ✅ Find real connections, not just followers.
- ✅ Get matched to friends who *actually vibe* with you.
- ✅ Discover events you didn’t even know existed on campus.
- ✅ Vent, celebrate, or just say “hi” — your campus, your wall.

### 📸 Screenshots / Demo GIFs
- FlickMatch swipe
- Event interface
- Vibe Wall posts
- MoodMate AI output

### 💬 Testimonials / Student Quotes
- “Met my best friend through Flick.”
- “Honestly better than Tinder + YikYak + Eventbrite combined.”

### 📦 Features Summary
- Friend/Study Match
- Event Discovery
- Anonymous Posting
- AI-Powered Recs
- Cross-platform

### 🧠 Behind the AI
- Uses ethical machine learning to promote well-being.
- No selling data. Ever.

### 📥 CTA Again
**“Ready to Flick?”**  
Buttons: App Store / Play Store / Join Beta

---

Want a clickable Figma mockup or a README template next? 😎