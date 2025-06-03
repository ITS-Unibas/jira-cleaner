# jira-cleaner
Automatic removal of unnecessary jira-tickets for WASP. How to run the script?! Great you ask!

First get your python env up to speed:
```Python
> pip install -r requirements.txt
```

After that run the jiraCleanup.py

The jira-cleaner can be run with credentials (username and password) or with a jira-token. Either way the necessary contents have to be inserted in the config.json.

The jira-cleaner lists all items (jira-tickets) that it's going to delete before deletion and ask the user before deletion.

The amount of tickets to keep are listed in the config.json as well. It's default is set to 5.
