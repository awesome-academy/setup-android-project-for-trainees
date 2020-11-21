# Setup CI tutorial for Trainee

**Setup Sun*CI**
Create file .sun-ci.yml with [template](https://github.com/huytq-0932/template-ci/blob/main/.sun-ci.yml) to your project root

**Edit environment**
- Replace info chatwork box's id in ROOM_ID by your box's id
- Replace info chatwork accounts in MEMBERS by your team's chatwork accounts
```
 environment:
      # This is Android review pull request box 
      ROOM_ID: "123456789"
      # Insert the chatwork accounts which you want to mention when the pull request was verified
      MEMBERS: "[To:1234567] Tran Quang Huy"
```
**Review**
- Add changes and push them to your repository
- Notify Trainer review 
