## GIT Homework 1

## JSON
#### 4. Create external repository named JSON 
Web Git Hub => "Repositories" Tab => [New] Button => Repository Name "JSON" => Click "Add a REDMI file" => [Create repository"] Button
#### 5. Clone JSON repository to local computer
git clone "https://github.com/DariaMartinovskaya/JSON.git"
#### 6. Create file “new.json” inside JSON repository
touch new.json
#### 7. Add the file to git
git add new.json
#### 8. Commit the file
git commit -m new.json
#### 9. Send the file to external GitHub repository
git push
#### 10. Edit content of “new.json” file - add the information about yourself (Full name, age, amount of pets, future desired salary). To be written in JSON format
vim new.json => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter" 
#### 11. Send changes to external repository
git commit -am + git push
#### 12. Create preferences.json file
touch preferences.json
#### 13. Add information about your preferences (favorite film, favorite series, favorite food, favorite season, country you would like to visit) into preferences.json file in JSON format
vim preferences.json => i (edit mode) => {Input data} => "esc" + ":wq" + "Enter"
#### 14. Create sklls.json file and add information about skills to be learnt during the course in JSON format
touch skills.json + vim skills.json => i (edit mode) => [Input data] => "esc" + ":wq" + "Enter"
#### 15. Send 2 files to external repository at the same time
git add . && git commit -m "2Files" + git push
#### 16. Create bug_report.json file on external repository
Web Git Hub => Repositories => "JSON" => Click [Add file] Button => Choose "Create new file" => Name of the file: "bug_report.json" 
#### 17. Commit changes (save) on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 18. Modify bug_report.json file on the web interface, add a bug report in JSON format
Choose bug_report.json => Edit this file button 
#### 19. Commit changes (save) changes on the web interface
[Commit changes...] Button => [Commit changes] Button
#### 20. Synchronize external and local JSON repositories 
git pull
