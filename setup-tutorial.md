# Setup CI tutorial for Trainee

### Setup Sun*CI
Create file .sun-ci.yml with [template](https://github.com/huytq-0932/template-ci/blob/main/.sun-ci.yml) to your project root
### Setup CircleCI
- Create file config.yml with [template](https://github.com/huytq-0932/template-ci/blob/main/.circleci/config.yml) to your project root under a .circleci folder 
### Edit environment
- Replace info chatwork box's id in ROOM_ID by your box's id
- Replace info chatwork accounts in MEMBERS by your team's chatwork accounts
```
 environment:
    JVM_OPTS: -Xmx3200m
      # This is Android review pull request box 
      ROOM_ID: "123456789"
      # Insert the chatwork accounts which you want to mention when the pull request was verified
      MEMBERS: "[To:1234567] Tran Quang Huy"
```
### Review
- Create pull request for the changes
- Send pull request to Trainer for reviewing
