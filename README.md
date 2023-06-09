# WeatherApp

This project was followed from the following Angular tutorial on YouTube:
https://www.youtube.com/watch?v=psZXU8PTAS8

Project is generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.3.

## Key Takeaways

1. In Angular, the HttpClientModule is a service module provided to perform HTTP requests. A service module only instantiates services and does not export any components, directives and pipes. (Add this import { HttpClientModule } from '@angular/common/http' into app.module.ts)

2. It is best to access HttpClient via a service. Run `ng g s services/serviceName` to create a new service. Inject the HttpClient into the service constructor.

3. To fetch data from server, create a method that can be called in components. Inject this service into the component that requires the data. The HTTP GET method returns an observable that components can subscribe to.
