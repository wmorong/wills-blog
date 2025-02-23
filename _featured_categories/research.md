---
# Featured tags need to have either the `list` or `grid` layout (PRO only).
layout: page

# The title of the tag's page.
title: Research

# The name of the tag, used in a post's front matter (e.g. tags: [<slug>]).
slug: research

# # (Optional) Write a short (~150 characters) description of this featured tag.
# description: >
#   This is a featured category, which have their own page.
#   Check out `_featured_tags/example.md` to learn how to create your own.

# (Optional) You can disable grouping posts by date.
# no_groups: true

# Exclude this example category from the sitemap.
# DON'T USE THIS SETTING IN YOUR CATEGORIES!
sitemap: false
---
I've worked on development of experimental quantum technologies in a few different subfields over the years. Here I provide a summary and some highlights, but if you just want the papers you can find them at my [Google Scholar page](https://scholar.google.com/citations?user=wsl7rBYAAAAJ). All of my peer-reviewed papers are available for free on the [arxiv](https://arxiv.org/).

## Superconducting quantum computers
I currently work at the [AWS Center for Quantum Computing](https://aws.amazon.com/blogs/quantum-computing/announcing-the-opening-of-the-aws-center-for-quantum-computing/), where we're building quantum computers out of superconducting circuits. I can't say much about this yet, but stay tuned!

## Trapped ions
![Full-width image](/assets/img/research/ions.png){: width="1200"}

False-color image of a chain of trapped ions from our lab. Each spot is an individual ion, glowing brightly under a resonant laser pulse. The apparent size and shape of the ions are actually just showing the limit of the imaging system; each blob is like a smeared glow that is much larger than the actual ion.  (Credit: Patrick Becker PhD thesis)
{:.figure}

From 2019-2022, I worked in the [trapped ion group of Chris Monroe](https://iontrap.duke.edu/) (then at University of Maryland, now at Duke). Our lab studied the interactions among a chain of trapped and suspended Ytterbium ions, held in a vacuum chamber. You can think of this as an extremely pristine testbed for understanding what collective behaviors are possible in a system of quantum particles.

### Time crystals

![Full-width image](/assets/img/research/an-infinite-looking-row-of-pink-and-blue-crystals.webp){: width="400"}

This is the image that Google Quantum made to represent their time crystal experiment. It at least gives some sense of the actual state of matter, which is like a crystal that has an associated oscillation (imagine that each crystal is a snapshot at a different moment in time). (Credit: Google Quantum AI)
{:.figure}

One of our studies involved the creation of [a type of time crystal](https://arxiv.org/abs/2102.01695). The phrase "time crystal" seems to really capture people's imaginations, and as a result this is probably the most widely-seen (and most cited) of the papers I've worked on.

To be honest, I think that the name "time crystal," although established in the literature, is actually a rather misleading way to describe the phenomenon that we and others have studied[^1]. There is a technical motivation for this name, based on the type of symmetry breaking that describes the properties of the quantum system that we created. For perspective, following this logic we should call a regular crystal, such as a crystal of salt, a "space crystal" since it has a regular structure in space. Likewise, a time crystal is, roughly, a material that features some kind of stable and spontaneous oscillation. A clearer name would perhaps be something like a "spontaneous oscillating state." That has much less of a mysterious sci-fi sound to it, but I think it actually gives a better sense of what was actually going on in the effect that we studied. We created an approximately isolated system with an oscillation that is stabilized by the interactions within the system, and we studied how the oscillations vary with respect to various control parameters like the initial energy. For a certain range of energies the oscillations are long-lived, while outside this range they melt away-- a type of non-equilibrium phase transition. The boundary energy agreed nicely with the theory developed by my collaborators.

## Ultracold atoms
From 2012-2019, I worked towards a PhD in the [research group of Brian DeMarco](https://research.physics.illinois.edu/demarco/) at the University of Illinois. Our group created artificial "materials" out of atoms (Potassium, in my particular case) suspended in a laser beam. The basic idea was similar to my trapped ion work: to create a near-perfect model quantum system and see what it could do.

For example, my capstone paper studied the impact of disorder on the mobility of the atoms. We found some counterintuitive results. For example, it is well-known that strong interactions can lock up particles in place, forming a state of matter called a "Mott insulator" that prevents them from easily moving. We found that adding disorder could disrupt this and restore motion- but only to a point. Strong disorder would itself also freeze the particles in place, causing an insulating transition. The details of how this interplay works out are still not very well understood, even in a simple system like ours.

![Full-width image](/assets/img/research/DoubDisorderLarge.png){: width="400"}

My attempt to make a graphic representing my thesis project. Laser beams (green and red) combine to form an environment for atoms that has a regular structure plus disorder. Depending on the details of this environment, the atoms (orange and blue) can be localized to single sites, perhaps in a pair, or can exist in delocalized "puddles".
{:.figure}

In science, as in many other endeavors, one often finds that the work that one is personally most proud of is not necessarily the work that has the largest impact. For me, this was one example. I thought and still think that this measurement suggests all sorts of interesting questions about disordered and strongly correlated states of matter, but so far no one has really followed it up.

## Entangled photons
In 2011-2012, I had two brief positions related to generating entangled pairs of photons. First, in a summer internship at the University of California, Berkeley, I helped to implement an undergraduate lab class module that allowed students to explore quantum entanglement, hands-on. I was supervised by Prof. Hartmut Haffner. Then, I worked in the [research group of Alex Ling](https://sites.google.com/site/phylej/) at the Centre for Quantum Technologies at the National University of Singapore. My project involved development of lightweight and rugged sources of entangled sources of photons that could be launched aboard a satellite. The idea is to be able to distribute pairs of entangled particles over as large of a distance as possible, to take advantage of certain quantum effects that can be used for communication and cryptography.

Towards the end of my tenure at CQT, I helped to author a [semi-popular article](https://pure.strath.ac.uk/ws/portalfiles/portal/64830445/Morong_etal_QO_2012_Quantum_optics_for_space.pdf) explaining our program. Although some parts of the writing betray my youthful inexperience, it still gives a nice flavor of the project.

[^1]: That said, the term "time crystal" was originally introduced by Frank Wilczek, an extremely influential physicist and Nobel prize winner. If you decide to side with him instead of me I won't take it personally.