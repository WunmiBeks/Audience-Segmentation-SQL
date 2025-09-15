# REQUIREMENT NOTES 

- Assuming that 7 day window is to ensure in the scenario if automation is paused or failed, the next run can pick up those records.
- Assuming no other Welcome journeys have been set up - so no need to exclude members who have already received (note that on first run - large batch of customers who joined within the last 7 days will be selected)
- Assuming that members who have downloaded the app exists in the Customer_AppData data extension
- Any fields required for dynamic content/personalization for the email build 