# Didactic Broccoli

This repository is for my mini Scala-projects while I improve as a programmer (and also perhaps as a human)

## 1. Finnish Flag Generator

The function `suomenLippu(leveys: Double)` constructs the Finnish flag from nine rectangular
components. It calculates a unit size from the given width and builds:

- white background rectangles
- blue vertical cross
- blue horizontal cross
- center piece

The components are combined using `leftOf`, `rightOf`, and `below` operations.

### What I learned
- How to structure visual components in Scala
- How to break a graphic into reusable parts
- How to write clean, readable functions

---

## 2. Sports Team Points Calculator

This part contains two utility functions:

- `leaguePoints(wins: Int, draws: Int)`  
  Calculates total points using the standard 3/1/0 system.

- `teamStats(teamName: String, wins: Int, draws: Int, losses: Int)`  
  Builds a formatted season summary including total matches, result distribution,
  and total points.

### What I learned
- Basic functional programming patterns
- How to return formatted output strings
- How to structure small utility functions

## 3. Course Grade Calculator

This part of the project contains two functions:

- `overallGrade(project: Int, exam: Int, participation: Int)`  
  Calculates a course grade from three components and ensures the result does not exceed 5.

- `verbalEvaluation(projectGrade: Int, examBonus: Int, participationBonus: Int)`  
  Converts the numeric grade into a verbal description using a buffer of predefined terms.

### What I learned
- How to use `math.min` to enforce upper limits
- How to store and access values in a Scala `Buffer`
- How to structure small utility functions cleanly

---

## Why I built this

I created these mini‑projects as part of learning Scala and experimenting with it. This also allows me to see my progress as a programmer. 
