trian-----------------------------
python train_simple_nn.py --dataset animals --model output/simple_nn.model --label-bin output/simple_nn_lb.pickle --plot output/simple_nn_plot.png
predict---------------------------
python predict.py --image images/cat.jpg --model output/simple_nn.model	--label-bin output/simple_nn_lb.pickle --width 32 --height 32 --flatten 1
