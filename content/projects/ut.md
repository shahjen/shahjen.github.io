---
title: "UT Austin" # in any language you want
description: "Projects at UT Austin 2023 - 2025"
draft: False
weight: 102
summary: "2023 - 2025"
---

I am currently pursuing a Master of Science degree in the University of Texas at Austin. Some projects that I have worked on/am currently working on here:

- **DCE MSOT Image Reconstruction Project** : I am set to work on this project with Prof Umberto Villa in Spring 2024. More information about this project can be found [here.]({{< relref path="./irp.md" >}})
- **2D Finite Difference Solver** : In a team of 3, I wrote a 2D finite difference solver in C++. We used both GSL and PETSc to implement this. Specifically:
    - We created 1D and 2D laplacian matrices for 2nd and 4th order approximations
    - Then implemented both Gauss-Sidel and Jacobi iterations in GSL along with sparse matrix optimisations
    - Plotted and compared the solution to our analystical solution (we chose this to be a sine wave)
    - Compared our convergence time with PETSc's inbuilt GMRES solver
    
    Some other features of this project:
    - We used libGRVY for input and output
    - We hosted this on our team github repo with continuous integration
    - The environment to run the code was also containerized and pushed it to dockerhub
    - Wrote unit tests using bats framework and added them to the CI

- **Deep learning for universal linear embeddings of nonlinear dynamics**: In a team of 3, we tried to learn the dynamics of chaotic systems by learning their Koopman modes. To summarize:
    - We used an encoder to map the dynamics to an infinite dimensional linear space, and then used a decoder to get back to the finite dimensional settting.
    - We closely followed [Lusch et al 2018](https://www.nature.com/articles/s41467-018-07210-0) for inspiration and for the starting point to our neural network architecture.
    - We validated results in the paper
    - We extended the model to try and learn the dynamics of a chaotic Lorenz-96 system
    - The code can be found on GitHub: [https://github.com/shahjen/DeepKoopmanLorenz96](https://github.com/shahjen/DeepKoopmanLorenz96) 