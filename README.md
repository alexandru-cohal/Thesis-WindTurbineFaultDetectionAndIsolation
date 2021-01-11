# Thesis-WindTurbineFaultDetectionAndIsolation
### The thesis developed within the *"Automatic Control"* Bachelor

- **Date**: July 2015
- **Purpose**: The purpose of my Bachelor's thesis was to develop several methods for the detection and the isolation of different types of faults which can affect a wind turbine. A benchmark model implemented in MATLAB and Simulink of a real wind turbine (Odgaard, et al., 2009) is used to test these fault detection and isolation methods. The developed methods are implemented as Simulink blocks, allowing an online detection and isolation of the considered faults.
- **Programming Language**: MATLAB & Simulink
- **Team**: Individual project
- **Approach**:
  - The faults considered in this thesis affect some of the sensors (i.e. fixed value fault, gain factor fault) and the actuators (i.e. offset value fault) of the wind turbine
  - The fault detection and isolation methods used can be divided into two categories:
    - Modelbased methods (designing a state-space estimator is considered)
    - Methods based on the wind turbine's signals analysis
      - In frequency domain (Fast Fourier Transform)
      - In time domain (mean, standard deviation, autocorrelation)
  - For more information about the solution, implementation, results, conclusions and improvements see [this document](documentation/ThesisDocumentation-WindTurbineFaultDetectionAndIsolation.pdf) (in Romanian language), [this presentation](documentation/ThesisPresentation-WindTurbineFaultDetectionAndIsolation.pdf) (in Romanian language) and [this paper](documentation/PaperCEAI2017-FaultDetectionAndIsolationOfAWindTurbine.pdf) published in the *Journal of Control Engineering and Applied Informatics* Vol.19, No.3, 2017
- **References**:
  - Odgaard, P. F., Stoustrup, J. and Kinnaert, M., 2009. Fault Tolerant Control of Wind Turbines – a benchmark model. Proceedings of the 7th IFAC Symposium on Fault Detection, Supervision and Safety of Technical Processes, pp. 155-160. 
