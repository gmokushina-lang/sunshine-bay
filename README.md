# Sunshine Bay

Unzip the package and open index.html in Chrome or Edge. Keep the assets folder beside the HTML file. The game works without external JavaScript libraries. Optional web fonts fall back to system fonts offline.

## Play

Click the sand to walk, or use the arrows / WASD. Click a character to approach and talk, or a glowing circle to explore. Mia never walks automatically after a conversation or mission. Open “⚑ Mission” for a small side task card without dimming the beach. “Show me” marks a destination; you decide when and where to move.

Choose a plan, explain your idea aloud, then press “I’ve said my idea”. Use “Type instead” to write your answer. Characters ask a follow-up question. Find the item for your plan and bring it back. The water cart starts beside the boardwalk. The backpack stays at the top of the screen. The whole beach fits in the viewport; there is no page scrolling.

“Need words?” opens optional English phrases. “Our story” opens the conversation history. “Voice on” enables an available English browser voice. Progress is saved in the current browser. The restart button asks before beginning a new game.

## Teaching notes

Designed for A2–B1 individual lessons, around 15–25 minutes. Invite the learner to give reasons, consider trade-offs and adapt ideas. The main activity is speaking; typing is optional.

Characters use branching, prewritten dialogue. Typed answers can route an open plan using keywords; the game does not evaluate meaning or grammar. There is no speech recognition. The teacher listens to spoken answers and can expand the character’s response.

## Files

The panoramic background fills the screen edges. The logical playfield and all controls still fit without page scrolling. Both wrapper clues are on open sand away from the characters. Visitors use a separate approach lane; volunteers work in separate beach areas.

index.html — interface. game.js — navigation and interaction. story.js — five missions and fifteen dialogue branches. game.css and readability.css — visual design and large-text layout. assets/ — generated environment, clean environment, character sheet, walk animation and item atlas. ASSET-PROMPTS.md — image-generation prompts.

The game uses an isometric 2.5D environment with rendered 3D art and animated sprites. Image assets were created with built-in ImageGen. play.css provides the full-screen HUD and mission overlay. beach-life.js animates the waves, swimming turtle, floating litter, visitors with reusable bottles, clean-up volunteers and final festival. Litter disappears after the relevant mission. At the end, six distinct guests relax around the beach with warm lights, a short confetti celebration and optional locally synthesized music. Fast synchronized dancing and repeated confetti are disabled. Music plays only when its button is pressed.

Run `node tests/game.test.cjs` to check all five mission transitions, manual movement, scene rewards and navigation routes.
