## Recipes

Experimental https://github.com/espnet/espnet style recipes.


# /zhzhao/miniconda3/bin/conda init bash | conda activate pytorch16 | /zhzhao/miniconda3/envs/pytorch16/bin/python /zhzhao/code/wavenet-vocoder/egs/mulaw256/../..//train.py --dump-root /zhzhao/dataset/LJSpeech-1.0/wavs/ --preset /zhzhao/code/wavenet-vocoder/egs/mulaw256/conf/mulaw256_wavenet.json --checkpoint-dir=/zhzhao/code/wavenet-vocoder/egs/mulaw256/exp/lj_train_no_dev_mulaw256_wavenet --log-event-path=/zhzhao/code/wavenet-vocoder/egs/mulaw256/tensorboard/lj_train_no_dev_mulaw256_wavenet

/zhzhao/miniconda3/envs/pytorch16/bin/python /zhzhao/code/wavenet-vocoder/train.py  --dump-root /zhzhao/dataset/LJSpeech-1.0/wavs/  --preset /zhzhao/code/wavenet-vocoder/egs/LJSpeech/conf/mulaw256_wavenet.json  --checkpoint-dir=/zhzhao/code/wavenet-vocoder/egs/LJSpeech/exp/lj_train_no_dev_mulaw256_wavenet  --log-event-path=/zhzhao/code/wavenet-vocoder/egs/LJSpeech/tensorboard/lj_train_no_dev_mulaw256_wavenet
