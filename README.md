# F# Zip & email functionality

This project rises from an idea that no solution has been found to encrypt pdf reports when email using SSRS subscriptions

The following solution proposed:

1. Create Data-driven SSRS report and choose Windows Shared Folders as destination
2. Setup windows task to schedule run this application, which will encrypt and email pdf reports, produced by SSRS

