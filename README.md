# QuickAdd-for-Todoist
Effortlessly add tasks to your Todoist Inbox using just your voice with Alexa!

This skill utilizes Todoist’s natural language processing to allow you to add tasks effortlessly. Simply say, 'Alexa, tell QuickAdd to add [task],' and it will default to today's date in your Inbox. For tasks needing a specific due date, just include it after the task name.

Manage your to-do list hands-free while focusing on your productivity, not your planning. Just say the task and, optionally, when it’s due, and Alexa handles the rest. Perfect for busy individuals who need to organize their tasks quickly and efficiently!

Get started by saying, "Alexa, tell QuickAdd to add..."

Note: You may use both "Alexa, tell QuickAdd" and "Alexa, ask QuickAdd." This invocation format is different than the native Todoist integration was and is specified by Amazon to ensure smooth operation with Alexa. You might need a few tries to get used to this new way of adding tasks, but once you do, it’ll become second nature!

Pro Tip: For the shortest and easiest invocation say "Alexa, tell QuickAdd add [task]."

Disclaimer: Linking your Todoist account and purchasing the skill are required for operation. Account linking needs to happen in the browser and not in the native Todoist app. Some Android devices may automatically attempt to open the native Todoist app for account linking. If this occurs, please complete the linking process directly from a web browser instead, or copy the URL from the app and paste it into your browser's address bar.

This skill is independently created and is not affiliated with or endorsed by Doist.

If you are enjoying QuickAdd, please consider:

Reviewing it on Amazon - https://www.amazon.com/dp/B0D7948ZX5 

Or contributing to future enhancements - https://buymeacoffee.com/erikjohnrichter


# How to use QuickAdd for Todoist

For a full, updated list of features and instructions, please visit - https://www.erikrichter.com/project/quickadd-for-todoist-alexa-skill

**1) Invocations** - All invocations of QuickAdd need to start with "Alexa, [tell/ask] Quick Add to add..." You may say:

- "Alexa, tell QuickAdd to add [task]" - Adds [task] with a default due date of "today" to your Todoist Inbox.
- "Alexa, tell QuickAdd to add [task] no date" - Adds [task] with no due date to your Todoist Inbox.
- "Alexa, tell QuickAdd to add [task] [day of the week - OR - month/date]" - QuickAdd supports Todoist's natural language dates. This invocation overrides the default "today" due date when adding a [task] to your Todoist Inbox or Project.
- "Alexa, tell QuickAdd to add [task] to my [Todoist project name]" - Adds [task] with a default "today" due date to your custom Todoist Project. NOTE: The project name MUST contain no spaces (see below).

Any of these endpoint commands may be combined or added to in your invocation requests.

**2) Labels** - All tasks added to Todoist using the QuickAdd skill will have the @Alexa label attached to it. This mimics the same workflow from the old official integration.

**3) Due Dates** - All tasks added to Todoist using the QuickAdd skill will have a default "today" due date, unless otherwise specified (see invocation examples above).

**4) Custom Projects** - All tasks added to Todoist using the QuickAdd skill will default to adding the [task] to a user's Todoist Inbox unless a specific project is mentioned (see invocation example above). NOTE: Any custom [project] name you use MUST contain NO spaces for QuickAdd to add a [task] to that custom [project]. Example: If you have an existing project in Todoist named "Grocery List," you must edit that project's name in Todoist to remove the space to "GroceryList"...and then invoke the custom project by saying "Alexa, tell QuickAdd to add apples to my Grocery List," for instance.
