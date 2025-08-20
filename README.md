1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room(client) wanted to expand their Android based game 'Draw It or Lose It' to support web based access across multiple platforms. Their requirements included scalability for many users, real time gameplay with timers and synchronized updates, unique identifiers for games, teams, and players, with a secure, distributed architecture. The goal was to deliver a responsive and accessible game experience while preserving the feel of the original mobile version.


2. What did you do particularly well in developing this documentation?

I think I did particularly well in clearly outlining the technical and business requirements, and then translating those into concrete design decisions. For example, I emphasized scalability, security, and memory efficiency by recommending the use of Linux servers, WebSockets for real-time communication, and Redis caching for game states. This helped connect the client’s needs directly to technical solutions within the document.


3. What about the process of working through a design document did you find helpful when developing the code?

The design document gave me a structured roadmap to follow. By breaking down system architecture, constraints, and domain models ahead of time, it made it significantly easier to see how different parts of the code would interact. Having requirements and constraints defined upfront helped prevent scope creep and ensured that design choices aligned with user needs before any actual coding began.


4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I were to revise one part, I would make some additions to the evaluation section comparing operating platforms. While I provided analysis for each environment, I would improve it by adding more performance metrics, benchmarks, and cost comparisons to support the recommendations with quantitative data. This would help make the evaluation stronger and more persuasive for the client.


5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted user needs by focusing on accessibility, ease of use, and real time responsiveness of the application. For example, users needed a seamless experience when playing on any device, desktop or mobile. For this reason, I recommended responsive design and browser based compatibility. Considering user needs is crucial because software that doesn’t match how users/clients actually want to use it won’t succeed, even if it’s technically sound.


6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach combined requirements gathering, domain modeling, and system architecture planning. I applied OOP principles such as encapsulation and inheritance to keep the design flexible and maintainable throughout it's lifespan. In the future, I’d continue using structured design documents but iI would also want to incorporate more prototyping and user testing earlier in the process. This would help validate design assumptions sooner and aid in refining features before development gets too far down the road.
