<details>
<summary>Homework 1 condition✅</summary>
# Git-branch-hw
  
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
  
$git branch Postman  
$git branch Jmeter  
$git branch Checklists  
$git branch Bug_reports  
$git branch SQL  
$git branch Charles  
$git branch Mobile_testing  
  
2. Запушить все ветки на внешний репозиторий  
$git push -u origin Postman Jmeter Check_lists Bug_reports SQL Charles Mobile_testing  
  
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта  
$git branch  
$git checkout Bug_reports  
$cat > bug_report_structure.txt  
$vim bug_report_structure.txt  
  
4. Запушить структуру багрепорта на внешний репозиторий  
$git add .  
$git commit -m "BR structure"  
$git status  
$git push  
5. Вмержить ветку Bag Reports в Main  
$git branch  
$git checkout main  
$git merge Bug_reports  

6. Запушить main на внешний репозиторий.  
$git status  
$git add bug_report_structure.txt  
$git commit -m "copy BR str"  
$git push  
7. В ветке CheckLists набросать структуру чек листа.  
$git checkout Check_lists  
$cat > Check_list_structure.txt  
$vim Check_list_structure.txt  
  
8. Запушить структуру на внешний репозиторий  
$git add .  
$git commit -m "CL str"  
$git push  
  
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  
10. Синхронизировать Внешнюю и Локальную ветки Main  
$git fetch  
$git checkout main  
$git pull  
  
</details>
