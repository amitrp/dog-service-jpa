
# dog-service-jpa
This is a Spring Boot RESTful DogService for performing simple CRUD operations on Dog

## This repository is part of https://www.amitph.com tutorials.
> The dogs-service-jpa will be used as a Source Code example for > 
> - **[Spring Data and JPA Tutorial](https://www.amitph.com/spring-data-and-jpa-tutorial/)**
> - **[Wildcard Queries with Spring Data JPA](https://www.amitph.com/spring-data-and-jpa-tutorial/)**

- [DogsRepository.java](src/main/java/com/amitph/spring/dogs/repo/DogsRepository.java): Simple CRUD Repository to perform basic operations on Dog table.
- [DogsRepositoryWildcardWithQuery.java](src/main/java/com/amitph/spring/dogs/repo/DogsRepositoryWildcardWithQuery.java): Example of executing wildcard queries (LIKE, NOT LIKE, Starts With, Ends With) using @Query annotation.
- [DogsRepositoryWildcardWithQueryMethods.java](src/main/java/com/amitph/spring/dogs/repo/DogsRepositoryWildcardWithQueryMethods.java): Example of performing wildcard searches  (LIKE, NOT LIKE, Starts With, and Ends With) using Spring Data JPA Query methods.

_The source code may be incomplete or written within a limited scope of the tutorial, and some essential parts may have been ignored._