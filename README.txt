Project for FIB-PAE together with Nestlé's cybersecurity group.

This program presents an AI prototype for the problem that Nestlé presented to us about improving an AI for the detection of
phishing in an environment with attacks from adversaries.

USE:
1. Run RandomForestURLClient.ipynb to create discriminatormodel.sav which is our basic phishing detection model.
2. Run BlackBoxAttack.ipynb to train the generator, the generator model and created URLs will be saved.

This second step will take a while, because we are training both models, the attacker to create more credible URLs for
trick the discriminator model and the discriminator model to keep learning to detect the attacker's fake URLs.