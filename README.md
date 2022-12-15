## Final report on the Sherman-Morrison-Woodbury kernels, implemented in QMCkl

    This work has been executed in the context of the TREX-CoE. To that end we aim to address the
    following goals. To
      - solve a numerical problem that exists in the Sherman-Morrison method, as implemented and
        used extensively in the QMC=Chem software package,
      - extend and generalise this method to include higher-rank cases (Woodbury matrix identity),
      - implement these methods and optimise them to run efficiently on high performance computing
        (HPC) architectures.

    QMC=Chem is used as a test case to address the numerical problems in its implementation of
    the Sherman-Morrison method. However, it is often used in other Quantum Monte Carlo (QMC)
    applications as well. Indeed, the method itself is more general and can be employed in many
    other application domains. Because of this, these algorithms have been made available to the
    public in the form of computational kernels inside the Quantum Monte Carlo kernel
    library (QMCkl).
          
    Finally, we include performance- and numerical benchmarks to demonstrate that the numerical
    issues that have been identified in QMC=Chem have been resolved and the stated objectives
    have been met.
    
 [Read the report: 'SMWB_report.pdf'](SMWB_report.pdf)
