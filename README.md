# :file_folder: PROJECT: API Trello - E2E scenario - Postman
Verification of REST API in Trello / E2E scenario using Postman

Project scope:
- find, read and analyse REST API documentation for Trello,
- E2E scenario:
    - create three boards,
    - add stars to two of them,
    - create two lists "To do" and "Done" for one of the board,
    - create a card for "To do" list,
    - add a member and a due date to the created card,
    - move the card from "To do" list to "Done" list,
    - archive the card,
    - delete the card,
- create requests and test scripts in Postman,
- apply good practisies: clean up after testing activities,
- create Postman's collections, environment and test data,
- run Postman collections with environment and data load from Newman,
- create Test Report
  
**Summary:** [Trello - Test Report](https://drive.google.com/file/d/15d9UxWAi-sDo3G0BwWjzmtu9JhtX3BTi/view?usp=drive_link)

**Tools:**
- Postman x86_64 10.19.7,
- Newman 6.0.0,
- Newman Reporter htmlextra 1.22.11.

**Environment:** Trello production [https://trello.com/](https://trello.com/)

**Postman Environment:** [TRELLO Prod.postman_environment.json](https://drive.google.com/file/d/1pHBp8j-vs0dfUFYrQLaAOju6P-sHIQup/view?usp=drive_link)

**Documentation:** [REST API Trello - documentation](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-post)

**Endpoints:** 
- https://api.trello.com/1/boards
- https://api.trello.com/1/members
- https://api.trello.com/1/lists
- https://api.trello.com/1/cards

## Collection - P.5. Trello E2E scenario.postman_collection.json

**Postman Collections:**
- [P.5. Trello E2E scenario.postman_collection.json](https://drive.google.com/file/d/1-u3nVRRlqkmEd7NTcXlvOrVfkNAEzAcA/view?usp=drive_link)

**Reports:**
- [P.5. Trello E2E scenario_report.html](https://drive.google.com/file/d/14_tQBtcKLP10ha_TXVBUhPbGR79yK6XW/view?usp=drive_link)

