Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 18:00:34 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Parameshreddy1995/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_17:57:09] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_17:57:17] STEP 2: Create topics started

  [INFO 2024-12-05_17:57:38] STEP 2: Completed

  [INFO 2024-12-05_17:57:52] STEP 3: producing data started

  [INFO 2024-12-05_17:57:57] MQTT connection established...

  [INFO 2024-12-05_17:57:59] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:58:04] STEP 4: Preprocessing started

  [INFO 2024-12-05_17:58:06] STEP 7: Visualization started

  [INFO 2024-12-05_17:58:13] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_17:58:23] STEP 9: Starting privateGPT

  [INFO 2024-12-05_17:58:34] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_17:58:35] STEP 8: Starting docker push for: parameshreddy1995/tmlproject1paramv1-8c73-amd64

  [INFO 2024-12-05_17:59:07] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 30137a9cd768 parameshreddy1995/tmlproject1paramv1-8c73-amd64 - message=0

  [INFO 2024-12-05_18:00:18] STEP 8: Successfully ran Docker push: docker push parameshreddy1995/tmlproject1paramv1-8c73-amd64 - message=0

  [INFO 2024-12-05_18:00:33] STEP 10: Started to build the documentation

  [INFO 2024-12-05_18:00:35] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


