# GitHub. HW_2
## 1. On the local repository, create branches for:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
 
` git branch Postman `

` git branch Jmeter`

` git branch CheckLists `  

` git branch Bag_Reports`

` git branch SQL `

` git branch Charles`

` git branch Mobile_testing`

## 2. Push all branches to remote repository:

 ` git remote -v  `
 ### then
 ` git push -u origin --all`

## 3. In the Bag Reports branch, create a text document with the bug report structure:

` cat>bag_report.txt`

 with text 

 `Bug Summary 

Steps to reproduce

Actual Result

Expected Result 

Severity

Priority

Attach`

## 4. Push the bug report structure to remote repository:
`git add .` 

`git commit -m "add file bag_report" `

`git push `

## 5. Merge Bug_Reports branch to main:
` git merge Bag_Reports `

Resalt:

` Fast-forward `

` Fast-forward`

 `bag_report.txt | 8 ++++++++` `

 `1 file changed, 8 insertions(+)`

 `create mode 100644 bag_report.txt `


## 6. Push main branch to remote repository:

` git push -u origin main`

## 7. In Checklists branch create file .txt with checklist structure:

` ~/Git/Git_branches `

`cat>check_list.txt`

## 8. Push the file to remote repository:

`git add .` 

`git commit -m "add file check_list" `

`git push `

## 9.  On the remote repository make Pull request from Checklists branch to main.

## 10. Sinchronize remote main branch and local main branch:

` git pull `



