*Ce projet explore une méthode de reconstruction d’un signal supposé constant par morceaux à partir d’observations bruitées. L’objectif est de retrouver la forme originale du signal en éliminant le bruit tout en identifiant les points de rupture. Ce problème est fréquent en traitement du signal, notamment dans l’analyse de séries temporelles.*

# Reconstruction dun signal constant par morceaux à partir de données bruitées

Ce projet d’optimisation porte sur la reconstruction d’un signal constant par morceaux à partir d’observations bruitées, problématique fréquente en traitement du signal, en analyse d’images et en compression de données. Le signal initial, non directement observable, est perturbé par un bruit gaussien centré, et l’objectif est de retrouver une estimation fidèle de ce signal en exploitant sa régularité structurelle. 

Pour cela, plusieurs formulations du problème sont étudiées, basées sur la minimisation de fonctions objectives mêlant fidélité aux données et régularisation par des différences finies. Trois approches sont mises en œuvre : un algorithme de gradient à pas fixe, un algorithme à pas décroissant, et une méthode duale avec projection sur la boule uniforme (associée à la norme infini). 

Ces méthodes sont comparées expérimentalement selon leur précision, leur rapidité d’exécution et leur capacité à préserver les ruptures du signal. Les résultats montrent que la méthode duale offre la meilleure reconstruction des discontinuités, avec une excellente efficacité computationnelle, tandis que les approches de gradient direct restent intéressantes pour leur simplicité d’implémentation.

# Reconstruction of a piecewise constant function from noisy data
This optimization project concerns the reconstruction of a piecewise constant signal from noisy observations, a frequent problem in signal processing, image analysis and data compression. The initial signal, not directly observable, is perturbed by centered Gaussian noise, and the aim is to recover a faithful estimate of this signal by exploiting its structural regularity.

To achieve this, several formulations of the problem are studied, based on the minimization of objective functions combining data fidelity and finite-difference regularization. Three approaches are implemented: a fixed-step gradient algorithm, a decreasing-step algorithm, and a dual method with projection onto the uniform ball (associated with the infinite norm). 

These methods are compared experimentally according to their accuracy, speed of execution and ability to preserve signal breaks. The results show that the dual method offers the best reconstruction of discontinuities, with excellent computational efficiency, while direct gradient approaches remain interesting for their simplicity of implementation.
