# shaype

A reference to shape API endpoints and their response objects

`base_url: https://shape.io/steadyApi/v1/`

## Clients

append: `/UserService/ClientsBudgets`

resp: 

* `"Clients":`
  * `id_client`
  * `name_client`
  * `date_added`
  * `currency`
* `"Budgets":`
  * `id_client`
  * `id_budget`
  * `name_budget`
  * `start_date`
  * `amount_budget`
  * `spend_to_date`
  * `checked_budget`
  * `checked_by_queue`
* `"BudgetMetrics":`
