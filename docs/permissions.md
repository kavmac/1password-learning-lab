# Permissions
Let's see how far I can push access without annoying myself.

## What I want to look at

### vault-level permissions
Basic stuff:
- read
- write
- manage
- whatever “limited” actually means

### item-level behavior
Curious about:
- who can edit items
- who can move items
- who can delete things
- whether anything gets silently blocked

### admin-level permissions
Things that control the org:
- manage groups
- manage vaults
- manage policies
- manage users

## What I want to test
- how permissions behave if someone’s in multiple groups  
- whether vault permissions override group permissions or the other way around  
- what happens when access changes mid-session  
- how untrusted devices behave when permissions get stricter  
