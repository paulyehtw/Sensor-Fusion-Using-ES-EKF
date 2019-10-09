# Sensor-Fusion-Using-ES-EKF
Implement Error-State Extended Kalman Filter on fusing data from IMU, Lidar and GNSS.  

This is a module assignment from [State Estimation and Localization](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars) course of [Self-Driving Cars Specialization](https://www.coursera.org/specializations/self-driving-cars?) on Coursera.org.

This assginment implements Error-State Extended Kalman Filter on fusing IMU, Lidar and GNSS data coming from different frequencies.

IMU data is used for motion model prediction and Lidar and GNSS data is used for measurement model correction.

For more details for ES-EKF please refer to [this paper](https://d3c33hcgiwev3.cloudfront.net/3dXfty7_EemFOA6Hm29iNA_de05a1c02eff11e9821ed19f5bd73b7b_CarlaUE4Ubuntu.tar.gz?Expires=1557446400&Signature=VsAZmQwuGUCkPwkuBxs~PR8GoF1Ie9d-4zd4c-bKv5OOsS6-wbGoriCty~OxnYxK9MBEXlvaSxMeNXAVuZzCBLbri-syKLMQ~EjSLMcU6PK9wA3ZFCHETko-9rBpkJKuTlN7cEODpFTjEN~hYkjwLVip7QGAwJMytqwE2WB~iTA_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

# How to run it
Simply do `python3 es_ekf.py`, the data will be loaded and fused.

# Result
Please see the fused 3D trajectory below.
<p align="center"><b>Fusion Result</b>
  <img  src="https://github.com/paulyehtw/Sensor-Fusion-Using-ES-EKF/blob/master/Result.png">
</p>
