<head>
  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
  <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
      tex2jax: {
      skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
      inlineMath: [['$','$']]
      }
    });
  </script>
</head>

- [What is Distributed Optical Fibre Sensors(DOFSs)?](#what-is-distributed-optical-fibre-sensorsdofss)
- [What is the key aspects of the performance of DOFSs?](#what-is-the-key-aspects-of-the-performance-of-dofss)


## What is Distributed Optical Fibre Sensors(DOFSs)?

 They determine spatial distribution of the measurands along the fibre often many kilometres long.


## What is the key aspects of the performance of DOFSs?

 1. **the measurand resolution**

     The ability for the sensor to distinguish small changes in the value of the quantity that is measured. In general, it's a function of location because the signal is increasingly attenuated with increasing distance.

 2. **the spatial resolution**

     The ability to distinguish the value of the measurand at close locations.

      The spatial resolution $\delta z$ is usually defined as the distance over which the sensor output corresponding to an abrupt transition is spread, estimated between 10% and 90% points on the transition.

      <div align="center"><img src="./Pic/1.1.png" width="400"></div>


     When the width of the measurand is smaller or equal to the width of spatial resolution, the value measured will be lower than actual value as the picture.

      <div align="center"><img src="./Pic/1.2.png" width="400"></div>

 3. **sampling resolution**

     1. It's the fiber distance of the samples of analogue signals.

     2. Ideally it is smaller than spatial resolution to reproduce the information available from the receiver. As a rule of thumb, it is recommended to ensure that the *sampling resolution is at least two times finer than the spatial resolution* – this ensures that the profile can be reconstructed and interpolated to an accuracy that is limited only by the spatial resolution.

     3. It's the inverse of the sampling frequency.

 4. **the range**

     The maximum length of the fiber that the sensor can measure.

     This value will also dictate the maximum pulse repetition rate. Because we must wait until the backscatter returned to the launch end from the far end.



 5. **the measurement time to achieve the stated measurement resolution**

