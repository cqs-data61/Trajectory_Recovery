# Trajectory Recovery

This repository contains an implementation and enhancement of the trajectory recovery algorithm proposed by Xu et al. in
"Trajectory Recovery From Ash: User Privacy Is NOT Preserved in Aggregated Mobility Data" (2017) [1].
It is supplied as a Python module and as a Jupyter Notebook with detailed step-by-step explanations.

We evaluate the algorithm on two open-source datasets: GeoLife [2] and Porto Taxi [3].

- `data/` contains all the preprocessed datasets.
- `results-a/` contains plotted results and pickle files of the results for the re-implementation as presented in [1]. It also contains plots of all the predicted trajectories against the true ones.
- `results-b/` contains all the content as above for our enhanced version. It also contains comparative plots of various metrics.
- `algorithm_walkthrough.ipynb` is the Jupyter Notebook explaining the algorithm.
- `documentation.pdf` is the documentation for the Python module.
- `trajectory_recovery.py` is the Python module.

References:
- [1] F. Xu, Z. Tu, Y. Li, P. Zhang, X. Fu, and D. Jin, “Trajectory recovery from ash: User privacy is not preserved in aggregated mobility data,” in Proceedings of the 26th International Conference on World Wide Web, ser. WWW ’17. International World Wide Web Conferences Steering Committee, Apr. 2017. [Online]. Available: http://dx.doi.org/10.1145/3038912.3052620
- [2] Y. Zheng, H. Fu, X. Xie, W.-Y. Ma, and Q. Li, Geolife GPS trajectory dataset - User Guide, geolife gps trajectories 1.1 ed., July 2011. [Online]. Available: https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/
- [3] M. O’Connell, L. Moreira-Matias, and W. Kan, “Ecml/pkdd 15: Taxi trajectory prediction (i),” 2015. [Online]. Available: https://kaggle.com/competitions/pkdd-15-predict-taxi-service-trajectory-i

---

This project is licensed under the MIT License - see the [LICENSE](https://github.com/ndsi6382/Trajectory_Recovery/blob/main/LICENSE) file for details.
