# Useful resources related to visual SLAM and associated tasks
## Datasets
### Classic
|  | Name | Ground Truth | Comments | Paper|
|--|:------:|:----:|:-------:|:----------:|
| 1. | [KITTI dataset](http://www.cvlibs.net/datasets/kitti/) | sequences 00 - 10 | driving sequence | Geiger, Andreas, et al. "Vision meets robotics: The kitti dataset." (2013) [pdf](https://journals.sagepub.com/doi/pdf/10.1177/0278364913491297) [bibtex](https://scholar.googleusercontent.com/scholar.bib?q=info:fE-BSqAqlDkJ:scholar.google.com/&output=citation&scisdr=CgWvipfOEKPs96GKM38:AAGBfm0AAAAAYCGMK3-tcLZbX-i8VoPH30IC_OVNnF8a&scisig=AAGBfm0AAAAAYCGMKxw1hoEYO0ir6nXQC2Tlg4ZZ9YDS&scisf=4&ct=citation&cd=-1&hl=en)|
| 2. | [EuRoC dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets) | + | UAV, shaky and aggressive motion, ground truth needs interpolation for image timestamps | Burri, Michael, et al. "The EuRoC micro aerial vehicle datasets."(2016) [pdf](https://www.researchgate.net/profile/Michael-Burri/publication/291954561_The_EuRoC_micro_aerial_vehicle_datasets/links/56af0c6008ae19a38516937c/The-EuRoC-micro-aerial-vehicle-datasets.pdf) [bibtex](https://scholar.googleusercontent.com/scholar.bib?q=info:bNHy1pLIzEkJ:scholar.google.com/&output=citation&scisdr=CgWvipfOEKPs96GNSy0:AAGBfm0AAAAAYCGLUy3i9m_vri9ljuG-897bnmuQW-yU&scisig=AAGBfm0AAAAAYCGLUy8bMxjvX_RT-Q7GwAGH3q8JXHyu&scisf=4&ct=citation&cd=-1&hl=en)|
| 3. | [Mono TUM](https://vision.in.tum.de/data/datasets/mono-dataset) | missing entries, NaNs | handheld device, photometric calibration | Engel, Jakob, et al. "A photometrically calibrated benchmark for monocular visual odometry." (2016) [pdf](https://vision.in.tum.de/_media/spezial/bib/engel2016monodataset.pdf) [bibtex](https://vision.in.tum.de/data/datasets/mono-dataset?key=engel2016monodataset) |
### Loop Closure and Relocalization
|  | Name | Ground Truth | Comments | Paper|
|--|:------:|:----:|:-------:|:----------:|
| 1. | [Oxford RobotCar dataset](https://robotcar-dataset.robots.ox.ac.uk/) | + | same route recorded in various conditions, many dynamic objects | Maddern, Will, et al. "1 year, 1000 km: The Oxford RobotCar dataset." (2017) [pdf](https://ora.ox.ac.uk/objects/uuid:c5266bad-e0f8-49f1-918e-1602ef935990/download_file?file_format=pdf&safe_filename=1%2BYear%252C%2B1000km-%2BThe%2BOxford%2BRobotCar%2BDataset.pdf&type_of_work=Journal+article) [bibtex](https://scholar.googleusercontent.com/scholar.bib?q=info:jhUNdtsRXAAJ:scholar.google.com/&output=citation&scisdr=CgWvipfOEKPs96GLmLU:AAGBfm0AAAAAYCGNgLW7nbnaUCMNtAMtCh9FeelHAtoU&scisig=AAGBfm0AAAAAYCGNgEpGLnnN8RVNjyEnLVM34_4dt3j5&scisf=4&ct=citation&cd=-1&hl=en)|
| 2. | [Newer College dataset](https://ori-drs.github.io/newer-college-dataset/) | + | several loops, outdoor environment, handheld device, some aggresive motion | Ramezani, Milad, et al. "The Newer College Dataset: Handheld LiDAR, inertial and vision with ground truth." (2020) [pdf](https://arxiv.org/pdf/2003.05691) [bibtex](https://scholar.googleusercontent.com/scholar.bib?q=info:Ocxd02TCUjYJ:scholar.google.com/&output=citation&scisdr=CgWvipfOEKPs96GIeU0:AAGBfm0AAAAAYCGOYU3sqJCYQEoXFMwEwVyrm59FYRV6&scisig=AAGBfm0AAAAAYCGOYVkLWBStCbDZwcxTN3HdyVhG1iK3&scisf=4&ct=citation&cd=-1&hl=en)|
