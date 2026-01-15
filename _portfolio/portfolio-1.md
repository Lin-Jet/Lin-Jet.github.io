---
title: "L Game"
excerpt: "Implemented Edward de Bono’s L-game with a custom AI agent using minimax and alpha-beta pruning. Optimized for time and memory using heuristics and memoization. Added board transposition, flipping features, and visual enhancements for improved user interaction. Earned first place in class tournament by instantly computing optimal moves with a stronger heuristic."
collection: portfolio
---

[L Game GitHub Repo](https://github.com/Gandledore/L-Game-AI)

For the final project of CSE 175 Artificial Intelligence, we were tasked with implementing Edward de Bono’s L-game and developing a custom AI agent using minimax and alpha-beta pruning. 

Working with my tutoring center coworkers, we stayed after hours planning our project on the whiteboards. We planned out the structure of our game and implemented the functions in pseudocode. 

After game implementation, we focused on finding strong heuristics. I enjoyed the brainstorming process, playing the game with my teammates, and coming up with heuristics for our AI agent to play optimally. 
I implemented minimax and alpha-beta pruning, and we ran into our first issue. With many possible game states, our agent runs frustratingly slowly.
We speculated that all board positions were simply rotations or reflections of each other, but we could not formalize this insight. After sketching dozens of L-piece configurations on the whiteboard, I had a breakthrough: an L-piece has only six fundamental orientations. This meant we could normalize every board position into a canonical form, dramatically reducing our search space.

Implementing this transformation was exhilarating; our agent's response time became instantaneous. Combined with memoization for infinite lookahead, it now calculates moves instantly. 
We were efficient with our project time management, even developing many bonus features. We earned first place in the class tournament. Through this project, I learned to identify bottlenecks for optimization, create clear, concise code, and problem solve through team collaboration.
I took these skills and applied them to my Awan AI benchmark, NeuralSeek Agentic AI math tutor, and recent work creating a herb formula recommendation model based on symptoms.

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->


