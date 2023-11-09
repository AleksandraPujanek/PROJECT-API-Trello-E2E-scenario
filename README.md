# :file_folder: PROJECT: API Trello - E2E scenario
Verification of REST API in Trello / E2E scenario:
- create three boards,
- add stars to two of them,
- create two lists "To do" and "Done" for one of the board,
- create a card for "To do" list,
- add a member and a due date to the created card,
- move the card from "To do" list to "Done" list,
- archive the card,
- delete the card.

**Summary:** [Trello - Test Report]()

**Tools:**
- Postman x86_64 10.19.7,
- Newman 6.0.0,
- Newman Reporter htmlextra 1.22.11.

**Environment:** Trello production [https://trello.com/](https://trello.com/)

**Postman Environment:** [TRELLO Prod.postman_environment.json]()

**Documentation:** [REST API Trello - documentation](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-post)

**Endpoint:** https://api.trello.com/1/

## Collection - P.5. Trello E2E scenario.postman_collection.json

**Postman Collections:**
- [P.5. Trello E2E scenario.postman_collection.json]()

**Reports:**
- [P.1.Trello - board name tests - QueryParams - positive_report.html]()

