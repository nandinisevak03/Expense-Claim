### ExpenseManager

The ExpenseManager app helps companies manage employee expenses easily. It allows employees to submit expense claims for items like travel, meals, and other work-related costs. Each expense claim includes details like the employee's name, the type of expense, the date, and the amount spent.

A built-in approval process lets managers review and decide on each claim. When an employee submits a claim, it goes to "Submitted" status. The manager can then mark it as "Under Review" and either approve or reject it, updating the status accordingly. Permissions are role-based: only employees can submit claims, and only managers can approve or reject them. This app simplifies the expense reporting and approval process, making it easy for both employees and managers.








### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app expensemanager
```



### CI

This app can use GitHub Actions for CI. The following workflows are configured:

- CI: Installs this app and runs unit tests on every push to `develop` branch.
- Linters: Runs [Frappe Semgrep Rules](https://github.com/frappe/semgrep-rules) and [pip-audit](https://pypi.org/project/pip-audit/) on every pull request.


### License

mit
