# Assessing Robustness of Driving Corridors According to Temporal Logic Specifications

## Bewertung der Robustheit von Fahrkorridoren anhand von Spezifikationen in temporaler Logik

### Abstract (English)
This thesis tackles the problem of assessing the robustness of set-based driving corridors according to Signal Temporal Logic (STL) specifications. Since driving corridors can represent specific maneuvers, a quantitative robustness degree can serve as a measure to rank different maneuvers prior to planning. To this end, we propose novel robustness measurements to quantify the degree of adherence to a given specification. We first develop an algorithmic framework for representing STL formalisms within the domain in which driving corridors are defined. This geometric representation, coupled with the proposed robustness measurements, captures intricate geometric relationships between the reachable states of the system and the representation of a specification. In contrast to previous methods that simplify geometries by representing a specification or the reachable sets as single points, or disregarding their full geometric intricacies, our robustness measurements consider the complete geometry of the reachable sets and the representation of the specification. Within this work, three measures are investigated: the first assesses geometric displacement, the second introduces a weighted perimeter calculation based on the distances between geometries, and the third refines this calculation to consider only lines relevant to specification adherence or violation. Our numerical experiments on CommonRoad scenarios demonstrate that the proposed robustness measures preserve soundness and monotonicity. To combine robustness scores along longitudinal and lateral dimensions across all driving corridors, we formulate a joint optimization problem for ranking corridors. We further evaluate the computational efficiency of our approach by varying the considered time horizon and complexity of the specifications.

### Abstract (German)
Diese Arbeit befasst sich mit dem Problem der Bewertung der Robustheit von setzbasierten Fahrkorridoren gemäß den Spezifikationen der Signal Temporal Logic (STL). Da Fahrkorridore spezifische Manöver darstellen können, kann ein quantitativer Robustheitsgrad als Maß dienen, um verschiedene Manöver vor der Planung zu bewerten. Zu diesem Zweck schlagen wir neuartige Robustheitsmessungen vor, um den Grad der Einhaltung einer bestimmten Spezifikation zu quantifizieren. Zunächst entwickeln wir einen algorithmischen Rahmen für die Darstellung von STL-Formalisierungen innerhalb des Bereichs, in dem Fahrkorridore definiert sind. Diese geometrische Darstellung, kombiniert mit den vorgeschlagenen Robustheitsmessungen, erfasst komplexe geometrische Beziehungen zwischen den erreichbaren Zuständen des Systems und der Darstellung einer Spezifikation. Im Gegensatz zu früheren Methoden, die Geometrien vereinfachen, indem sie eine Spezifikation oder die erreichbaren Mengen als einzelne Punkte darstellen oder ihre gesamten geometrischen Feinheiten ignorieren, berücksichtigen unsere Robustheitsmessungen die vollständige Geometrie der erreichbaren Mengen und die Darstellung der Spezifikation. In dieser Arbeit werden drei Maße untersucht: das erste bewertet die geometrische Verschiebung, das zweite führt eine gewichtete Umfangsberechnung basierend auf den Abständen zwischen den Geometrien ein, und das dritte verfeinert diese Berechnung, um nur Linien zu berücksichtigen, die für die Einhaltung oder Verletzung der Spezifikation relevant sind. Unsere numerischen Experimente an CommonRoad-Szenarien zeigen, dass die vorgeschlagenen Robustheitsmessungen Schallheit und Monotonie bewahren. Um Robustheitswerte entlang der longitudinalen und lateralen Dimensionen über alle Fahrkorridore zu kombinieren, formulieren wir ein gemeinsames Optimierungsproblem zur Bewertung der Korridore. Wir bewerten außerdem die rechnerische Effizienz unseres Ansatzes, indem wir den betrachteten Zeithorizont und die Komplexität der Spezifikationen variieren.

## Overview
This thesis is structured as follows:

1. **Introduction**: Formulation of the problem, review of related work, and outline of contributions.
2. **Preliminaries**: Introduction to the theoretical foundations including reachability analysis and Signal Temporal Logic (STL).
3. **Algorithmic Framework**: Detailed description of the framework for representing and evaluating STL specifications.
4. **Predicates**: Definition and discussion of various predicates used in the context of the thesis.
5. **Robustness Measurement**: Introduction of novel robustness measures and their mathematical formulation.
6. **Experimental Results**: Presentation of numerical experiments and their results, including the evaluation of the proposed measures.
7. **Conclusions**: Summary of findings and suggestions for future research directions.

## Citation
If you find this work useful for your research, please cite it using the following BibTeX entry:

```bibtex
@mastersthesis{Nexhipi2023,
  author       = {Evald Nexhipi},
  title        = {Assessing Robustness of Driving Corridors According to Temporal Logic Specifications},
  school       = {Technical University of Munich},
  year         = {2023},
  address      = {Munich, Germany},
  month        = {October},
}

## Copyright
Copyright © 2023 Evald Nexhipi 
