# yiota0707.github.io-dissertation
# Assortative Matching and the Emergence of Cooperation
# Link : https://yiota0707.github.io/PanayiotaPapafiggouDISSERTATIONWEBSITE/
Interactive visualisation developed as supporting material for my MSc Computer Science dissertation at the University of Warwick.

The website illustrates the partner-rematching mechanisms used in the dissertation's Baseline and Hybrid reinforcement-learning models for repeated Prisoner's Dilemma interactions.

## Interactive Visualisation

The simulation displays the two models side by side:

### Baseline Model
Agents interact with their current partners and then all partnerships enter the rematching process. The assortativity parameter \(m\) determines whether rematching is random or based on agents' previous cooperative or defective behaviour.

### Hybrid Model
Agents can make learned stay/switch partner decisions. A partnership is retained only when both agents choose to stay; otherwise, both agents enter the rematching pool. Assortative rematching is then applied only to agents whose partnerships were dissolved.

## Assortativity

The slider allows the assortativity parameter \(m\) to be varied between 0 and 1.

- `m = 0` represents random rematching.
- `m = 1` represents assortative rematching based on previous cooperative or defective behaviour.
- Intermediate values represent a mixture of random and assortative rematching.

## Simulation Stages

The visualisation cycles through four stages:

1. Agents interact with their current partners.
2. Partnership continuation or switching is determined.
3. Agents requiring new partners enter the rematching process.
4. New partnerships are formed.

Agents labelled `C` previously cooperated, while agents labelled `D` previously defected.

The Run, Pause and Reset controls can be used to inspect the rematching process interactively.

## Purpose

This website is an explanatory visualisation of the mechanisms studied in the dissertation. It is intended to help illustrate the conceptual difference between the Baseline and Hybrid models and the role of assortativity in partner rematching.

It is not the computational implementation used to generate the dissertation's experimental results. The full reinforcement-learning models, experiment scripts and statistical analysis code are provided separately in the dissertation code repository.

## Files

- `index.html` — structure and content of the visualisation.
- `style.css` — layout, responsive design and visual styling.
- `script.js` — interactive simulation, rematching logic and user controls.

## Dissertation

**Assortative Matching and the Emergence of Cooperation**

MSc Computer Science  
University of Warwick
