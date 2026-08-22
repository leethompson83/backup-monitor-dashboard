Backup Systems
(Veeam, Rubrik, Commvault, Cohesity, Azure Backup, etc.)
            |
            v
     Shared Mailbox
 backupalerts@company.com
            |
            v
    Power Automate Flow
    - Monitor mailbox
    - Parse email
    - Classify severity
    - Create Dataverse record
    - Send notifications
            |
            v
        Dataverse
    Alert Repository
    Incident Tracking
    Assignment Status
            |
      ----------------
      |              |
      v              v
  Power Apps      Power BI
  Alert Mgmt      Executive &
  Remediation     Operations Dashboard
