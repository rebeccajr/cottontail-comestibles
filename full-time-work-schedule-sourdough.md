# Full-Time Work Schedule Sourdough

```text
Author: Rebecca
Yield:  2 loaves
```

## About Me

I'm a software engineer and work 9 hour days so I have been experimenting with process to figure out a consistent way to feasibly bake bread within the constraints of my work schedule.

The process here might be a little less traditional, but it works for me and I've been getting good results for my purposes.


## General

**Note:** Quantities for 1 loaf are in parentheses `()`.

### Software

Qty | Ingredient
-|-
`250 g  (125 g)`  | happy starter
`700 g  (350 g)`  | filtered water
`1000 g (500 g)`  | all purpose flour
`22 g   (11 g)`   | salt
`~ 2 qt`          | boiling water

### Hardware

Qty | Equipment
-|-
`1`     | Oven
`1`     | Kitchen scale
`1`     | Probe thermometer
`2 (1)` | Loaf pans
`2 (1)` | (Optional) Parchment paper sheet for lining loaf pan
`1`     | Mixing bowl
`2 (1)` | Containers with lids for dough refrigeration (e.g. mixing bowl, pot with lid, etc)
`1`     | Silicone coated flipper
`1`     | Rimmed baking sheet or any other pan with sides (to hold water for baking)
`1`     | Kettle or device to boil 2 qt water
`2 (1)` | (Optional) Sheet of foil


#### `#ifndef STAND_MIXER` If Not Using Stand Mixer

- Dough scraper
- Surface for kneading

#### `#ifdef STAND_MIXER` If Using Stand Mixer

- Paddle attachment
- Dough hook attachment

## Process

### Day 1

#### Morning 1

1. Feed starter one last time to make enough starter for recipe (e.g. `100 g` happy starter + `80 g` water + `80 g` for 2 loaves). Some know this as leaven.

#### Evening 1

1. Mix starter + water well.

   `#ifdef STAND_MIXER` **If Using Stand Mixer**
   - Use the paddle attachment.

1. Add flour and mix until it turns to a blob. **Note:** Do not add salt at this time. See resource on autolyse.

   `#ifdef STAND_MIXER` **If Using Stand Mixer**
   - Remove attachment after it turns into a blob.

1. Cover bowl and let it sit for 1 - 2 hr (autolyse step).

1. Mix in salt and knead 5 - 15 min.

   `#ifndef STAND_MIXER` **If Not Using Stand Mixer**
   - Do not flour surface.
   - Use the dough scraper to scrape up bits if they get stuck on the surface.
   - You can probably knead for 5 min.

   `#ifdef STAND_MIXER` **If Using Stand Mixer**
   - User the dough hook attachment.
   - Remove dough hook after kneading.

1. Repeat `3x`.
   1. Cover bowl for 30 minutes.
   1. 'Slap and Fold'. See notes.
      1. Using the rubber flipper, scoop up dough from side of the bowl and fold it into the center.
      1. Turn the bowl 90 degrees and repeat for 2 - 3 full rotations.

1. Split dough in half (for two loaves), and put each dough ball into a container for overnight refridergeration. **Note:** If making 2 loaves, you can also split the dough after refrigeration.

1. Refrigerate overnight.

### Day 2

#### Morning 2

1. Remove dough from refrigerator.
1. (Optional) Line each loaf pan with parchment paper.
1. For each dough ball:
   1. Shape by stretching and folding dough into itself until you have a smooth oblong sphere.
   1. Place smoothed dough ball into loaf pan.

   **Note:** I shape the dough in my hands without using a surface to minimize cleanup.

1. Put loaf pans into cold oven.
1. Go to work or get on with your day.

#### Evening 2

1. After 8 - 12 hours, remove loaf pans from oven.
1. Score loaves with sharp knife.
   - **Note:** With this method, the dough might have formed a skin. Ensure that you break through this skin when scoring.
