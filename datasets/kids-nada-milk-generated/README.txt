SYNTHETIC NADA MILK PACKAGING DATASET

IMPORTANT: ALL 40 IMAGES ARE AI-GENERATED. They are photorealistic synthetic
illustrations, not real photographs of official Nada products. The user
explicitly requested generated images after the real-photo search fell short.
The original exclusion of AI-generated images therefore does not apply to
this revised delivery. No claim of a collected real-photo dataset is made.

CLASSES AND COUNTS
NadaFullFatMilk: 20 generated images, blue FULL FAT panel and blue lower accents.
NadaLowFatMilk: 20 generated images, red LOW FAT panel and red lower accents.
Both classes have blue caps. Class assignment follows the generated front fat
label and packaging accents, not cap color or the visual appearance of milk.
The exact requested two classes are preserved; no extra class was added.

WHY THESE CLASSES
The two familiar milk products support a beginner packaging-recognition
exercise. The blue versus red fat panel is an intentionally useful visual
signal. The task does not measure the fat content of the liquid. Logos and
product labels remain visible because they are part of the requested target.

GENERATION AND PREPARATION
A design preview was generated using the user's described Nada references.
The dataset uses that synthetic design as a consistent visual guide. The
preview, which contains both classes, is excluded from training files.
Twelve candidates were generated as individual scenes. Thirty-two further
independent scenes were rendered as four eight-panel batches. Four scenes
with repeated scene briefs were omitted, yielding exactly 20 per class.
Batch panels were exported as complete images; the grid itself is not a
training image. Each exported panel depicts a different generated scene;
these are not augmentation crops, flipped versions, or recolored copies
of one photograph. Batch provenance is explicitly recorded in the CSV.

Both classes use the same 20 scene briefs, covering gray and white tables,
wood tables, linen surfaces, kitchen contexts, and outdoor foliage. Lighting
includes daylight and room lighting. Views, object size, camera height,
framing, and single/multiple cartons vary. Only one class appears per image.
The generator did not always reproduce the requested camera angle exactly;
actual poses were checked visually. Cell boundaries and complete carton
visibility were checked before packaging.

Generated PNG outputs were converted to RGB JPG at quality 92. Individual
scenes were proportionally resized to a maximum longest side of 1000px.
Batch scenes preserve their native panel size (512px wide, with height
varying according to the generated scene boundaries). No upscaling was
used. Images open correctly and have consistent names. The supplied source
CSV records every image, generator provenance, scene brief, preparation,
and whether it was exported from a generation batch.

SOURCE AND REUSE INFORMATION
There are no external source-page URLs or photographer attributions: every
image was generated for this conversation. Empty source_url fields are
intentional. No Creative Commons or public-domain designation is invented.
Use is subject to the applicable OpenAI service terms and third-party rights.
Nada's logo and related marks belong to their respective owner. This is not
an official Nada dataset or advertisement, and no brand endorsement or
license is claimed. Preserve the synthetic-generation disclosure when sharing.

QUALITY CONTROL AND LIMITATIONS
Each scene was reviewed for a visible carton, a readable FULL FAT or LOW FAT
panel, correct blue/red accents, and absence of the opposite class. Exact
pixel checksums, perceptual similarity screening, and visual review were
used to examine all folders for duplicated or closely repeated scenes.
The paired class scenes are intentionally similar in background; different
product labels and independently generated details are expected to distinguish
them. Similar backgrounds across the two classes should not be interpreted
as one photograph copied and recolored.

Generated carton graphics differ from the user's real-product references.
Fine print, Arabic lettering, nutrition information, and barcodes may be
inaccurate or invented. Do not use this dataset to verify real product
packaging, ingredients, nutrition, barcode identity, or authenticity.
The 40 images are usable examples of the intended synthetic packaging
classes, not independently verified real-world product photographs.

A model may learn background, lighting, camera style, presentation, or
generator artifacts instead of the intended product label. Even though
backgrounds are matched between classes, reliable performance on real Nada
cartons has NOT been tested. Synthetic images alone are a weak basis for
claiming real-world accuracy. Test with original photographs of actual cartons.

WORKSHOP USE
Create the two labels in Machine Learning for Kids and upload the JPGs from
the matching folders. Reserve 3-4 images per class for testing and do not
use those images during training. Prefer holding out different settings.
Also test with genuinely new real photographs. Discuss why blue caps cannot
distinguish the classes and why packaging recognition differs from measuring
fat content. There are no images of both classes together in the ZIP.
