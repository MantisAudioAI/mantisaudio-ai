# Developer Log #02 — The Interface Is the Canvas

### Why my music software starts as a picture

I've been a comic book fan my whole life. Long before I wrote a line of code, I was studying cover art and the way a great cover tells you an entire story before you ever open it. That obsession turned into more than 25 years of graphic design work.

So when I sit down to build a music program, I don't start with a spec sheet. **I see the instrument first.** The panel, the wear on the paint, the glow of the screen, the little red LEDs over the buttons. By the time I'm drafting code, I already know what the thing looks like and how it should feel under your hands.

For me, the interface isn't a wrapper around the features. It's the canvas.

#### Same hands, two mediums

If you've seen my Daytona Faded artwork for Electric Matrix AI, you've already seen the instincts behind my software: the pulp comic covers, the VHS sleeves, the Channel 900 tape spines. Worn paper, halftone grit, neon against a dusk sky, a strong sense of era, and a cast of characters you start to recognize. (Yes, the mantis in the suit is the same one in my company name.)

My software comes out of the same toolbox:

- **Lofi Hip-Hop Lab's Arrange console** uses chunky, stackable blocks for patterns. You can see the whole arrangement at a glance, like snapping bricks together on a bedroom floor.
- **NYC '94** wears a skyline across the top of the chassis, because the city and the era are part of the sound.
- **Lofi Hip-Hop Lab v2** has a cartridge slot and a 4 track cassette deck, because loading a sound should feel like loading a tape.
- **2K Platinum Synth** browses presets as CD jewel cases, because in the early 2000s that's how you found new sounds: flipping through discs.
- - **The FX pedal collection** has 26 pedals, and every one is a small piece of illustration: a fox on the Fuzz, an owl on the Filter, a turtle on Slow Down. Each pedal is its own little album cover.


None of that is decoration for decoration's sake. **Visual identity tells you what an instrument is for before you press a single key.**

#### Why it matters to the code

Seeing it first changes how I build. When the picture is clear, the structure follows: what lives on the main screen, what hides in a drawer, which control earns a big knob and which one gets a small button. Layout is a hierarchy decision, and hierarchy is a design decision.

Comics taught me that. Panel order, focal points, where your eye lands next. A good interface reads the same way a good page does.

It also keeps me honest. If a feature doesn't have a natural place on the panel, it usually means I don't fully understand it yet.

#### A little nostalgia, a lot of intention

I'm drawn to skeuomorphism, the old school idea that software should resemble real objects. A lot of modern apps moved toward flat, clean, interchangeable screens. Those work. But they rarely make you feel anything.

I want my instruments to have a time, a place, and a personality. A 1994 New York sampler shouldn't look like a chrome 2002 rompler workstation, and neither one should look like a dusty lo-fi tape box.

//

*More soon from the design table.*

#UIDesign #GraphicDesign #ComicArt #AudioSoftware #SynthDevelopment #CreativeCoding #AIAssistedDevelopment #Skeuomorphism