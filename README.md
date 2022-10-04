# StableFusion
A simple yet comprehensive UI for Stable Diffusion.

## Project Features

- [x] Windows/WPF-based
- [x] Uses [the official repo](https://github.com/CompVis/stable-diffusion) for a base
- [ ] Simple and easy-to-use; also covers common additional niceties and features
- [ ] Auto-install (including prerequisites: python, official repo, weights)
- [x] Efficient prompt/image/configuration/other metadata saving and retrieval mechanism
- [x] Easily enable or disable watermarking and safety filter
- [x] Adjust output resolution
- [ ] Prompt history + prompt auto-complete
- [x] Random or fixed seed, as well as random prompt + 'Randomize All Settings' feature
- [x] Gallery, Favorites + intuitive result rating system (helps hone prompting skills/makes best results easily find)
- [ ] Image-to-image features that help avoid frustration when creating results from an image input
- [ ] Intuitive inpainting interface
- [ ] Hassle-free masking system for image-to-image/outpainting
- [x] Guidance scale/temperature-over-steps staggered gradient feature for unique impact on inference
- [x] Multiple prompts (sharing a weight of 1.0 unless otherwise specified)
- [ ] Prompt auto-weight-distribution (intelligent and fine-tuned emphasis of words and phrases)
- [ ] Result publishing
- [ ] Infinite samples by handling seed incrementation ourselves
- [ ] Node/scripting system to help better automate repetitive tasks

**Additional goals**
- [x] Language-model (T5/Parrot)-based prompt augmentation (paraphrased variations of main prompt to widen semantic coverage - given much less weight, then merged/added with the learned conditioning for main prompt)
- [ ] Improved local detail, coherence, and accuracy, using native (SD-based) super-resolution
- [ ] Extend prompt length by implementing a multiple-pass (image-to-image/overlay/inpainting) system
- [ ] Artist name and examples gallery
- [ ] Generate variations of an input image, with or without a prompt
- [ ] Custom dataset training (low memory)
- [ ] UI-templating (enable user to create their OWN UI/layout based on a basic template language), rewire UI elements to do different things (e.g. add API for a different site to publish results)

**Disclaimer(s)**
###### Made for fun. No feature is based on any other work specifically, nor intended to infringe on any ideas that have already been implemented (as almost all common sense ideas have been) - this, if it ever happens, is entirely unintentional. VERY MUCH a work in progress. 
