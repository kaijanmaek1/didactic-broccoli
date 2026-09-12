# Didactic Broccoli

This repository is for my mini Scala-projects. 

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

---

## Why I built this

I created these mini‑projects as part of learning Scala and experimenting with it. 
