# 1. Setup Pull Request Title Checker Tool for Trainee Tutorial
- Create file .github/workflows/pull_request_title_conventions.yml 
- Copy content of [file](https://github.com/huytq-2422/setup-ci-tutorial/blob/main/.github/workflows/pull_request_title_conventions.yml) into recent created file.

# 2. Setup CI tutorial for Trainee

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
# 3. Review
- Add changes and push them to your repository
- Notify Trainer review  
