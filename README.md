# CS 230: Software Design Document Portfolio

## 1. Summary of The Gaming Room and Its Requirements

The Gaming Room was the client for this project. They wanted to expand their existing Android game, Draw It or Lose It, into a web-based application that could support multiple types of devices. The game allows teams to identify images presented as clues during timed rounds. The application needed to support multiple games, teams, and players while ensuring that game and team names were unique and that each game, team, and player had a unique identifier. My design focused on creating a web-based system that could support users across different platforms.

## 2. What Did I Do Particularly Well in Developing the Documentation?

I believe I did well explaining the client's requirements and connecting them to the proposed software design. I organized the document into sections covering the requirements, design constraints, domain model, platform evaluation, and recommendations. I also explained how the Entity, Game, Team, and Player classes relate to one another and how the GameService class manages game instances. This helped me communicate the structure of the application and the reasoning behind my design decisions.

## 3. What Was Helpful About the Design Document Process?

Creating the design document helped me think through the application's structure before implementation. Developing the domain model allowed me to understand the relationships between games, teams, and players, while considering design constraints helped me identify requirements such as unique identifiers and names. Evaluating different operating platforms also helped me consider performance, scalability, and cost. This planning process provides a clearer direction for development and can reduce confusion when translating requirements into code.

## 4. What Would I Revise and How Would I Improve It?

If I could revise my work, I would expand the platform evaluation section with more detailed comparisons of the advantages and disadvantages of each operating system. I would also provide additional examples explaining how the proposed architecture would handle increasing numbers of players and simultaneous game sessions. These improvements would make my recommendations more detailed and help the client better understand why the proposed solution fits the application's requirements.

## 5. How Did I Interpret the User's Needs and Implement Them Into My Software Design?

I interpreted The Gaming Room's needs by identifying the main requirements for expanding Draw It or Lose It beyond Android. The application needed to support different devices, multiple games, teams, and players, while maintaining unique names and identifiers. I incorporated these needs into my design by recommending a web-based, server-based architecture with centralized game information. Considering user needs is important because software must solve the client's actual problem, work as expected, and provide a useful experience for its intended users.

## 6. How Did I Approach Designing Software, and What Would I Do in the Future?

I approached software design by reviewing the requirements, identifying design constraints, developing a domain model, evaluating operating platforms, and making recommendations for the system architecture. I recommended Linux for the server because of its flexibility and suitability for web applications, with users accessing the game through browsers on different devices. In future projects, I would continue using requirements analysis, UML diagrams, object-oriented design principles, and comparisons of potential technologies. I would also seek feedback and review the design against the original requirements to ensure that the final solution meets the client's needs.
