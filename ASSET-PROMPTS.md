# Sunshine Bay asset package

## Animated clean-up volunteer

assets/cleanup-cycle.png — built-in ImageGen, transparent 4×2 sprite atlas of the same friendly worker: tied curly dark hair, orange volunteer vest, cream shirt, navy shorts, protective gloves and a green grabber. Top row: four walking-cycle frames. Bottom row: leaning down, crouching to pick up rubbish with the grabber, standing with a tied gray bag, and dropping the bag into a bin outside the frame. Consistent elevated three-quarter 3D game camera, equal cells, full body, aligned feet, no background, floor, shadows, text or borders. Used for actual walking, collection and disposal instead of rotating a static cutout.

## Full-screen panorama

assets/beach-panorama.png — built-in ImageGen horizontal extension of beach-living.png, requested as an ultrawide 3:1 panorama. Keep the original beach scene centred and extend both sides seamlessly with palms, hibiscus, boardwalk, dunes, coastal rocks and ocean. Match the original sunny 3D game rendering and retain the kiosk, stage, umbrella and rockpool layout; no people, animals, turtle, litter, text or new interactive objects. Returned image: 2172×724, displayed as a 3072×1024 panoramic environment behind the logical playfield.

## Animated-world additions (November 2026)

beach-living.png is an ImageGen edit of beach-clean.png: remove only the static turtle, fill its area with matching water and underwater pebbles, and preserve the beach layout. The turtle is now an independent sprite animated by beach-life.js. Floating debris and wave/ripple overlays are independent game elements; litter removal follows mission state.

visitors.png was generated with built-in ImageGen as a transparent 3×2 full-body sprite atlas with consistent raised three-quarter camera, warm lighting, rounded detailed 3D materials, equal scale, aligned feet and no scenery. Requested visitors: a red-haired adult woman in a cream shirt and teal shorts; a dark-skinned man in a navy polo, beige shorts and sunhat; a teenage boy in a pale yellow striped shirt and turquoise shorts; a female volunteer in an orange vest and blue shorts; a male volunteer with a navy cap, sage shirt and tan shorts; a blond teenage girl in a coral top and green shorts. Empty hands allow bottles or grabbers to be attached in code. No floor, shadows, text, borders, overlap or drawn inventory items.

Generated with the built-in ImageGen tool. All production images are stored in assets/. No paid API key, externally loaded image or image-generation service is required to play.

## beach-world.png

Use case: stylized-concept. Create a polished beautiful isometric 3D game environment background for a teenage English learning point-and-click adventure, landscape 3:2 image. High quality cozy handcrafted 3D render, rounded rich materials, detailed sand, soft ambient occlusion, warm sunlight, turquoise ocean along the upper edge with tiny foam waves. Elevated three-quarter overhead camera, playable sandy beach spans center and lower two thirds, generous open walking paths. Upper left small coral orange beach drinks kiosk with striped awning; upper middle distant wooden festival stage with speakers and bunting; upper right a striped violet beach umbrella, deckchair and camera tripod; lower right a shallow turquoise tidepool with rocks and a tiny sea turtle; lower left blue and green recycling bins and a wooden boardwalk entrance. Several discreet scattered plastic bottles and wrappers, lush palm trees along left and right borders. No humans, UI, letters, logos or speech bubbles. Crisp premium adventure game art, visually appealing to a 13-year-old, not flat vector, not low-poly geometric blocks. All objects match the same orthographic camera.

## characters.png

Production sprite sheet for a premium cozy isometric 3D beach adventure. Transparent background. Strict three columns by two rows equal grid, six separate full-body characters, each entirely within its cell, no overlap, same scale and three-quarter isometric camera, feet visible. Soft sunlit rounded stylized high-quality 3D animation-film materials, detailed expressive faces. Top left: 13-year-old girl explorer with chestnut ponytail, turquoise shirt, cream shorts, coral backpack and trainers, facing front right. Top middle: young adult smoothie kiosk owner, curly dark hair, orange apron over white tee, holding reusable cup. Top right: teenage girl influencer, dark curly bob, lavender shirt and shorts, sunglasses on head, phone. Bottom left: teenage football player, blue sports shirt, sandy blond hair, ball. Bottom middle: female marine volunteer, mustard shirt, green shorts, sunhat, clipboard. Bottom right: young male DJ with brown skin, mint green open shirt and headphones. No text, numbers, borders, floor or background scenery. Clean alpha silhouettes, lighting upper left.

## items.png

Production item atlas, transparent background, strict four columns by two rows grid. Exactly eight separate fully visible items, centered in each cell, no overlap, elevated three-quarter camera, sunny lighting, rounded detailed 3D materials. Row one: turquoise reusable metal water bottle; wooden litter grabber with green claw; coral protective gloves; wooden handcart carrying blue water refill tank. Row two: blue lidded recycling bin; rolled green collection net with wooden handle; charming red-orange crab with raised claws; cute green sea turtle with patterned shell. No text, grid lines, scenery, floor or baked shadows. Clean cutouts for inventory and beach props.

## walk-cycle.png

Production animation atlas, high-quality 3D render, transparent background. Exactly four columns by two rows equal cells. Same teenage girl in all eight cells: chestnut high ponytail, teal short-sleeve shirt, cream shorts, coral backpack, white and teal trainers. Full body visible, same scale, aligned feet, padding. Raised three-quarter camera, warm sunlight. Top row four successive walk frames facing right/front: left foot forward, passing, right foot forward, passing. Bottom row four walk frames facing right/back, backpack visible. Natural arm swing and leg movement; consistent face and outfit. No text, grid, scenery, floor or colored background.

## beach-clean.png

Edit target: beach-world.png. Produce its cleaned-up final state. Preserve camera, dimensions, layout, sunlight, sand texture, kiosk, stage, palms, umbrella, chair, bins, boardwalk, rocks, turtle and water. Only remove scattered plastic bottles and snack wrappers from sand and tidepool vicinity. Fill removed areas seamlessly with sand or water. Do not add people, text or new objects. Layout must match the original for partial overlays.

## Sprite atlas coordinates

Characters, zero-based row-major: 0 Mia, 1 Max, 2 Bella, 3 Leo, 4 Ruby, 5 Finn. Items: 0 bottle, 1 grabber, 2 gloves, 3 water cart, 4 lidded bin, 5 net, 6 crab, 7 turtle. Walk cycle: row 0 front/right; row 1 back/right; mirror horizontally for leftward movement.
