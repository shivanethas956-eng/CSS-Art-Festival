CSS Art Festival 🎨

A pure HTML & CSS mascot gallery, hand-coded without any images, SVGs, or background-image URLs. Every character — Pikachu, Mario, Octocat, and the Among Us Crewmate — is built entirely from <div> and <span> elements, shaped using border-radius, box-shadow, transform, and position: absolute.


📋 Challenge Requirements

RequirementStatusOnly HTML & CSS✅Only div / span elements✅border-radius, box-shadow, transform, absolute positioning✅No <img> tags✅No SVGs✅No background-image URLs✅Hand-coded (no art generators)✅

🖼️ Characters Included


Pikachu — Pokémon mascot, featuring layered ears, a lightning-bolt tail built with clip-path, and shaded fur via inset box-shadow.
Mario — Nintendo mascot, with a cap and "M" badge, mustache, overalls, and gloves.
Octocat — GitHub's mascot, combining cat ears with octopus tentacle legs and rounded pupils.
Crewmate — Among Us mascot, a capsule-shaped body with a reflective visor and backpack.


🛠️ Techniques Used


border-radius (including elliptical x% y% values) to sculpt organic, non-rectangular shapes from plain divs
box-shadow (mostly inset) for two-tone shading, giving each shape a sense of light and depth without gradients or images
clip-path: polygon() for angular shapes like Pikachu's tail and Octocat's ears
transform: rotate() / scaleX() / translate() to angle limbs, mirror ears, and center elements
position: absolute layering within a position: relative "stage" to stack every body part precisely
CSS custom properties (:root variables) for a consistent color palette across all four characters
A responsive CSS grid gallery layout with a shared "stage" background (sky gradient, clouds, ground) for visual consistency


📁 Project Structure

├── index.html   # All markup, styles, and characters in a single file
└── README.md    # This file

🚀 Running Locally

No build tools or dependencies required — it's a single static HTML file.

bashgit clone <your-repo-url>
cd css-art-festival
open index.html   # or double-clic
