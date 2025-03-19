---
title: "Gift Grouping App - In Progress"
excerpt: "An Android mobile application that allows users to efficiently track and manage gift purchases within groups. This personal project utilizes Java, Android Studio, SQLite, and RESTful APIs. [*repo*](https://github.com/acortez1003/GiftLoop)"
collection: portfolio
---

I'm currently developing an app that allows users to track and manage gift purchases within a group. [*repo*](https://github.com/acortez1003/GiftLoop)

## Current Progress

* **Data Models**: Set up models for `User`, `Group`, and `Gift` to define the structures of the data.
* **DAO Classes**: Implemented DAO (Data Access Object) classes for each model, including `@Insert`, `@Delete`, and specific queries to retrieve all groups or all gifts for a particular group.
* **Repository Setup**: Created a repository to interact with the DAOs. This layer is responsible for managing data operations, using the ExecutorService library to handle background threads efficiently.
* **ViewModels**: Set up ViewModels using the Android ViewModel library to manage UI-related data and allow data binding to the UI.

## Next Steps

* **UI Setup**: Implementing the UI using `NavHostFragment` to navigate between screens. Each screen will be structured as individual fragments with corresponding XML layouts.
* **Connecting ViewModels**: After setting up the UI, I'll connect each fragment to its respective ViewModel to handle user interactions and data updates.
* **Amazon RESTful API Integration**: I plan on incorporating Amazon's API to allow users to search for gifts, view recommended items, and access direct purchase links for each item.