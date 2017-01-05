# React + Redux Training

# Rangle.io

---

## Prerequisites

- Access to the command line
- Node JS (v6 or higher)
- NPM (v3 or higher)
- Code editor (Sublime, Atom, etc.)
- Some JavaScript knowledge (ES2014/ES2015)
- Basic React Knowledge (Part 1 of this course)

---

## Structure of this Training

- 1.5 hours training
- 15 min Intro/Slides
- 1h 15 min Live Coding

---

## Table of Contents

This is part 2 of a 3 part series:

- Part 1: Intro to React (3h)
- **_Part 2: Intro to Redux (1.5h)_**
- Part 3: Advanced React and Redux (2h)


---

# Welcome to Redux

![reactredux](content/images/reactredux.png "reactredux")

---

## Why Redux?
- React is great, but as applications get larger and complex, you need to manage global state
- Redux is one solution to this problem: Guard rails for state management
- Useful for sharing data between containers
- Make state mutations predicatble. How? 3 principles.

---

## 3 Principles

- Single source of truth
- State is read only
- Changes are made using pure functions


---
## Flux

![flux](content/images/flux.png "flux")

---

## What is Redux?

- Creation by Dan Abramov
- Like a model layer (MVC)
- Implementation of flux architecture
- Larger, global version of this.state

---

## Redux Lingo

- Action
- Dispatch
- Reducer
- Store

---

## Folder Structure

![folderss](content/images/folderss.png "folderss")

---

## Enough talking, lets code!

---

# What is React + Redux?

- Redux is a framework agnostic tool to manage state
- 3 principles: single source of truth, read-only state, pure functions
- `react-redux` connects the two through `<Provider>` and `connect()`
- With React and Redux you can now build large, scalable, SPAs


