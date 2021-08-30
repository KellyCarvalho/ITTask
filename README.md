# ITTask
# Making Integration Tests  Pass

## TDD Challenge to Deliver
TASK: TDD Event-City

Implement the necessary features for the project tests below to pass:
https://github.com/devsuperior/bds02

This is a system of events and cities with an N-1 relationship between them:

![Imagem](https://github.com/KellyCarvalho/ITTask/blob/main/src/main/java/com/devsuperior/bds02/img/Classes.png)




**Minimum for approval: 4/6**


Tests: 

- [x] deleteShouldReturnBadRequestWhenDependentId
- [x] deleteShouldReturnNoContentWhenIndependentId
- [x] deleteShouldReturnNotFoundWhenNonExistingId
- [x] findAllShouldReturnAllResourcesSortedByName
- [x] updateShouldUpdateResourceWhenIdExists
- [x] updateShouldReturnNotFoundWhenIdDoesNotExist
