# CS360-Mobile-Architecture-and-Programming


* **Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**

<u>Per our first project in the course, these were the app requirements:</u>

This application will be used to track items in a warehouse. This application must include the following:

    A database with at least two tables, one to store the inventory items and one to store user logins and passwords
    A screen for logging into the app. Note that this should also be used to create a login if the user has never logged in before.
    A screen, with a grid, that displays all items in the inventory
    A mechanism by which the user can add and remove items from inventory
    A mechanism by which the user can increase or decrease the number of a specific item in the inventory
    A mechanism by which the application will notify the user when the amount of any item in the inventory has been reduced to 0 (zero)

    
* **What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**

These screens were necessary to support the application:
  Login screen
  Main inventory
  Settings
  Add inventory
  Update inventory
    
* **How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?**

While developing this app, I began by creating the UI. From there, I followed an incremental approach beginning with transitioning between screens, then adding an item to the inventory through SQLite, adjusting that item, deleting, logging in or creating an account, and lastly setting up SMS notifications through the settings.
    
* **How did you test to ensure your code was functional? Why is this process important and what did it reveal?**

Each time I added a feature I tested to make sure it was working as intended, and also did some simple regression testing by just making sure the other already added / tested features did not break or become altered. This process is important to any project as failing to test can have immediate impact if functions are not working as intended, and could potentially lead to other issues down the road if new features impacted or changed previously added features. 
    
* **Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?**

One area where I had to overcome a challenge was in implementing RecyclerView in a grid system. While I had a general idea of how RecyclerView worked, I had to look into altering my xml files to get items to appear in a grid, as opposed to a list. After that, it took some time to get SQLite to work with it, as I hadn't previously worked with Android or SQLite.
    
* **In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**

Perhaps the best example of what I learned in this course was in the main inventory screen. This screen has a navigation bar, floating action button, and inventory grid, all of which took some time to design and then code the backend for.
