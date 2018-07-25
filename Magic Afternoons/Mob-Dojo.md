# Mob Dojo Activity

Mob programming is best defined as a software development approach where a team works on the same thing, at the same time, in the same space, and on the same computer. It is very similar to pairing, and involves more people.

Mob programming naturally favors the Lean concept of flow efficiency rather than resource efficiency. So if you value getting things done and delivered to your customers, then yes, mobbing is very productive.

This afternoon the objective is to complete a coding exercise using some very specific mob programming techniques.

We will form groups with a minimum of 4 members and a maximum of 6 per mob and follow these rules:

## Rules

The team will start with 3 roles:

* **Driver** - acts as a "smart keyboard"; she should not type whatever she wants, but interprets the direction of the Navigator(s) into code. The `Navigator(s)` thoughts must travel through the driver.

* **Navigator** - you will communicate your thoughts to the `Driver`.  Your thoughts have to go through their hands to become code.

* **Observer** - you will pay close attention and contribute your ideas and suggestions to other members of the mob based on the rules in each round.

### Round 1 - Practice Patience

Rules for this round are: Only one Navigator can talk. Everyone else observes. The Driver may not type any code without explicit direction from the single Navigator. Navigator, you will verbalize your thoughts so your ideas flow through the Driver and become code in the computer. Every 5 minutes everyone will rotate until each person has been a Driver, Navigator, and Observer.  During this round Observers should not speak. Instead they should pay close attention and follow what is happening so they are prepared for the next role change.

### Round 2 - Phone a Friend

All the same rules apply as from round 1, but now: The Navigator can ask a question of any Observer if they need help. Continue to rotate through the roles every 5 minutes.

### Round 3 - Make Order from Chaos

Same rules as round 2, but in addition now all other Observers can raise their hand and if called upon they can talk. Continue to rotate through the roles every 5 minutes.

### Round 4 - Teamwork Makes the Dreamwork

Same rules as round 3, but now everyone is a navigator, there are no longer any observers. Everyone (except the driver) can now help contribute ideas and direction as a navigator. You are now working as a full mob team. Continue to rotate through the roles of Navigator and Driver every 5 minutes.

## The Project

Create a web based mob timer that is hard to ignore, but also not overly annoying
Should be able to do the following:

### Level 1

* Create a public repository on GitHub for your project
* Create a basic web based application with:
  * Ability to set custom duration
  * Start, stop buttons
  * counts down and then play a sound

### Level 2

* Ability to add names and display who should be driving
* Ability to display who should be navigating

### Level 3

* Ability to skip a user
* Ability to randomize the order of users
* Ability to add a random amount of time for a user

### Level 4

* Publish as an electron app for desktop use

### Level 5

* Publish as a react native app for mobile use

## Conclusion

By the 4th round you should be acting like a real Mob programming team.  Here are some rules to consider following moving forward:

- Create teams with members that have all the right skills for the task
- Least amount of code to achieve the goal
- All code must go through another persons hands
- Start with writing tests (unless research is required)
- Better to start something than debate the best way to do it
- Refactor at every opportunity
- Start a feature together without upfront detailed requirements
- Always be 5min away from production
- Retrospective every day (focus on the good)
- Retrospective at the end of every feature