1. Put one oven rack on the bottom part of the oven, and one rack in the middle.
1. Put baking sheet on the bottom rack.
1. Preheat oven to 425 degrees Farenheight.
1. Boil `2 qt` water.
1. When oven is preheated, fill baking sheet with water (don't let it overflow).
1. Put loaf pans on middle rack.
1. Bake for 20 minutes.
1. If after 20 minutes, if the crust is already brown, cover each loaf with foil.
1. Lower heat to 400 degrees Farenheight.
1. Bake for 35 minutes or until the interal temperature of bread is 200 - 210 degrees Farenheight.
1. Remove each bread loaf from oven and pan.
1. Let it cool (or don't 😅) and cut it in half to view the beautiful crumb.

---

## Notes On My Process

### No Special Equipment

In the interest of workflow optimization and my values, I don't use any of the special equipment like a dutch oven, bannetons, or flour towels.

#### Loaf Pans

I like the having uniformly sized slices, so I prefer to bake my bread using loaf pans.

At the time of writing I have two loaf pans: one metal and one glass which is why I started using lower baking temperatures. Though when trying a higher temperature (500 then reduced to 450) the crust would burn before cooking was complete.

#### No Dutch Oven

In the interest of process automation, I no longer use a dutch oven to bake. For my first couple of loaves in loaf pans, I put the loaf pan into the dutch oven. However I found that the bread would rise and hit the lid of the dutch oven, burning the top.

In order to generate steam, I use a pan of water on the bottom of the pan which is working well.

#### No Flour Towels

We have dogs and I simply don't trust any cloth material to touch my food no matter how much I lint roll it. I find that while the dough rests, I can cover the bowl with either a plate (for the 'slap and fold' step), or a tightly fitting lid (in the refrigerator).

#### No Banneton Baskets

I've never owned any bannetons and I see it as another piece of equipment to clean.

### Methodology

#### Slap and Fold in Mixing Bowl

I used to put the dough on my surface to slap and fold, then cover it with an upside down mixing bowl to keep it clean. I find that you can use this method directly in the mixing bowl, and prevent dirtying a surface. Plus, the dough is so sticky at this point that I find it easier to handle with a tool.

#### Cold Filtered Water

I used to warm water before feeding my starter, and before adding to the main recipe. I would meticulously take its temperature, microwave it, then add cold water if needed to get the water to around 100 degrees Farenheight. Now I just get cold filtered water from the fridge and don't worry about the temperature.

### Starter Maintenance

I try to maintain a minimal amount of starter, and reduce the amount of discard I collect.

#### Restarting After A Loaf

When making a loaf of bread and I transfer the starter to the main mixing bowl, I save the bowl with the starter reminants and:

1. Scrape the reminants of the starter from the side of the bowl.
1. Mix the starter reminants with equal parts water and flour (about `10 g`).
1. Transfer to a clean jar.

#### Starter Lid

I lightly screw on the lid of the starter jar to allow for air flow.

#### Every Day: Feed A Little, No Discard, New Jar

Every day I feed my starter, I weigh it, then add equal parts flour and water and transfer it to a *clean* jar. I'm not too concerned with the exact amount of starter, but just make sure the weights of the flour and water are about the same weight as the starter. I will only create discard if my starter goes beyond `100 g`. By my bread making day I need to have `250 g` of active starter, so I will adjust the amounts so that the day before I have about `80-100 g` of starter.

This method probably only works if you have very happy starter - so if your starter is less active, you might want to be more precise, always using equal parts starter, flour, and water.

#### Feeding Times

I feed my starter at least once a day, but twice if I remember. If I feed it twice I don't weigh it and will add the same amount of flour and water as I did previsouly in the day. I will not transfer it to a clean jar until the next feeding. With this method I've never had any issues with mold.

---

## Resources

[What is an autolyse?](https://www.kingarthurbaking.com/blog/2017/09/29/autolyse-sourdough#what-is)
