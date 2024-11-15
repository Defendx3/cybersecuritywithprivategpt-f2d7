Latest Logs From Latest Build
==============================

Generated On: 2024-11-15 16:42:48 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Defendx3/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-15_16:39:41] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-15_16:39:44] STEP 2: Create topics started

  [INFO 2024-11-15_16:39:59] STEP 2: Completed

  [INFO 2024-11-15_16:40:05] STEP 3: producing data started

  [ERROR 2024-11-15_16:40:07] Cannot connect to MQTT broker in tml_read_MQTT_step_3_kafka_producetotopic_dag-cybersecuritywithprivategpt-f2d7.py - invalid literal for int() with base 10: ''

  [INFO 2024-11-15_16:40:08] STEP 4: Preprocessing started

  [INFO 2024-11-15_16:40:10] STEP 4: Preprocessing started

  [INFO 2024-11-15_16:40:11] STEP 7: Visualization started

  [INFO 2024-11-15_16:40:17] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-15_16:40:22] STEP 9: Starting privateGPT

  [INFO 2024-11-15_16:40:27] STEP 8: Starting docker push for: defendx/cybersecuritywithprivategpt-f2d7-amd64

  [INFO 2024-11-15_16:40:49] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit f6323295ea62 defendx/cybersecuritywithprivategpt-f2d7-amd64 - message=0

  [WARN 2024-11-15_16:42:22] STEP 8: There may be an issue pushing to Docker Hub, or just wait few seconds to see if the container shows up.  Here is the command: docker push defendx/cybersecuritywithprivategpt-f2d7-amd64 - message=1

  [INFO 2024-11-15_16:42:48] STEP 10: Started to build the documentation

  [INFO 2024-11-15_16:42:49] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


