# Tomato canopy images for population growth-stage determination

Canopy images of greenhouse tomato acquired by a rail-mounted inspection robot,
used in the study *"From leaf patches to population phenology: growth-stage
determination in greenhouse tomato canopies"*.

## What is in this dataset

398 images, provided **as acquired** - no cropping, masking, resizing or colour
adjustment. Only the file names were changed; every original file name, which
carries the camera address and the acquisition timestamp, is kept in `metadata.csv`.

```
autumn_greenhouse/     seedling/  flowering/  fruiting/
spring_greenhouse/     seedling/  flowering/  fruiting/
metadata.csv
```

| Sequence | Resolution | seedling | flowering | fruiting | Total |
|---|---|---|---|---|---|
| autumn_greenhouse | 3840 x 2160 | 155 | 49 | 74 | 278 |
| spring_greenhouse | 1600 x 900 | 52 | 40 | 28 | 120 |
| | | | | | **398** |

`metadata.csv` gives, for each image: relative path, growth stage, sequence,
pixel width and height, the date embedded in the original file name, and the
original file name.

## Selection

These are the images retained after review. Frames that did not meet the
acquisition requirements were removed before analysis - mainly those affected by
back-lighting, local over-exposure, or a shooting distance or angle that left the
leaf subject unidentifiable, together with a small number of days on which the
inspection routine could not be completed. Removal was based on image quality
alone and was carried out before any recognition was performed. The counts above
therefore differ slightly from the acquisition totals reported in the paper,
which describe what was collected rather than what was retained.

## Growth stages

`seedling` - `flowering` (flowering and fruit set) - `fruiting`

Stages were assigned by two agronomists experienced in tomato phenological
observation. They read canopy form and the presence or absence of flowers and
fruits image by image, determined the boundary dates between stages, and assigned
each acquisition day to the interval in which it falls. Tomato development is
irreversible, so a crop does not revert once a boundary date has passed.

## Acquisition

**Site.** Greenhouse No. 15, National Precision Agriculture Demonstration Base,
Changping District, Beijing, China (40.18 N, 116.46 E), cultivar 'Rola'
(large-fruited). The spring sequence was taken in a second solar greenhouse.
Both are ridge-cultivated on a north-south orientation with integrated
water-and-fertiliser drip irrigation.

**Equipment.** A movable chassis carrying a high-definition camera, suspended from
a U-shaped rail beneath the greenhouse roof and driven by remote network commands.
Acquisition is entirely non-contact.

**Protocol.** Six fixed positions along the rail; two views at each - a downward
view with the camera pointing vertically down, recording canopy expansion and the
plant centre, and an upward view from below, recording trusses and fruit set in
the upper part of the plant. A 1 m ruler was placed in the canopy at each position
and captured with the images, so pixel dimensions can be calibrated to real ones.
Two inspection runs were planned per observation day, one in the morning and one
in the afternoon, covering front, back and diffuse lighting; greenhouse operations,
weather and equipment status meant that two runs were not always possible.

The autumn sequence covers 18 September to 10 December 2021; the spring sequence
covers 1 March to 8 May.

## Licence

CC BY 4.0. You may use, share and adapt these images provided you give credit.

## Citation

If you use this dataset, please cite the accompanying paper. Citation details will
be added here once the paper is published.

## Contact

Zhiyuan Lyu - lvzhiyuan2020@126.com
College of Mechanical and Electrical Engineering, Hohai University,
Changzhou 213200, China
