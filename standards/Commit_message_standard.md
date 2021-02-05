## Commit Message Standard



Well-crafted Git commit message is the best way to communicate about a change to fellow developers (and indeed to their future selves).

A diff will tell you *what* changed, but only the commit message can properly tell you *why*



Try to reduce commit message as small as you can but don't write too small commit message which is incomplete.



A commit message shortly describes the change is made in that commit.



Follow those standards of commit message

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to write description



### Examples

#### Separate subject from body with a blank line

```diff
-Use task scheduler to handle jobs

+Use task scheduler to handle jobs
+
+We are using too much cron commands to execute custom command.
+It will be more elegant if we use task scheduler.
```



#### Limit the subject line to 50 characters

```diff
-This is a too long commit message that is so bad. Try to use short message as commit message
+What this commit will do
```



#### Capitalize the subject line

```diff
-uncapitilized subject line
+Capitilized subject line
```



#### Do not end the subject line with a period

```diff
-Subject line ended with a period.
+Subject line ended without period
```



#### Use the imperative mood in the subject line

```diff
-Updated UI design of home page
+Update UI design of home page
```

**TIP : **A properly formed Git commit subject line should always be able to complete the following sentence:

If applied, this commit will *<u>your subject line here</u>*



#### Wrap the body at 72 characters

Git never wraps text automatically. When you write the body of a commit message, you must mind its right margin, and wrap text manually.

The recommendation is to do this at 72 characters, so that Git has plenty of room to indent text while still keeping everything under 80 characters overall.

```diff
-The recommendation is to do this at 72 characters, so that Git has plenty of room to indent text while still keeping everything under 80 characters overall
+The recommendation is to do this at 72 characters,
+so that Git has plenty of room to indent text while still keeping 
+everything under 80 characters overall
```



#### Use the body to write description

```DIFF
-Descriptino in subject line

+Short message
+
+Description goes here
```



