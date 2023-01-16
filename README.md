## HW_1 : Git

1. На локальном репозитории сделать ветки для:

- Checklists - `git branch CheckLists`;
- Bag Reports - `git branch BagReports`;
- SQL - `git branch SQL`;
- Charles - `git branch Cahrles`;
- Mobile testing - `git branch MobileTesting`;

2. Запушить все ветки на внешний репозиторий - `git push -u origin ChekLists BagReports SQL Charles MobileTesting`;

3. В ветке BagReports сделать текстовый документ со структурой баг репорта - `git checkout BagReports / touch bag_report.txt`;

4. Запушить структуру багрепорта на внешний репозиторий - `git add . && git commit -m "new file bag_report.txt" && git push`;

5. Вмержить ветку Bag Reports в Main - `git checkout main / git merge BagReports`;

6. Запушить main на внешний репозиторий - `git add . && git commit -m "new file bag_report.txt" && git push`;

7. В ветке CheckLists набросать структуру чек листа - `git checkout CheckLists / touch checklist.txt`;

8. Запушить структуру на внешний репозиторий - `git add . && git commit -m "new file checklist.txt" && git push`;

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main;

10. Синхронизировать Внешнюю и Локальную ветки Main - `git checkout main / git pull`.
