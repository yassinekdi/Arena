# Functional Requirements

1. **Multiplayer Gameplay**
   - Enable real-time gameplay allowing multiple users to interact and play Crazy Eights simultaneously.

2. **Anonymous Users**
   - Users can enter a temporary name to play. Sessions are deleted once the user closes the browser or logs out.

3. **Game Creation**
   - Allow users to create a game, wait for others to join, invite specific users by name, and choose RL agents to participate. The game starts when the minimum number of players is reached and the user decides to start it.

4. **Join Restrictions**
   - Users cannot join a game as a player once it has started, but they can join as viewers.

5. **Player and Viewer Limits**
   - Accommodate up to 8 players per game and display the number of viewers in the room during the game.

6. **Game Rules**
   - Implement and enforce the official rules of Crazy Eights.

7. **Reconnection Grace Period**
   - Allow a defined time for users to reconnect with the same username if disconnected. Failure to reconnect results in session loss.

8. **Notifications**
   - Provide notifications for game invites, game start, and when it's a player's turn.

9. **Game Timer**
   - Implement a timer for each player's turn to keep the game pace consistent and prevent delays.


# Non-Functional Requirements

1. **Maintainability**
   - Ensure code is modular and well-documented. Use GitHub for version control.

2. **Scalability**
   - Design the system to handle a growing number of users and concurrent game sessions.

3. **Reliability**
   - Ensure high availability and minimal downtime through redundancy and fault-tolerant design.

4. **Observability**
   - Implement comprehensive logging, monitoring, and alerting using Grafana. Include metrics for app performance, user activity, game sessions, and RL agent performance.

5. **Performance**
   - Optimize for minimal latency and fast response times, ensuring smooth real-time gameplay.

6. **Usability**
   - Design an intuitive and user-friendly interface, ensuring easy navigation and interaction.

7. **Flexibility**
   - Ensure the system is easily extendable for new features, game rules variations, and integration of additional RL agents.

8. **Testability**
   - Implement unit tests and integration tests.

9. **Cost Efficiency**
   - Optimize the design and deployment to minimize operational and infrastructure costs.
