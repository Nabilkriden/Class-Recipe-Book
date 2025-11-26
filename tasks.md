Activity 1 — Create a branch with your name


git checkout -b firstname-branch


Activity 2 — Add your own recipe
Create:  recipes/<your-name>-recipe.md



Example:
# My Recipe: Chocolate Milkshake
Ingredients: milk, cocoa, sugar
Steps: mix everything

Commit and push.


Activity 3 — EVERY STUDENT EDITS THE SAME LINE

Open:

ingredients/common.txt

Every student changes the line to their favorite ingredient:

banana

chicken

pasta

cheese

salt

chocolate

This guarantees merge conflicts.


Activity 4 — Create Pull Requests

Each student opens a pull request:

Title: "Added my recipe + updated ingredient"

Ask a classmate for review


Activity 5 — Merge Conflicts Appear

Students fix the conflicts, example:

Git shows:
<<<<<<< HEAD
favorite_ingredient = pasta
=======
favorite_ingredient = cheese
>>>>>>> student-branch


Students choose which version to keep, or combine:
favorite_ingredient = pasta & cheese


End Result

Students will have practiced:

✔ Git basics
✔ Branching
✔ Merging
✔ Merge conflicts
✔ Code reviews
✔ Pull requests
✔ Working on the same project
✔ A real collaborative workflow

But with simple, fun, easy examples.