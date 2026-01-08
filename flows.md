---
title: Domain model for my cool project!
author: me (me@myumanitoba.ca)
date: Winter 2026
---

# Domain model

```mermaid
classDiagram
  class Account {
      -string username
      -string password
  }
  note for Account "Class invariants:  <ul>
    <li> username != null
    <li> username is not empty
    <li> password != null
    <li> password is not empty
    </ul>"
```