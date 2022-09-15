
<img width="1257" alt="image" src="https://user-images.githubusercontent.com/17634377/190291286-2d27fd51-3f0f-448c-a73c-22296abaa3ca.png">

# Commit Driven Development 

> Repo to show some ideas presented in Git Merge 2022 Chicago by Carlo Gilmar.

[🔗 Git Merge 2022 Talk Slides](https://www.slideshare.net/CarloGilmarPadillaSa/git-merge-2022)

# 🚀 Write your commit's descriptions before code 

1. Think first about how to solve your feature and break it up in small steps.
2. Write down a bullet list with this small steps. Every description should represent one of your steps. 
3. Write the lines of code that achieve your steps.
4. After made your commits, read your git log history, this should represent your building process.

# ❤️ Values

- Order and clarity before commit your code.
- Great communication telling how you're coding. 
- Open to feedback and ask questions.
- Invest time in your tools, invest time learning and using git. 

# 🤝 Who should use this approach

- Developers looking for new ways to work.
- Recruiters looking to understand how candidates are working.
- Team leaderships looking to build a culture around their teams.
- Tech companies looking to improve their onboarding experience.
- Tech educators looking to implement new team dynamics.
- Newcomer developers.

# Examples

1. Start with a simple list writting down all the steps you consider are needed to solve your feature in question (probably you'll find more steps during coding)

```
Step 1: Creating an empty elixir project with mix tool
Step 2: Adding simple http server
Step 3: Adding model account with his unit test
Step 4: Adding genserver for manage the account creation flow with his unit test
Step 5: Set ExUnit for running tests in order
Step 6: Adding function for get the current state of the account
Step 7: Running mix formatter
```

2. Write your code.
3. Read your commit log history using some like `git log --pretty=oneline`, can you recognize your coding process? 

```
* 499a51e  2 years, 9 months ago Carlo Gilmar Adding function for try to initialize again an account
* 74e7343  2 years, 9 months ago Carlo Gilmar Running mix formatter
* 7ba0030  2 years, 9 months ago Carlo Gilmar Adding function for get the current state of the account
* 3c13c47  2 years, 9 months ago Carlo Gilmar Set ExUnit for running tests in order
* f6f6866  2 years, 9 months ago Carlo Gilmar Adding genserver for manage the account creation flow with his unit test
* b0c4164  2 years, 9 months ago Carlo Gilmar Adding model account with his unit test
* fd86455  2 years, 9 months ago Carlo Gilmar Adding simple http server
* fe0ceeb  2 years, 9 months ago Carlo Gilmar Creating an empty elixir project with mix tool
```

<img width="1088" alt="image" src="https://user-images.githubusercontent.com/17634377/189939119-735248c5-d31d-4e20-a053-c68a9defc26e.png">

# 🏆 Achievements

- You're able to **read your own building code story** following just the commit descriptions (like reading a cook recipe). 
- You're able to **reproduce the building process** through explore every commit using `git show`.
- Anyone from your team should be able to **follow your coding process**.
- Anyone from your team should be able to **reproduce your coding process**.
- Anyone outside your team, **but with enough context about your stack**, should be able to follow your coding process.
- Anyone outside your team should be able to reproduce your coding process **just using git**.

<img width="1095" alt="image" src="https://user-images.githubusercontent.com/17634377/189939435-aa321529-bd0e-49e5-977d-8a5d9fe36b8a.png">

# 🤔 When to use? 

- You can use this technique before code any feature, this will enforce you to have enough clarity and ask you questions that probably you'll have to ask to your team as well. 
- Building features in this way will give you a way to track your building process in the commit history. You can use this to share with your team.
- If your team is using this approach, you'll be able to learn about their building process. 
- You can incorporate this to your onboarding process of new joiners to teach them how your team is working. 
- You can use this to solve code exercises or code challenges to give to your interviewer another way to understand how you're working.

# Guidelines for programming languages

- [Elixir](langs/elixir.md)

# Traductions

- [Español](traductions/spanish.md)

*TODO SECTIONS*

- Branch history maturation.
- Rebuilding a bunch of commits to create a more useful history.
- Replicate a building history through commits.
- Onboarding feature branches. 
