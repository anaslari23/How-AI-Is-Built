# How AI Is Built

An interactive guide to how AI models are built. Start with randomness and a single neuron, then follow the full lifecycle of a language model: data, tokenization, architecture, pre-training, fine-tuning, alignment, evaluation and deployment. Change a setting and watch the simulation respond.

It is one HTML file with no build step, made for anyone curious about AI, from first-time learners to engineers.

## What is inside

**Learning path**
- **Foundations:** randomness (random walks, diffusion, weight initialization, accept-reject, LLM sampling, noise) and neural networks (a neuron, the perceptron, a small network that learns XOR).
- **The model lifecycle, in 8 steps:** data curation, tokenization, architecture, pre-training, SFT and LoRA, alignment, evaluation, deployment.
- **Frontier and Sim Lab:** mixture of experts, interpretability, distillation and merging, retrieval, FlashAttention, diffusion, and the production data flywheel.
- **Map, glossary and quiz:** a full system map, about 23 terms and a 12-question quiz.

**How it teaches**
- Guess first, then run the demo, then check your guess.
- Every control shows what changed, and a finished training run stays on the chart so you can compare it with the next one.
- Guided mode keeps each step short, and Full Stack mode adds the engineering detail.
- Progress is saved in your browser. Nothing is sent anywhere.

**Interface**
- 3D scenes (three.js) and live charts (Chart.js).
- Light and dark OLED themes.
- Works on phones, tablets and desktops.

## Run it

Open `interactive_ai_model_building_roadmap_simulator.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8765
```

Then visit http://127.0.0.1:8765/interactive_ai_model_building_roadmap_simulator.html

An internet connection is needed for the 3D and chart libraries and for fonts. The rest still works without them.

## Built with

Plain HTML, CSS and JavaScript, [Tailwind CSS](https://tailwindcss.com) (compiled and inlined), [three.js](https://threejs.org) and [Chart.js](https://www.chartjs.org).

## Credits

Created by Anas Lari. Randomness concepts follow [The Nature of Code](https://natureofcode.com/random/) by Daniel Shiffman.
