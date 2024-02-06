# create PVQD-S and PVQD-A from PVQD

Step 1: 
download PVQD dataset in "Audio Files"

Step 2: 
mkdir data/16k/train_speech data/16k/train_a data/16k/train_i data/16k/dev_speech data/16k/dev_a data/16k/dev_i data/16k/test_speech data/16k/test_a data/16k/test_i

Step 3:
python create_pvqdS_pvqdA.py

Step 4:
cd data

Step 5:
python seg_utterance.py

Step 6:
python create_loadfile.py 
