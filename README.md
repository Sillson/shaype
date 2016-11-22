# shaype

A reference to shape API endpoints and their response objects

`base_url: https://shape.io/steadyApi/v1/`

## ClientsBudgets
append: `/UserService/ClientsBudgets`

resp: 

### Clients
* `"Clients":`
  * `id_client`
  * `name_client`
  * `date_added`
  * `currency`

### Budgets
* `"Budgets":`
  * `id_client`
  * `id_budget`
  * `name_budget`
  * `start_date` (not a date)
  * `amount_budget`
  * `spend_to_date`
  * `checked_budget` (yyy-mm-dd)
  * `checked_by_queue` (yyy-mm-dd)
  * `auto_pilot`
  * `cycle_months`
  * `cycle_days`
  * `cycle_repeats`
  * `init_start_date`
  * `current_start_date` (yyymmdd)
  * `current_end_date` (yyymmdd)
  * `cycle_active`
  * `timezone`
  * `rollover`
  * `rollover_rogue`
  * `rollover_active`
  * `auto_add_campaigns`
  
### BudgetMetrics
* `"BudgetMetrics":`
  * `"11027":`
    * `id_company`
    * `id_client`
    * `id_budget`
    * `spend_to_date`
    * `clicks`
    * `conversions`
    * `impressions`
    * `trend`
    * `start_date`
    * `end_date`
    * `number_campaigns`
    * `active_campaigns`
    * `paused_campagins`
    
## BudgetCampaignMetrics
append: `/ClientService/BudgetCampaignsMetrics?id_client=`

resp: 

### BudgetCampaigns
* `"BudgetCampaigns":`
  * `id_client`
  * `id_budget`
  * `id_campaign`
  * `name_campaign`
  * `autopilot`
  * `userChanged`
  * `type`

### BudgetCampaignMetrics
* `"BudgetCampaignMetrics":`
  * `id_client`
  * `id_budget`
  * `id_campaign`
  * `spend`
  * `clicks`
  * `impressions`
  * `conversions`
  * `status`
  * `daily_budget`
  * `search_rank_LIS`
  * `seach_budget_LIS`
  * `type_campaign`
  * `start_date` (yyymmdd)
  * `end_date` (yyymmdd)

 
