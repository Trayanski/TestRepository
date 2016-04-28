# TestRepository
28.04.2016 This repository is a part of the "Java Course".

Repositories: Задачи

1. Да се създаде проект с GIT #
2. Да се направят промени и да се commit-нат #
3. Да се създаде нов branch. Да се направят промени в него и след това branch-a да се слее (merge) с master'a #
4. Да се направи rebase и merge с конфликти, които да се ресолвнат и да се определят разликите между 2'та подхода

 

5. Да се създаде tag #
6. Да се изследва и установи каква е разликата между rebase и merge #

Merging is nice because it’s a non-destructive operation. 
The existing branches are not changed in any way. 
This avoids all of the potential pitfalls of rebasing.
Merging can make it hard for other developers to understand the history of the project.

The major benefit of rebasing is that you get a much cleaner project history.
Rebasing also results in a perfectly linear project history—you can follow the project all the way to the beginning without any forks.
Rebasing makes it easier to navigate your project with commands like git log, git bisect, and gitk.
If you don’t follow the "Golden Rule of Rebasing", re-writing project history can be potentially catastrophic for your collaboration workflow.
Rebasing loses the context provided by a merge commit—you can’t see when upstream changes were incorporated into the newBranch.

7. Да се check out-не проекта на друго място #
8. Да се определят разликите между централизирана и дистрибутирана система за управление на кода
9. Да се разгледат инструментите на GitHub за комуникация между разработчици (pull requests,issues, branches,tags, merging).
