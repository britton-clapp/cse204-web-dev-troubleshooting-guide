---
title: "CSE204: Troubleshooting Guide"
abstract: "Troubleshooting for TAs."
keywords:
- CSE204
- CSS
author:
- Britton Clapp
paginate: true
backgroundColor: CornSilk
style: |
  h1 {
    color: DarkRed;
  }
  a {
    color: FireBrick;
  }
---

# Troubleshooting Websites

## CSE 204

---

## Github Pages issues

- Github Pages branch
- index.html - did they use a different filename?
- Check commit logs - is the newest commit there?
- Are they editing the right files?

---

# Use Dev Tools Debugger

---

## Javascript

- Javascript at end of body tag.
- Check for spelling errors.
- Call functions from the Dev Tools console.
- Access DOM elements from the Dev Tools console.
- Double-check method names.
- Check properties vs methods:
    - document.getElementById("myDIV").className = "mystyle";
    - element.classList.add("my-class");
- event.preventDefault() on forms to prevent page from reloading.
- getElementsByClassName() returns a collection, not an element.

---

# React

- Try hard-coding API output
- Check props vs state.
- Bind functions - be clear about when.