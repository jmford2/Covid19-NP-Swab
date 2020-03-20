*Last updated: March 20, 2020*

# Making NP swabs

As clinical laboratories around the world have begun testing for Covid-19, we have encountered a new crisis: a shortage of the swabs required to obtain the necessary sample. These are called nasopharyngeal swabs, or NP swabs for short.

**The goal of this repository is sharing information required to manufacture NP swabs locally/everywhere at volumes of thousands per day, until standard manufacturers can make and deliver more.**

Because the crisis is **now,** the goal is to re-create versions of the swabs already in use (as opposed to creating better/fundamentally different redesigns).

The files in this repo contain some information to get started. **This includes .stl files that you can modify/print (see the list of files above).**

If anyone has any questions, please reach out to any of the contributors here or to Dr. Ramy Arnaout, MD, DPhil, at rarnaout@bidmc.harvard.edu.

This is a team effort with already dozens of people involved from all over the country, including industry, academia, and just members of the public, none looking for thanks or recognition, helping out just because they can.

Anything you find here is free for use for all.


## Contents

- [Basic description of an NP swab](#design)
- [Requirements](#reqs)
- [NOT required](#not-reqs)
- [List of known acceptable swabs](#acceptable-swabs)
- [Approaches](#approaches)
- [Flock](#flock)
- [Contact](#contact)

<a name="design"></a>
## Basic description of an NP swab

![Copan 480C](swab_images/copan_flocked_swab_macro.png)

![Copan 480C closeup](img/nasopharynx-child.png | width = 250)

![Copan 480C closeup](swab_images/copan_flocked_swab_micro_1.png | width = 250)

An NP swab is a flexible stick around 15cm in length that goes up your nose to the back of the nasal cavity (see [movie](https://www.youtube.com/watch?v=hXohAo1d6tk&feature=youtu.be&t=40)). It is swept or twirled around to brush or wick up secretions, which carry Covid-19 virus particles. The swab comes out of the nose and goes into a vial that contains fluid (viral transport medium). The vial gets capped and sent for processing.

There are **two parts**: a bristled **bulb** end (above) and a **shaft**. The bristles in the above are nylon.

The bulb looks like it would be fluffy to the touch but it is not: the bristles are short enough that it feels more like hard foam.

Often the shaft itself has a thin **neck**, for flexibility, and a thicker **handle**. The handle is often **scored**---a weak point in the shaft---where you can break it off so the bristled part stays in the vial; the handle is then thrown away.

The distance along the handle where the scoring occurs depends on the vial you use. For example, for the vials for use with Copan 480C swabs, the breakpoint is 7cm; for [15-](https://www.fishersci.com/shop/products/falcon-15ml-conical-centrifuge-tubes-5/p-193301) or [50-mL](https://www.fishersci.com/shop/products/falcon-50ml-conical-centrifuge-tubes-2/p-193321) conical tubes (of the kind used routinely in biomedical research and sold by many manufacturers), 11.5 cm will do (the 15mL Falcons are listed as 12cm, 50mL as 11.5cm, but we haven't checked yet whether this is interior height or includes the cap).


<a name="reqs"></a>
## Requirements

-	Wand is stiff enough to push to the back of the nasal cavity but flexible enough to get up the nose and will bend when it hits resistance instead of stabbing people (for reference, swabs are a little more flexible than the tiny straws used for coffee, and somewhat similar to the inside tube that holds the ink when you take apart a Bic ballpoint pen)

-	Ideally, the bulb end is *flocked* (see below): it has lots of tiny bristles perpendicular to the wand (see close-up above). The bristles provide for a high surface-area-to-volume and helps both wick secretions onto the bristle and liberate particles when put in the transport medium. Perpendicularity is a nice-to-have that we believe may improve yield slightly but requires electrostatic deposition; even random orientation of flock should work fine

-	Bristles or collecting substrate (including any adhesive) must be firmly attached and not get left behind in the nasal cavity. Similarly no part of the swab should break off or get left in the nasal cavity. We have enough problems with the pandemic already

-	Materials cannot inhibit [PCR](https://en.wikipedia.org/wiki/Reverse_transcription_polymerase_chain_reaction). This means no wood or cotton (although we believe rayon is OK; see partial list of PCR inhibitors below). Nylon and polypropylene seem to be good choices, but start with medical equipment/grade materials if possible since they should be high quality/pure (some additives can be inihibitors).

-	Wand must break off inside the tube – better to be too short than too long.  Wand could be manually scored to create a weak point

For more technical requirements, see [Design Constraints](https://github.com/HMS-RIC/Covid19-NP-Swab/blob/master/Constraints/Design%20Constraints.md)

<a name="not-reqs"></a>
## NOT required

-	Sterility. Not a major concern for most uses; only for immunocompromised (in which case the ability to decontaminate by [autoclaving](https://en.wikipedia.org/wiki/Autoclave) or ethanol bath is needed). The air and the nose are already non-sterile and the PCR assay is specific enough to ignore most contaminants (as long as other Covid-19 contaminated things/people don’t come in contact with it and it doesn’t pick up PCR inhibitors)

-	Labor intensive is ok, to fill short term needs. There are students and researchers out of school and lab who are willing to volunteer to hand-assemble these from inoculation loops, adhesive, and wicking substrate #studentArmy


<a name="acceptable-swabs"></a>
## List of known acceptable swabs

Model what you make after one of these.

Product numbers are listed. Unless otherwise stated, these are from the [FDA approved list](https://www.fda.gov/medical-devices/emergency-situations-medical-devices/faqs-diagnostic-testing-sars-cov-2) current as of **March 20, 2020**. You can look these up online.

**Copan:** 480C *(2)*, 481C *(1)*, 482C *(1)*, 501CS01, 503CS01, 516CS01, 518CS01, 534CS01

**Puritan:** LA-117 *(1)*, 3317-H, 25-3317-H, 25-3316-U, 25-3316-H, 25-3317-U, 25-3318-U, 25-3318-H, 25-3319-H, 25-3320-U, 25-3320-U EMB 100MM, 25-3320-U EMB 80MM, 25-3320-H and 25-3320-H EMB 80MM

*(1)* Preferred, per FDA

*(2)* Acceptable, per BIDMC


<a name="approaches"></a>
## Approaches

#Approaches under investigation:

(1a) 3D printing a shaft, and attaching flock material via adhesive

(1b) 3D printing a shaft with enough definition---either "nubs" along the surface or bristles---to gather secretion from the nasopharynx.

#Other Approaches:

(2a) Repurposing existing materials, including cosmetics applicators or "loops" used in microbiology

For more detail on ideas not yet investigated, see **Other Approaches** (link to come)

### Scrounging, Repurposing

...but just a word about scrounging and repurposing. There are lots of swabs used for various things floating around hospitals, outpatient clinics, private practices, and so on. **Be creative and ask everyone you know. That's what we've been doing and it's gotten us thousands of swabs.** This is a stopgap at best, but every swab counts.

Will a repurposed swab work? Find someone who uses NP swabs, take pictures of what you find, and ask that person to weigh in on suitability. (We've been asking our respiratory care personnel.) In practice, as long as the materials are not wood or cotton, there's a chance you've got something usable. **If you find something that works, please tell us,** along with how you know it works, and we'll post it.

### Manufacturing

The consensus of a fair bit of thinking on our part is the simplest high-throughput approach is **3D printing**:

- 3D print a wand with the appropriate form factor (e.g. see the picture above and the .stl files)
- dip bulb in adhesive (we are working on appropriate adhesives)
- dip sticky bulb in [flock](#flock)
- shake/blow/rinse off excess flock
- (if needed) dip in 70% ethanol for sterilization

If this sounds like how you'd solve this problem if you were still in elementary school, you're right. This is basically decorating Easter eggs (if you started with a 3D-printed Easter egg). Currently we have no proven way to automate the last three steps so we are envisioning a "student army," as mentioned above. **If you've got a better idea, now's the time.**

There are several alternatives being tried:

- We are looking into using small urine loops as shafts; we don't yet have a solution for how to apply a swab end. Will post if we do. At least there are usually very many of these around in clinical microbiology laboratories
- Printing a bristled head is a no-go for conventional 3D printers, as the features are too small. It is possible that a sand-blasted/chemically etched/otherwise roughened bulb *might* work, but we are not doing research here: we're looking for our best bet for a sure thing
- Mascara brushes. The consensus so far is, the materials might be right but the brushes are far too large/widely spaced. Again, they *might* work, but see above

Again, we believe the best use of resources is to be creative around copying the template, not redesigning swabs.


<a name="flock"></a>
## Flock

"Flock" is the name of the bristle material. It can be ordered from e.g. www.flockit.com as a powder. The below information comes from extremely helpful conversations with them and Celluseude, the manufacturer. (Please remember your flock manufacturers and distributors this holiday season.)

- The nylon flock on the tip of the picture is 3 denier (3 dtex) *(1)*

- The flock on the flocked swab above was likely applied using electrostatic deposition: flock coated with something positively charged, shaft coated with adhesive and electrically grounded. We do not need to do this: the previous version of swabs, still widely in use, have matted flock and they work well enough (slightly lower sensitivity but clinically for now we'll take it)

- In general acrylic is used as the adhesive for flock, but be aware that acrylic is a **known PCR inhibitor** (see below). Decision point is rinse a lot to remove loose acrylic vs. just use something safer. Apparently Elmer's has something of the same problem.

- The only colors we should consider for the nylon are black and white, with preference for white. Black has some inorganic compound that was thought to be benign; white has titanium inside the fiber but not on the surface. White is the purest nylon. Colored nylons have various ionic or covalent groups on the outside, which are probably not things we want to deal with.

- Rayon is also safe to use

*(1)* Denier/dtex is a unit of measurement (*grams* per 9,000 *meters*) that the fabric industry uses. Denier is American; dtex is European. If the material had a different density from nylon but was of the same diameter, its denier measurement would be different.


<a name="adhesive"></a>
## Adhesive


Coming soon


<a name="contact"></a>
## Contact us

We want to emphasize this is a **group effort** with literally scores of people working on this right now; if you're reading this, you're probably one of them. If you have something to contribute, please contact Dr. Ramy Arnaout, MD, DPhil, at rarnaout@bidmc.harvard.edu.

Note there's also now a [Slack channel](https://join.slack.com/t/rapidmanufact-iop4498/shared_invite/zt-cykndes6-XtxzG~8bkji64M3wTVWiOw).

