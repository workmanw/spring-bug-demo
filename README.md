# Spring Boot Issue 25759

https://github.com/spring-projects/spring-boot/issues/25759

See the issue for complete details ^^

## Reproduction

1. Clone the repo and run the `DemoApplicationTests`.
2. Notice that an exception is generated on application startup.
3. Change the pom to use Spring Boot `2.3.9.RELEASE`.
4. Run `DemoApplicationTests` again.
5. Notice that the test runs and that logging out put contains `[[Demo Config]] --`.

At this point we have demonstrated prior behavior with `2.3.9.RELEASE` (configuration working w/ `spring.profiles.include`) AND regression with `2.4.2`.