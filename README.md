# distributed-logging

## Description

Repository dedicated for a logging library dedicated to distributed systems
It features a central server, that collects messages from its own codebase (local loggers) and from remote machines (remote loggers) across the network.
System also monitors the real-time resource consumption of the server and all connected remote machines to enable the correlation of occurred events, failures, and resource load.

Communication between the server and remote machines is powered by the accompanying library, [tcp-cliet-server](https://github.com/JakubMiodunka/tcp-client-server "Link to tcp-client-server repository"), also developed by the author.
Utilizing *tcp-cliet-server* here serves as a practical trial to gather feedback, which will directly inform and drive future updates and improvements to this communication library.

Project is realized primarily for educational purposes to gain knowledge in following fields:

* understanding of how logging frameworks operate under the hood as all functionalities of the system will be developed from scratch without third-party solutions
* asynchronous programming
* reliable data transfer over a network
* fault tolerance strategies for failure-state actions

Keep in mind, that project is still under active development, and not all planned features have been implemented.

## Repository Structure

* */doc* - Contains project documentation.

* */doc/html* - contains the HTML-based code documentation, automatically generated using [DoxyGen](https://www.doxygen.nl/ "DoxyGen website"). View the content by opening *index.html* in Your browser of choice.

* */src* - Contains project source code.

## Source Code Structure

* */src/UnitTests* - Source code of unit tests.

* */src/IntegrationTests* - Source code of integration tests.

## Project versioning

Versioning for this project follows the established guidelines of [semantic versioning](https://en.m.wikipedia.org/wiki/Software_versioning#Semantic_versioning "Wikipedia article").

Current version: 0.0.1

## Project management

Project development is tracked and managed using GitHub project available under following link: [distributed-logging](https://github.com/users/JakubMiodunka/projects/5 "Link to distributed-logging project").
If You spotted some bug or have a suggestion feel free to create corresponding issue there.

## Used Tools

* IDE: [Visual Studio 2022](https://visualstudio.microsoft.com/vs/ "Visual Studio website")
* Documentation generator: [DoxyGen 1.12.0](https://www.doxygen.nl/ "DoxyGen website")

## Authors

* Jakub Miodunka
  * [GitHub](https://github.com/JakubMiodunka "GitHub profile")
  * [LinkedIn](https://www.linkedin.com/in/jakubmiodunka/ "LinkedIn profile")

## License

This project is licensed under the MIT License - see the [*LICENSE.md*](./LICENSE "Licence") file for details.
