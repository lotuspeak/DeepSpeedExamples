huggingface-cli download --resume-download facebook/opt-350m --local-dir opt-350m

export HF_ENDPOINT=https://hf-mirror.com
export PYTHONPATH=/home/nh/code/DeepSpeedExamples/applications/DeepSpeed-Chat

huggingface-cli download --repo-type dataset --resume-download Dahoas/rm-static
