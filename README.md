# Sufficient Projections

Flyxion, Independent Researcher. October 30, 2026.

This repository holds the LaTeX source of a twelve-page essay on when a compressed record remains adequate for judgments that have not yet been specified. The compiled essay is available as a PDF at [Sufficient Projections](https://standardgalactic.github.io/antivenom/economics/sufficient_projections.pdf). An audio overview, [Why Today's Summaries Fail Tomorrow](https://standardgalactic.github.io/antivenom/economics/player.html?track=3), is published alongside it.

## The question

A system that compresses, summarizes, or reformulates a record is usually judged by how well the reduced representation serves the questions asked at the time of reduction. The essay treats a different requirement: that the reduced representation remain adequate for the judgments generated when the governing policy is later revised.

## Results

The essay defines sufficiency of a projection relative to a class of admissible revisions and shows that it is characterized exactly by a verdict-equivalence relation on histories. Three consequences follow. The minimal cost of sufficiency is the number of verdict classes the revision class induces. A test collection certifies sufficiency for the class it was drawn from exactly when it induces the same verdict-equivalence relation, so the operative condition is the relation and not the size of the collection. And the failure modes of retention, formalization, and execution are logically independent of one another. A new policy can be admitted to the family a sufficient projection supports exactly when the projection's kernel lies within the policy's kernel.

The essay places the account among antecedents in statistics, automata theory, and databases, and then reads four recent results as instances of the same structure: semantic alignment of formal statements, thread-structured agent memory, layered misalignment monitoring, and agent-written infrastructure. It closes with practical consequences and a section on the limits of the account.

## Building

The essay is a single file, `sufficient_projections.tex`, with its bibliography included as a `thebibliography` environment, so no BibTeX run is needed. It uses the `article` class with amsmath, amssymb, amsthm, geometry, microtype, and hyperref. With a standard TeX Live installation, run

    pdflatex sufficient_projections.tex
    pdflatex sufficient_projections.tex

Two passes are needed to resolve cross-references.

## Status

This is a working draft, published as it is produced and revised in place. It is dedicated to the public domain.
