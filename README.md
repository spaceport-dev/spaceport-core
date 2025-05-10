> [!IMPORTANT]
> 
> This repository is a placeholder for the Spaceport Core—currently only distributed as a pre-built JAR—for issue tracking and project management. See notes below about the path to open source and current licensing.

<br/><img src=https://spaceport.com.co/assets/spaceport-logo.svg width=125><br/>

**Spaceport** is a comprehensive full-stack web application framework engineered to make building applications dynamic, fast, and scalable. Designed for rapid iteration, it features an opinionated yet flexible technology stack built upon mature and powerful components. Spaceport uniquely enhances server-client interaction with built-in capabilities like server actions, server reactivity, and server elements directly embeddable within your HTML. These features seamlessly integrate with robust backend systems developed using powerful Groovy modules, offering a cohesive development experience.


### A dynamic stack

Spaceport is built on a robust foundation of open-source components— Groovy, Jetty, and CouchDB, ensuring long-term support and transparency for your operations.

Groovy enables rapid application development and iteration through its dynamic nature and seamless integration and full interop with the mature Java ecosystem.

As a high-performance web server platform, Jetty enables Spaceport's secure and accessible HTTP and WebSocket communications, crucial for delivering robust web applications.

CouchDB offers a flexible and scalable NoSQL database with built-in replication for reliable data backup and secure storage of evolving data structures, earning it the tagline — relax.

On the front end, Spaceport embraces the universal standards of HTML, CSS, and JavaScript. Designed to work seamlessly with these core web technologies in their vanilla form, Spaceport provides intuitive mechanisms to extend their capabilities and directly connect your front-end interactions to its powerful backend.


### 2.0.X Pre-release

After nearly a decade of internal use powering numerous closed-source products, Spaceport is preparing for its open-source debut. While some features are still under development, Spaceport already offers a robust set of mature core functionalities ready for immediate use. Current efforts are heavily focused on comprehensive testing, code refinement, and thorough documentation in anticipation of the fully open-source Spaceport 2.1 stable release. In the interim, Spaceport remains closed-source but is freely available for both personal and commercial applications. For specific licensing needs, please contact info@spaceport.com.co.


### Getting Started

Spaceport currently offers two Starter Kits to get your application off the ground.


#### Port-Echo Starter Kit
> [Port Echo](https://github.com/spaceport-dev/port-echo) offers a basic scaffold and minimal boilerplate to get your application up and going without any additional assumptions. 


#### Port-Mercury Starter Kit
> [Port Mercury](https://github.com/spaceport-dev/port-mercury) is a Spaceport starter kit that provides a basic app structure and configuration for building a single-tenant Spaceport application with some key Spaceport features. If you are just getting started with Spaceport, consider using this Starter Kit.


### Other Pre-requisites
- Java 8 or higher (Amazon Corretto 11 or Azul Zulu 11 recommended)
- CouchDB 2.0 or higher (3.5.X Recommended)


### Startup
To start Spaceport, run the following command:

```bash
java -jar spaceport.jar --start config.spaceport
```

This will start the application using the configuration file `config.spaceport`. You can also use the `--no-manifest` argument to assume a default configuration. 


### Get Spaceport

Don't have Spaceport yet? You can download it from the [Spaceport website](https://spaceport.com.co/builds/). Or, use
the following command to grab the latest version:

```bash 
curl -L https://spaceport.com.co/builds/spaceport-latest.jar -o spaceport.jar
```

### Learn more
For more information about Spaceport, visit the [Spaceport documentation](https://spaceport.com.co/docs).

As documentation is built out, feel free to join us on our [Discord Channel](https://discord.gg/rbdU6AD3a9) for questions not covered. 
