# How the stickers are made

[中文版](how-the-stickers-are-made.zh-Hans.md)

A short note for people who want to make something similar with an image model. The stickers are AI-generated and the review also uses AI, which is not the same as an expert check. The method changed several times; this page describes the current one.

## The loop

1. **Write a short field-mark card** for the species: how to tell it from its closest look-alikes, the bill, the legs and feet, the key proportions.
2. **Find reference photos.** When suitable photos exist, the prompt asks the model to use them as a reference for the bird's appearance, but not to copy the pose.
3. **Generate** with GPT-image. Most birds get the same field-guide layout: head to the left, side view, wings folded, both feet flat on an invisible ground line, plain light-grey background. Swimming, flying and a few other groups get their own poses.
4. **Review.** A second model scores the image from 0 to 4 on identification, plumage, bill and eye, legs and feet, and proportions. It passes only if every score is at least 3, identification is 4, and the image would work as a plate in a field guide.
5. **If another round is needed**, the reviewer is asked to propose one to three corrections, which go into the next prompt; where they conflict with anything else, the prompt says the corrections win. After it passes, the bird is cut out, upscaled if needed, and tagged as AI-generated in its metadata.

## Example prompt

One of the first-round images for the Canary Islands Robin (*Erithacus superbus*). Two images are attached: reference photos of the species, and an approved sticker of the European Robin, a related species, as a model for pose and rendering. Below are the original instructions given to the image-generation agent, translated from Chinese (the first paragraph was in English already). The agent rewrote them when it called the image-generation tool. The list of lessons at the end is long and is summarised in square brackets.

```
TAIL: draw the whole tail at its true length and shape for this species. The canvas
is wide on purpose: never shorten, fold, curl or crop the tail to make it fit.

Image 1: reference photos of this species (several may be combined). Use them only
to check plumage, markings, bill, legs and feet, and proportions; pose and angle
follow the written rules, don't copy the photos; don't draw watermarks or text
from the photos.
Image 2: a sticker of another species in the same group, already drawn to our
rules, as a model. Learn only its pose, foot structure, rendering and texture;
never its colours, markings or body proportions. This bird's appearance follows
the text and the reference photos. Note: the model shows Erithacus rubecula,
exactly the related species this bird is most easily drawn as; wherever the
differences below apply, draw this bird as itself.

1536x1024 landscape canvas. Draw only one bird, complete and centred, with space
all around; bill tip and tail tip inside the frame. The whole background flat
light grey #D9D9D9, no shadow; no white outline or sticker border around the bird
(don't copy the white border on the model). Realistic photographic look, crisp
feathers, like a standard image in an authoritative field guide; not an
illustration, not a cartoon. Rules: head toward the left of the frame, camera at
the bird's eye level, body turned slightly toward the viewer, about 15 degrees;
head in full profile, with the eye, bill shape and facial markings fully visible;
bill closed; wings folded; tail complete and naturally closed. Draw the typical
plumage of an adult, not the mottled look of a juvenile or subadult. Apart from the
markings described, feathers smooth and evenly coloured; don't add grid, scale,
chevron, groove or ring textures or regularly arranged highlights; spots and bars
vary naturally in size and spacing like on a real bird, never in neat dot grids or
a checkerboard.

This bird: Canary Islands Robin, Erithacus superbus. Draw the adult; sexes alike.
Pose: standing, side view: body at about 30 to 45 degrees to the ground, both legs
showing; both feet on an invisible horizontal ground line: soles at the same
height, toes relaxed and flat on the ground, hind toe flat on the ground too; not
curled into a grip, not in the air; no branch, rock or ground drawn.
Key points: forehead, face, throat and upper breast one solid patch of deep
orange-red, redder and deeper than the European Robin; around the orange-red a
broad blue-grey band, from above the eyebrow to the sides of the neck and breast;
a clear white eye-ring, conspicuous on the orange-red face; difference from the
European Robin E. rubecula: this species is a deeper, redder orange, with a broader
grey band, a white eye-ring, and a clearer boundary between the white belly and the
breast; the European Robin has no white eye-ring; upperparts dark olive-brown;
belly white, flanks pale grey-brown; bill black, thin and straight, about 40% of
the head length; legs fairly long, legs and feet pale brownish pink, three toes
forward and one back, visible tarsus about twice the bill length; tail about 40%
of the total length, olive-brown.
Difference from the most similar species (must be shown): this species is a
deeper, redder orange, with a clear white eye-ring and a broader grey band; the
European Robin Erithacus rubecula is paler orange, with no white eye-ring.
Lessons for this group: [mistakes earlier stickers in this group made, one line
each, e.g. "markings follow individual feathers; don't sprinkle them evenly over
the whole body"]
```

## A few things we learned

- **Be specific, even about the obvious parts.** In our experience "tail about 40% of total length" works better than "long tail", and parts you leave out tend to come out as a generic bird: thin pink legs, a songbird foot, a guessed tail length.
- **Set the pose yourself, with feet on the ground.** When the pose followed the photo, some images copied backs or flight shots and hid the identifying marks. In one test, when we asked for feet gripping an invisible branch, many images had dangling, spread claws, so standing birds now have both feet flat on an invisible ground line.
- **Write review feedback as sentences that can go straight into the prompt.** For example "visible tarsus about twice the bill length", not "legs are wrong".

## Limits

The images and the review are both AI, and some mistakes will only be found by people who know the birds. If you know one family well, [review it](../../../issues/new?template=family-review.yml); if you see a mistake, [report it](../../../issues/new?template=sticker-error.yml). Contributors are listed in [CONTRIBUTORS.md](../CONTRIBUTORS.md).
