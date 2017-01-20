# React + Redux Training

# Rangle.io

>Presented by:

>Andrei Neagoie - @aneagoie

>Rob Brander - @rbrander

---

## Prerequisites

- Access to the command line
- Node.js (v6 or higher)
- NPM (v3 or higher)
- Code editor (Sublime, Atom, etc.)
- Some JavaScript knowledge (ES5/ES6)
- Basic React Knowledge (Part 1 of this course)

---

## Structure of this Training

- 2 hours training
- 20 min Intro/Slides
- 1h 40 min Live Coding

---

## Table of Contents

This is part 2 of a 3 part series:

- Part 1: Intro to React (3h)
- **_Part 2: Intro to Redux (2h)_**
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

> Image from code.facebook.com

---

## What is Redux?

- Creation by Dan Abramov
- Like a model layer (The 'M' in MVC)
- Implementation of flux architecture
- Larger, global version of `this.state`

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

```bash
$ git clone https://github.com/aneagoie/react-training-RoboDex.git
```

---

# What is React + Redux?

- Redux is a framework agnostic tool to manage state
- 3 principles: single source of truth, read-only state, pure functions
- `react-redux` connects the two through `<Provider>` and `connect()`
- With React and Redux you can now build large, scalable, SPAs


