FRUIT RIPENESS DATASET FOR MACHINE LEARNING FOR KIDS

CONTENTS AND COUNTS
Six requested classes, with 20 distinct photographs each (120 images total).
No requested class was substituted or omitted.

RipeTomato: source-identified ripe tomatoes (Solanum lycopersicum), including
red, orange, and purple cultivars; whole fruit and one cross-section.
UnripeTomato: source-identified immature tomatoes before full ripeness,
including green and striped cultivars; single fruit and same-class groups.
RipeLemon: source-identified ripe lemons, including Meyer and New Zealand
Lemonade cultivars. Ripe lemons can remain green: color alone is not a reliable
ripeness test. Whole fruit and slices are included.
UnripeLemon: source-identified immature or still-ripening lemons, including
Meyer lemons. Lime photographs and confusing non-lemon species were excluded.
RipePomegranate: source-identified ripe pomegranates (Punica granatum),
including intact fruit, naturally split ripe fruit, and cut fruit with seeds.
UnripePomegranate: source-identified immature or still-ripening pomegranates
before full maturity; green and reddish developing fruit are included.
Pomegranate flowers without recognizable fruit were excluded.

WHY THESE CLASSES
The six classes were specifically requested for a children's workshop. The
fruit types are familiar, and tomatoes, lemons, and pomegranates have different
shapes, skin textures, and calyces. Ripeness pairs are a harder activity than
classifying fruit types: cultivar, climate, and developmental stage can make
ripe and unripe fruit visually overlap. These labels describe source-reported
ripeness rather than just red/yellow/green appearance.

SELECTION AND QUALITY CONTROL
Candidates were researched on Wikimedia Commons, Flickr, and iNaturalist.
The search pool exceeded 30 candidate photographs in each class when combining
sources. Search matches were not treated as valid examples automatically.
Species and maturity were checked against source descriptions, titles,
photographer tags, or explicit Commons subject categories. Source-page tags
and categories were accepted as source-provided labels, not independent
botanical measurements. Every retained photo was visually reviewed for
recognizable fruit and consistency with its label.

Excluded: illustrations and scans; irrelevant species; flowers without fruit;
uncertain maturity descriptions; obvious mixed ripe/unripe scenes; images
with mostly obscured or very small fruit; heavily edited or obviously
synthetic candidates; large text/logos/watermarks; duplicate exports; and
multiple versions of one source photograph. No synthetic images or augmented
copies were created. Natural variations in angle, lighting, background,
number of fruit, color, and cultivar were retained.

The 120 retained images were compared across all six folders using decoded
pixel checksums and perceptual hashes, followed by visual comparison and
source-photo identity checks. Near-duplicate versions and alternate website
copies were excluded. Every final JPG was decoded and checked for corruption.
File counts, balanced class sizes, source CSV coverage, and ZIP integrity
were checked after packaging.

IMAGE PREPARATION
JPG files with the original aspect ratio and a maximum longest side of 1000
pixels. EXIF orientation was normalized and images were saved as RGB JPG at
quality 90. Some source images are smaller. No crop, flip, recolor, or
generated augmentation was used to multiply examples. Thumbnails are resized
versions of the original photographs, not additional training examples.

SOURCES, ATTRIBUTION, AND REUSE
Every file is listed in dataset_sources.csv with its class, source page,
creator, actual license, license link where supplied, direct image URL,
labeling evidence, and preparation details. Keep this CSV with any shared
copy of the dataset so attribution is preserved.

This ZIP is a collection of images with DIFFERENT licenses. It is not a
uniformly licensed or unrestricted dataset. CC BY images require creator
credit, source/license links, and disclosure of modifications. CC BY-SA
images have those requirements and require adaptations to use the same or a
compatible license. CC BY-NC and CC BY-NC-SA images permit noncommercial use
only unless separate permission is obtained; the latter also requires
share-alike for adaptations. Do not assume that a paid or commercial workshop
is covered merely because it is educational. Public-domain/CC0 images have
no attribution obligation under the stated copyright designation, but
creator/source credits have been retained voluntarily. The individual
source pages and license texts govern each image.

LIMITATIONS
Source-reported ripeness was verified as a label; the collector did not grow,
taste, or laboratory-test the fruit. Photographer tags and community
categories can contain mistakes, even after visual screening. Ripeness
cannot always be established from a photograph alone. In particular, a
source-identified ripe Lemonade lemon and a source-confirmed ripe green/yellow
lemon harvest are included in RipeLemon. These are genuine requested-class
examples, but they make the ripeness task harder. Some pomegranates are
reddish while still developing, and others are yellow/brown when ripe.

Cultivars and locations are not evenly distributed. The unripe classes
contain more attached fruit, while some ripe classes contain cut or harvested
fruit. Both ripe and unripe classes include outdoor foliage and close-up
views, and the lemon classes also include indoor examples, but residual
presentation and background bias remains. Some sources/photographers appear
more than once with distinct photographs. No perfect independence of
orchards, trees, or growing conditions is claimed.

WARNING: the model may learn background, lighting, leaves, cut surfaces,
photo style, or presentation instead of the fruit and its maturity. A high
training score does not demonstrate reliable real-world ripeness detection.
This activity is not a food-safety or agricultural ripeness assessor.

USING THE DATASET
Create the six labels in Machine Learning for Kids and upload the JPGs from
each matching folder. Reserve 3-4 images per class for testing and do NOT use
those images during training. Where possible, hold out a different
photographer/background rather than randomly separating similar scenes.
Try fresh, independently sourced test photographs too, and discuss any
mistakes with the children. For an easier extension, pool ripe/unripe images
into three fruit-type labels (Tomato, Lemon, Pomegranate); the delivered
six-class dataset itself remains unchanged.

SOURCE COUNTS
Wikimedia Commons: 63
Flickr: 46
iNaturalist: 11

LICENSE COUNTS
CC BY 4.0: 4
CC BY-SA 4.0: 25
CC BY-SA 2.0: 7
CC BY 2.0: 24
CC0: 6
CC BY-NC 2.0: 9
CC BY-SA 3.0: 16
CC BY-NC 4.0: 11
CC BY-NC-SA 2.0: 11
Public domain: 3
CC BY-SA 2.5: 1
CC BY 3.0: 1
CC0 1.0: 1
CC BY 3.0 us: 1
