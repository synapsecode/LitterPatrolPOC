# LitterPatrol (PoC)
This is a basic proof of concept of LitterPatrol. Currently Deals with facial recognition

Steps to Run:
1. run in cmd: pip install -r requirements.txt (ONCE DURING INSTALL)
2. create the dataset folder (ONCE DURING INSTALL)
3. To Collect Dataset Samples: python sampler.py
4. To Train on Samples: python trainer.py
5. To Perform Inference: python recognizer.py