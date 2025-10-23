# Floquet_MHD_ECS_2D
This is meant to be a submodule of ECS_MHD_2D. I plan to store the Floquet analysis (eigenvalues and eigenvectors) of solutions here.

My goal is to replicate the file structure of the solutions/ directory on the parent repository in an obvious way. Each file will contain a partial Real Schur decomposition of the monodromy matrix M (n-by-n) described by the real matrices R (k-by-k)  and Q (n-by-k) such that MQ = QR. Here n is the dimension of the system and k is the number of vectors I bothered to converge.

The eigenvalues of R are eigenvalues of M, and eigenvectors of R multiplied by Q are eigenvectors of M.