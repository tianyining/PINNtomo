# PINNtomo
PINNtomo: Seismic tomography using physics-informed neural networks

Seismic traveltime tomography using transmission data is widely used to image the Earth's interior from global to local scales. In seismic imaging, it is used to obtain velocity models for subsequent depth-migration or full-waveform inversion. In addition, cross-hole tomography has been successfully applied for a variety of applications, including mineral exploration, reservoir monitoring, and CO2 injection and sequestration. Conventional tomography techniques suffer from a number of limitations, including the use of a smoothing regularizer that is agnostic to the physics of wave propagation. Here, we propose a novel tomography method to address these challenges using developments in the field of scientific machine learning. Using seismic traveltimes observed at seismic stations covering part of the computational model, we train neural networks to approximate the traveltime factor and the velocity fields, subject to the physics-informed regularizer formed by the factored eikonal equation. This allows us to better compensate for the ill-posedness of the tomography problem compared to conventional methods and results in a number of other attractive features, including computational efficiency. We show the efficacy of the proposed method and its capabilities through synthetic tests for surface seismic and cross-hole geometries. Contrary to conventional techniques, we find the performance of the proposed method to be agnostic to the choice of the initial velocity model.


## Citation
If you find our work useful in your research, please cite:
```
@article{waheed2021pinntomo,
  title={PINNtomo: Seismic tomography using physics-informed neural networks},
  author={Waheed, Umair bin and Alkhalifah, Tariq and Haghighat, Ehsan and Song, Chao and Virieux, Jean},
  journal={arXiv preprint arXiv:2104.01588},
  year={2021}
}
```

## Contact
If you have any questions, please feel free to email the author.
