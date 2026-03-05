#  Production-worthy Spring AI

In which Josh Long and Adib Saikali look at the amazing power of a production-worthy platform-as-a-service when married with the bombastic Spring AI framework.

## who 

[Adib Saikali](https://linkedin/in/adibsaikali) | [Josh Long](https://linkedin/in/joshlong)

Here is the [code](https://github.com/joshlong-attic/2026-02-18-bootiful-cloud-native-agentic-spring-boot-4/).

Spring AI carries forward the concepts of the 'spring triangle':

 * dependency injection
 * portable service abstractions
 * aspect oriented programming (aop)

## what

1. start the `auth` module first.
2. then start the `scheduler`
3. then start the `assistant` service

In your browser, go to this [url](http://localhost:8080/ask?question=fantastic.%20when%20can%20i%20pick%20up%20or%20adopt%20a%20dog%20from%20the%20London%20Pooch%20Palace%20location%3F&continue).

On my cloudfoundry instance, [inquire about neurotic dogs](https://adoptions-assistant.apps.tas-ndc.kuhn-labs.com/ask?question=do%20you%20have%20any%20neurotic%20dogs%3F), and then [inquire about scheduling](https://adoptions-assistant.apps.tas-ndc.kuhn-labs.com/ask?question=when%20can%20i%20pick%20up%20or%20adopt%20Daisy%20from%20the%20San%20Francisco%20Pooch%20Palace%20location%3F).
