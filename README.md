<div style="text-align:center; margin-bottom: 30px;">
    <h3>Project Process</h3>
    <p>Build an end-to-end object detection YOLOv7 contraband detection network. The YOLOv7 object detection algorithm adopts a cascaded model scaling method to effectively integrate features. By utilizing reparameterization and dynamic label allocation strategies to handle the weights of different output layers, it achieves high running speed and detection accuracy. The real-time detection tested can reach 24 FPS. A positive and negative sample matching strategy is adopted to effectively address the issues of class imbalance and invalid contextual semantics. To enable hardware deployment and migration of the algorithm model, a long-range attention mechanism enhances the reparameterized network model RepConv, and features from different network layers are connected to achieve feature reuse. Finally, to verify the feasibility of the algorithm, real security inspection SIXray data images are used for testing.</p>
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>Experiment Environment</h3>
    <p>The experiment was conducted on a Windows operating system with an Intel(R) Core(TM) i7-6700 CPU @ 2.40 GHz, NVIDIA GeForce RTX 2080 Ti GPU, 16GB of RAM, 1TB hard drive, Anaconda version 4.2, and Python version 3.8 as the programming language.</p>
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>Project Outcome</h3>
    <p>Experimental results show that the network can effectively detect contraband, with a network model compression rate of 62%.</p>
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>A random X-ray image of the dataset</h3>
    <img width="80%" alt="Random X-ray image" src="https://github.com/user-attachments/assets/222605f5-354e-46ce-a786-741b8cdf186a" />
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>Security X-ray image</h3>
    <img width="80%" alt="Security X-ray image" src="https://github.com/user-attachments/assets/f48855c5-cc9a-47b9-9803-c231ac13bfd9" />
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>Training parameters and strategies</h3>
    <img width="80%" alt="Training parameters" src="https://github.com/user-attachments/assets/3115d1b4-27d6-4803-93e3-f5e339660c90" />
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>Classification of losses: Location loss, Confidence loss</h3>
    <img width="80%" alt="Classification of losses" src="https://github.com/user-attachments/assets/99971b18-27c4-462b-af83-7abd6b614c23" />
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>Performance comparison of the models before and after quantification</h3>
    <img width="80%" alt="Performance comparison before and after quantification" src="https://github.com/user-attachments/assets/86ef8694-d766-4994-83a5-a1658716d0e2" />
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>Before and after quantization</h3>
    <img width="80%" alt="Before and after quantization 1" src="https://github.com/user-attachments/assets/586a5551-525b-4652-81de-99ce63c2eb7a" />
    <img width="80%" alt="Before and after quantization 2" src="https://github.com/user-attachments/assets/1f197968-aa54-4ea7-83bc-6e877ca38a8f" />
</div>

<div style="text-align:center; margin-bottom: 30px;">
    <h3>Detection renderings</h3>
    <img width="80%" alt="Detection renderings" src="https://github.com/user-attachments/assets/503b783f-e85d-403c-b243-ab3954bb7a84" />
</div>
