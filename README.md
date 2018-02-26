# glaucoma-caffe

Média das imagens

$CAFFE_HOME/build/tools/compute_image_mean /home/samira/mestrado/caffe/glaucoma-caffe/input/train_lmdb /home/samira/mestrado/caffe/glaucoma-caffe/input/train_lmdb/mean.binaryproto

$CAFFE_HOME/build/tools/compute_image_mean /home/samira/mestrado/caffe/glaucoma-caffe/input/validation_lmdb /home/samira/mestrado/caffe/glaucoma-caffe/input/validation_lmdb/mean.binaryproto

Treinamento

$CAFFE_HOME/build/tools/caffe train --solver /home/samira/mestrado/caffe/glaucoma-caffe/solver.prototxt 2>&1 | tee /home/samira/mestrado/caffe/glaucoma-caffe/log/train.log