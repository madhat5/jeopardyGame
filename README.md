# Jeopardy Trivia
###### JS game


### Deployment flow

1. Create development branch
  - from master
    - git checkout -b development
2. Pull @ beginning of day
  - from development
    - git pull origin master
    - (npm install) if needed
3. Create 1 branch per file feature
  - from development
    - git checkout -b file_feature
4. By end of day
  - from branch
    - git add .
    - git commit -m "update details"
    - git push origin file_feature
    - gitHub: Pull request
    - git checkout development
  - from development
    - gitHub: Pull request
    - git branch -d branch_name

---

### Links

- Game templates
  - ...
- [Game Color palettes](http://www.color-hex.com/color-palettes/)
- [Game Wiki](https://en.wikipedia.org/wiki/Jeopardy!)
- Game resources
  - [Jeopardy Archive](http://j-archive.com/)
  - [Trivia 1](http://www.quizwise.com/subjects)
  - [Trivia 2](http://trivia.fyi/)
  - [Trivia 3](http://www.triviacafe.com/categorytrivia/)
  - [UK knowledge](http://pubquizquestionshq.com/categories/general-knowledge)

---

### Functions and objects

#### Objects:
- player
  - paddle 1
  - paddle 2
- Categories
  - questions
  - answers

#### Functions
- Game run
- ...

---

### Notes

- up to 3 players?
- 6 categories, 5 questions per category
- scoreboards
- button prompt (Q/T/P)?
- 3 rounds?
  - Jeopardy
  - Dbl Jeopardy
  - Final Jeopardy
- harcoded questions first? then build scraper/api?
