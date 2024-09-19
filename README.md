# Expense-Tracker-CLI

This is my solution of a project in Roadmap site, [project here](https://roadmap.sh/projects/expense-tracker)

# Usage
Get the files then install dependencies, then run
```
npm install -g .
```
then you can use the commans in terminal.

The list of commands and their expected output is shown below:
```
$ expense-tracker add --description "Lunch" --amount 20
# Expense added successfully (ID: 1)

$ expense-tracker add --description "Dinner" --amount 10
# Expense added successfully (ID: 2)

$ expense-tracker list
# ID  Date       Description  Amount
# 1   2024-08-06  Lunch        $20
# 2   2024-08-06  Dinner       $10

$ expense-tracker summary
# Total expenses: $30

$ expense-tracker delete --id 1
# Expense deleted successfully

$ expense-tracker summary
# Total expenses: $20

$ expense-tracker summary --month 8
# Total expenses for August: $20
```
