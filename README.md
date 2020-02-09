# A Hybrid Compact Neural Architecture for Visual Place Recognition

In this release, we provide an open source implementation of the FlyNet supervised learning experiments in [**A Hybrid Compact Neural Architecture for Visual Place Recognition**](https://doi.org/10.1109/LRA.2020.2967324), DOI [10.1109/LRA.2020.2967324](https://doi.org/10.1109/LRA.2020.2967324), accepted for publication in the IEEE Robotics and Automation Letters (RA-L) journal. Preprint version available at https://arxiv.org/abs/1910.06840.

Project page: https://mchancan.github.io/projects/

## Dataset

The dataset used to run this code can be downloaded from
[here](https://drive.google.com/open?id=1xrHKrHYgSqrMk9-XeC1qIe8UYDmOsgfd), which is a small subset of the Nordland dataset. However, this code can easily be adapted to run across other much larger datasets.

## Dependencies

This code was tested on [PyTorch](https://pytorch.org/) v1.0 and Python 3.6.

## Use FlyNet

We provide a demo of FlyNet on the Nordland dataset. After downloading the [dataset](https://drive.google.com/open?id=1xrHKrHYgSqrMk9-XeC1qIe8UYDmOsgfd), extract it into the `dataset/` directory and run:

	python main.py

## Sample results

![](results/demo_flynet_nordland.jpg)

## License

FlyNet itself is released under the MIT License (refer to the LICENSE file for details).

## Citation

If you find this project useful for your research, please use the following BibTeX entry.

	@article{chancan2020hybrid,
		author = {M. {Chanc\'an} and L. {Hernandez-Nunez} and A. {Narendra} and A. B. {Barron} and M. {Milford}},
		journal = {IEEE Robotics and Automation Letters},
		title = {A Hybrid Compact Neural Architecture for Visual Place Recognition},
		year = {2020},
		volume = {5},
		number = {2},
		pages = {993--1000},
		keywords = {Biomimetics;localization;visual-based navigation},
		doi = {10.1109/LRA.2020.2967324},
		ISSN = {2377-3774},
		month = {April}
	}
