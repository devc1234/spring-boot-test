Project Type: Maven

Choose dependencies:  Spring Data JPA, H2 database, Lombok, Spring Boot Dev Tools

@Data: This annotation is from the Lombok library and is used to automatically generate getters and setters for all fields in the class, as well as implementations of toString(), equals(), and hashCode(). This reduces the amount of boilerplate code that needs to be written.

@AllArgsConstructor: This annotation is also from Lombok and generates a constructor that takes all of the fields in the class as arguments.

@NoArgsConstructor: This annotation is also from Lombok and generates a no-argument constructor.

@Builder: This annotation is also from Lombok and generates a builder pattern for the class, which provides a convenient way to create instances of the class with default or optional values for some fields.

@Entity: This annotation is from the Java Persistence API (JPA) and marks the class as an entity that can be persisted to a database.

@Table(name = "employees"): This annotation specifies the name of the table that corresponds to this entity in the database.
4. Create Spring Data JPA Repository
The next thing we’re gonna do is create a repository to access a User’s data from the database.

The JpaRepository interface defines methods for all the CRUD operations on the entity, and a default implementation of the JpaRepository called SimpleJpaRepository.

![project - spring-boot-test_src_test_java_com_example_demo_EmployeeRepositoryTests java - Eclipse IDE 7_1_2024 3_53_55 PM](https://github.com/devc1234/spring-boot-test/assets/155445639/c1c4ead9-7ba3-4c57-b87d-c55e685f846e)
