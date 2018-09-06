# storyboard-repeatbehavior
A simple repro demonstrating how storyboard.repeatbehavior seems to be broken in the latest Windows 10 build (17744.rs5_release.180818-1845)

To reproduce, just clone this repo and run the solution.

Expected behavior (as seen on previous Windows builds): The square will flash due to the storyboard repeating infinitely
Actual behavior: The square flashes once and the animation stops
