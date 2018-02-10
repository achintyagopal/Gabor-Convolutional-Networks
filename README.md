#We are still partially improve the code. This is a demo for GCN on MNIST dataset using torch7

To run this demo, you should  install these dependencies:
```
luarocks install torchnet
luarocks install optnet
```

install GCN:
```bash
cd $DIR/GCN
bash install.sh
```

run this demo:
```bash
cd $DIR/MNIST_demo
bash ./scripts/Train_MNIST.sh
```

#The experimental results of the comparison algorithm are directly quoted from the corresponding papers. 

#Acknowledgement
This demo is partially referenced to the code of Orientation Response Networks(ORN,`http://zhouyanzhao.github.io/ORN/`)
If you use this demo please cite our paper and ORN. 

#bibtex:

@article{Luan2016GCN,
  title={Gabor Convolutional Networks},
  author={Luan, Shangzhen and Zhang, Baochang and  Chen, Chen and Cao, Xianbin and Han, Jungong and Liu, Jianzhuang},
  year={2017},
}

@INPROCEEDINGS{Zhou2017ORN,
  title={Oriented Response Networks},
  author={Zhou, Yanzhao and Ye, Qixiang and Qiu, Qiang and Jiao, Jianbin},
  booktitle = {CVPR}
  year={2017},
}

