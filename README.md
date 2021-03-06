# MIA_ML

### Implementation of Shokri et al(2016) [Membership Inference Attacks Against Machine Learning Models](https://arxiv.org/pdf/1610.05820.pdf)

### How to run

1. (Optional) Customize train / inference configurations in config.yaml

2. (Optional) `python train_target.py`: Train the victim model which is the target of the extraction.

3. `python train_shadow.py`: Corresponds to Diagram 1-1 ~ Diagram 2-2 illustrated below.

4. `python train_attack.py`: Corresponds to Diagram 2-3 ~ Diagram 3 illustrated below.

5. `python inference_attack.py`: Corresponds to Diagram 4 illustrated below.

### Paper's Methodology in Diagrams

![Page2](./assets/README/Page2.jpg)

![Page3](./assets/README/Page3.jpg)

![Page4](./assets/README/Page4.jpg)

![Page5](./assets/README/Page5.jpg)

![Page6](./assets/README/Page6.jpg)

![Page7](./assets/README/Page7.jpg)

![Page8](./assets/README/Page8.jpg)

![Page9](./assets/README/Page9.jpg)

![Page10](./assets/README/Page10.jpg)

