# ⚽ Scratch Soccer Game – Ben vs Jordyn  

A fun soccer game where **Ben** and **Jordyn** kick the ball back and forth on the field. The ball moves between them, players kick, celebrate, and you even hear the referee’s whistle and a cheering crowd!  

---

## 🎯 Objectives
1. Set up the soccer field and characters (Ben, Jordyn, and the Ball).  
2. Make Ben kick the ball and celebrate.  
3. Make the ball move towards Jordyn.  
4. Make Jordyn block the ball and react.  
5. Return the ball to Ben’s side and score a goal with cheering sounds.  

---

## 🏟️ What You Need
- **Backdrop**:  
  - *Soccer 2* (under **Sports**) → perfect because players can play back and forth on this field.  

- **Sprites**:  
  - **Ben** → First player, starts on the **left goal post**.  
  - **Jordyn** → Second player, stands on the **right goal post**.  
  - **Soccer Ball** → Placed at the center of the field.  

---

## ⚙️ Setup
1. Open Scratch and choose the backdrop **Soccer 2**.  
2. Add sprite **Ben** → place him on the **left goal post**.  
3. Add sprite **Jordyn** → place her on the **right goal post**.  
4. Reduce both players’ **size to 50%** (so they don’t look too big).  
5. Make Jordyn face Ben:  
   - Click **direction** → rotate to `-90` and then press the **center button** to correct posture.  
6. Add sprite **Soccer Ball** → place it at the **center of the field**.  
7. Reduce the ball size to **50%**.  

Now we’re ready to code!  

---

## 🥅 Objective 1: Ben Kicks the Ball

Make sure you **highlight Ben sprite** before coding.  

### Ben’s Script
- **`when green flag clicked` (Events)** → Start the game.  
- **`start sound [Referee Whistle]` (Sound)** → The referee blows the whistle.  
- **`wait (2) seconds` (Control)** → Pause before the kick.  
- **`glide (1) secs to x:0 y:-82` (Motion)** → Move Ben toward the ball.  
- **`switch costume to [ben b]` (Looks)** → Change to Ben’s *kicking pose*.  
- **`say [Goal!] for (2) seconds` (Looks)** → Ben celebrates.  
- **`broadcast [Ball moves to Jordyn]` (Events)** → Send message to move the ball to Jordyn.  

---

## ⚽ Objective 2: The Ball Moves to Jordyn

Make sure you **highlight the Ball sprite**.  

### Ball Script – First Move
- **`when I receive [Ball moves to Jordyn]` (Events)** → Wait for the message.  
- **`glide (1) secs to x:184 y:-56` (Motion)** → Move ball towards Jordyn’s position.  
- **`broadcast [Ball at Jordyn]` (Events)** → Tell Scratch the ball has reached Jordyn.  

---

## 🛡️ Objective 3: Jordyn Blocks the Ball

Now highlight **Jordyn sprite**.  

### Jordyn’s Script
- **`when I receive [Ball at Jordyn]` (Events)** → Wait for the ball.  
- **`switch costume to [jordyn b]` (Looks)** → Switch to Jordyn’s *blocking pose*.  
- **`say [Nice try!] for (2) seconds` (Looks)** → Jordyn reacts after blocking.  

---

## 🎯 Objective 4: Ball Returns and Scores a Goal

Highlight the **Ball sprite again** (since it’s now at Jordyn).  

### Ball Script – Return & Goal
- **`when I receive [Ball at Jordyn]` (Events)**  
- **`glide (1) secs to x:-229 y:-67` (Motion)** → Ball moves back to Ben’s goal.  
- **`start sound [Basketbounce]` (Sound)** → Ball bounce effect.  
- **`start sound [Goal Cheer]` (Sound)** → Crowd cheers loudly.  
- (Optional) **reset ball to center** so the game can be played again.  

---

## ✅ Test the Game
1. Click the **green flag**.  
2. The referee whistle blows.  
3. Ben moves, kicks, and celebrates.  
4. The ball glides to Jordyn.  
5. Jordyn blocks and reacts.  
6. The ball returns to Ben’s goal and the crowd cheers! 🎉  

---

## 🌟 Creative Extensions – Make It Your Own!
Once your game works, try adding:  
1. **Score counter** → each time someone scores, increase the score by 1.  
2. **Timer** → play for 30 seconds to see who wins.  
3. **Keyboard control** → move the ball left or right with arrow keys.  
4. **Extra players** → add more teammates to pass the ball.  
5. **Funny sounds** → replace goal cheer with animal noises or clapping!  

---

## 🕹️ How to Play in Scratch
1. Download this project file (**Soccer Game.sb3**).  
2. Open [Scratch Editor](https://scratch.mit.edu/projects/editor/).  
3. Go to **File → Load from your computer**.  
4. Select the file and click **green flag** to play.  

Enjoy your **Ben vs Jordyn Soccer Game**! ⚽🎉  
