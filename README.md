Usage:
 - Place *train*, *train_masks* and *test* data folders in the *input* folder.
 - Convert training masks to *.png* format.
		mogrify -format png *.gif
 - Train
		python train.py
 - Test and submit
		python test_submit.py
