# <Subject> 
# Summarize changes in around 50 chars or less in one line.  
# Capitalize the subject line and don't end it with a period
# Imperative mood. e.g. Fix a log-in crash bug 
#|===============================================|

# <Body> 
# The detail explanation of the change, if necessary
# Separate with a blank line between paragraphs
# Wrap the body at 72 characters
#|=====================================================================|

# <IntegrationTags>
# If the change fixes an JIRA issue, put a line of [FIX <JIRA ticket id>] <a brief description>
# e.g. [FIX WHOS-229] Fix DB verification crash
#
# If the change completes a task noted as a Trello card, put a line of [Do #<Trello card id>] 
# e.g. [Do #tf7qMz1Q] Implement auto-update feature
#
# Keep each single line 72 chars or less
#|=====================================================================|

# <Changelogs>
# If you have anything need to reflect to Change log, put lines in following format:
# [Add | Update | Modify | Change | Edit | Create | Delete | Remove] <a brief description>
# For instance: [Add] A new feature

# <Skip CI>
# Uncomment the following line if you want CI to skip this change
# [ci skip]
