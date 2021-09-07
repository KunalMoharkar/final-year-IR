# Amazon QA

to install all the requirements use -

pip install -r requirements.txt

put the processed data in data folder
[train](https://amazon-qa.s3-us-west-2.amazonaws.com/train-qar.jsonl)
[val](https://amazon-qa.s3-us-west-2.amazonaws.com/val-qar.jsonl)
[test](https://drive.google.com/file/d/1A_gaYbyBUOfwi8CQ7d5OO_b91lEvSnwr/view?usp=sharing)

test the setup using-

python/python3 main.py --mode=train --save_dir=saved_dirs/new_dir --model_name=LM_QAR

for more customized options refer params file in lang_models
