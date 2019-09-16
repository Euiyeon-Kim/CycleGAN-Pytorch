# CycleGAN-Pytorch
Reproduce CycleGAN using pytorch

### Main Losses

1. Adversarial Loss

2. Cycle consistency Loss

3. Identity Loss
	+ 이게 없어지니까 학습속도가 더뎌짐
	+ Paint에서 color composition을 유지하기 위해 사용
	+ Input image의 color보존에 도움을 줌