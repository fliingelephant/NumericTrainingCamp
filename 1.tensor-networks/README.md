# Tensor Networks (Quantum many-body)

## Contents
1. Ground state finding
   1. DMRG ([Julia](https://github.com/CodingThrust/SimpleTDVP.jl))
   2. Corner transfer matrix renormalization group (CTMRG) ([Julia](https://github.com/under-Peter/TensorNetworkAD.jl), [Python](https://github.com/TensorBFS/dTRG))
   3. variational uniform Matrix Product State algorithm (VUMPS) ([Julia](https://github.com/Jutho/TNSchool2018))
2. Finite temperature methods
   1. Continuous matrix product operator (CMPO) ([Python](https://github.com/TensorBFS/cMPO))
3. Time evolution
   1. Time-evolving block decimation (TEBD) ([Python](https://github.com/tenpy/tenpy))
   2. Time-dependent variational principle (TDVP) ([Julia](https://github.com/Jutho/TNSchool2018))
4. Classical tensor networks
   1. Tensor renormalization group (TRG) ([Julia](https://github.com/under-Peter/TensorNetworkAD.jl), [Python](https://github.com/TensorBFS/dTRG))

## Reading
- Review: A practical introduction to tensor networks: Matrix product states and projected entangled pair states[^Orus2014].
- Review: The density-matrix renormalization group in the age of matrix product states[^Schollwock2011].
- Review: Tangent-space methods for uniform matrix product states[^Vanderstraeten2019].
- Website: [Tensor Network website](https://tensornetwork.org/).
- Book: Density Matrix and Tensor Network Renormalization[^Tao2023].

## Researchers in the field
- [Jutho Haegeman](https://scholar.google.com/citations?hl=zh-CN&user=yfHe3OAAAAAJ) - Quantum Many Body Physics, Tensor Network Methods
- [Ignacio Cirac](https://scholar.google.com/citations?hl=zh-CN&user=gPGlTbgAAAAJ) - quantum optics, quantum information, many-body systems
- [Frank Pollmann](https://scholar.google.com/citations?hl=zh-CN&user=hlf61gwAAAAJ) - Condensed Matter Theory
- [Edwin Miles Stoudenmire](https://scholar.google.com/citations?hl=zh-CN&user=DLFxevAAAAAJ) - Condensed Matter Theory, Computational Physics, Tensor Network Methods, DMRG
- [Shuo Yang](https://scholar.google.com/citations?hl=zh-CN&user=nemjDVIAAAAJ) - condensed matter theory, quantum physics, tensor networks
- [Hiroshi Shinaoka](https://scholar.google.com/citations?hl=zh-CN&user=NT-EiksAAAAJ) - Condensed matter physics, computational physics, strongly correlated electrons
- [Steven White](https://scholar.google.com/citations?user=tXebds4AAAAJ&hl=zh-CN&oi=ao), DMRG, condensed matter physics
- [Frank Verstraete](https://scholar.google.com/citations?hl=zh-CN&user=wBrDPIEAAAAJ), Quantum Physics, Entanglement, Many-Body Physics, Quantum Computation, Tensor Networks
- [Norbert Schuch](https://scholar.google.com/citations?user=ZHmDt48AAAAJ&hl=zh-CN), Quantum Many-Body Physics, Quantum Information Theory

## Projects

* Reproduce: Isometric Tensor Network States in Two Dimensions[^Zaletel2019].
* Reproduce: Continuous matrix product operator approach to finite temperature quantum states[^Tang2020].
* Reproduce: Lower Bounds on Ground-State Energies of Local Hamiltonians through the Renormalization Group[^Kull2024].
* Reproduce: Differentiable Programming Tensor Networks[^Liao2019].
* Reproduce: Variational optimization algorithms for uniform matrix product states[^Zauner2017]

## References
[^Zaletel2019]: Zaletel, M.P., Pollmann, F., 2019. Isometric Tensor Network States in Two Dimensions.
[^Huang2018]: Huang, R.-Z., Liao, H.-J., Liu, Z.-Y., Xie, H.-D., Xie, Z.-Y., Zhao, H.-H., Chen, J., Xiang, T., 2018. A generalized Lanczos method for systematic optimization of tensor network states. Chinese Phys. B 27, 070501. https://doi.org/10.1088/1674-1056/27/7/070501
[^Schollwock2011]: Schollwöck, U., 2011. Schollwöck, U. (2011). The density-matrix renormalization group in the age of matrix product states. Annals of Physics 326, 96–192. https://doi.org/10.1016/j.aop.2010.09.012
[^Vanderstraeten2019]: Vanderstraeten, L., Haegeman, J., Verstraete, F., 2019. Tangent-space methods for uniform matrix product states. SciPost Physics Lecture Notes 7, 1–77. https://doi.org/10.21468/scipostphyslectnotes.7
[^Orus2014]: Orús, R., 2014. A practical introduction to tensor networks: Matrix product states and projected entangled pair states. Annals of Physics 349, 117–158. https://doi.org/10.1016/j.aop.2014.06.013
[^Tao2023]: Xiang, Tao. Density Matrix and Tensor Network Renormalization. Cambridge University Press, 2023.
[^Hubig2017]: Hubig, C., McCulloch, I.P., Schollwöck, U., 2017. Generic Construction of Efficient Matrix Product Operators. Phys. Rev. B 95, 035129. https://doi.org/10.1103/PhysRevB.95.035129
[^Xu2024]: Xu, Y., Hasik, J., Ponsioen, B., Nevidomskyy, A.H., 2024. Simulating Spin Dynamics of Supersolid States in a Quantum Ising Magnet. https://doi.org/10.48550/arXiv.2405.05151
[^Kull2024]: Kull, I., Schuch, N., Dive, B., Navascués, M., 2024. Lower Bounds on Ground-State Energies of Local Hamiltonians through the Renormalization Group. Phys. Rev. X 14, 021008. https://doi.org/10.1103/PhysRevX.14.021008
[^Liao2019]: Liao, H., Liu, J., Wang, L., Xiang, T., 2019. Differentiable Programming Tensor Networks. Physical Review X 9, 31041. https://doi.org/10.1103/PhysRevX.9.031041
[^Zauner2017]: Zauner-Stauber, V., Vanderstraeten, L., Fishman, M.T., Verstraete, F., Haegeman, J., 2017. Variational optimization algorithms for uniform matrix product states. npj Quantum Information 6, 1–32. https://doi.org/10.1103/PhysRevB.97.045145
[^Tang2020]: Tang, W., Tu, H.-H., Wang, L., 2020. Continuous matrix product operator approach to finite temperature quantum states. https://doi.org/10.1103/PhysRevLett.125.170604