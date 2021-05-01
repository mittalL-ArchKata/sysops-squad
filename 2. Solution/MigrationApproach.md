* Downtime is OK, so we can:
  * take the current system down,
  * do the data migration (shouldn't be big -- clarify??? how many tickets there already?)
  * Run QA UI to ensure the new system works (need all the key test cases ready)
  * Bring the new system live
  
  
----
Existing to new Components Mapping

| # | Existing Systems's Component | New System's Component | Action |
|----|----|----|----|
|1. | Login | Login Service | Rename of the service | 
|2. | Billing Payment | Billing Service | Merged into new service | 
|3. | Billing History | Billing Service | Merged into new service | 
|4. | Customer Notification | Notification Service | New Service for all notifications | 
|5. | Ticket Notify | Notification Service | New Service for all notifications |
|6. | Survey Notify | Notification Service | New Service for all notifications |
|7. | Customer Profile | Customer Service | Merged into new service |
|8. | Support Contract | Customer Service | Merged into new service | 
|9. | Expert Profile | Expert Service | Rename of the service | 
|10. | KB Maintenance | KB Service | Merged into new service | 
|11. | KB Search | KB Service | Merged into new service | 
|12. | Reporting | Reporting Service | Rename of the service | 
|13. | Ticket Shared | Ticket Service | Merged into new service | 
|14. | Ticket Assign | Ticket Service | Changed ticketing business process -> ADR.003| 
|15. | Ticket Route | Filter Service | Redesign functionality | 
|16. | Survey | Survey Service | Merged into new service | 
|17. | Survey Template | Survey Service | Merged into new service |
|18. | User Maintenance | User Service | Rename of the service |
  