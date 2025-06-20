---
title: "Memory Game"
excerpt: "An Android memory game developed in Android Studio using Java and XML, featuring user preferences management and dynamic level selection. [*repo*](https://github.com/acortez1003/MemoryGame)<br/><img src='/images/home.PNG' style='display: block; margin: auto;'>"
collection: portfolio
---

This application was the final project of my Mobile Programming course. This was a group project where my role was to implement user preferences management and designing level selection and navigation layouts. [*repo*](https://github.com/acortez1003/MemoryGame)

## UI & Navigation

<div style="text-align: center;">
    <img src="/images/home.PNG" alt="Home">
</div>

I designed the level templates in XML, ensuring a consistent layout and correct screen transitions. Each level button was configured to navigate to the appropriate game screen by using `onClickListener()`.

## User Preferences

I implemented `SharedPreferences` to persist user settings. This included **color themes, dark/light mode, and level completion tracking**. Even if the device was shut off or rebooted, these settings would persist.

![Gameplay](/images/gameplay.png)

Above is gameplay. This shows Medium Level 1 being played. After completion, the user is taken back to the level selection screen and that level is now turned Green. This was done by overriding the `OnResume()` method, which ensures that the UI updates dynamically to reflect the new level status. 

![Color change](/images/color_change.png)

In the `Settings` view, we can change the button color, which is persistent data. This was done through overriding the `onCreatePreferences()` method.

![Reset](/images/reset.png)

If the user wanted to restart their progress, they can hit the `Reset` button and the levels will reset as their color as well as the other saved preferences that were changed in the settings. This is done through calling `SharedPreferences.Editor.clear()`.

![Light mode](/images/light_mode.PNG)

Changing dark/light mode is also an option of persistent data in the settings.