#To run predictions use the command below.
#Replace best.pt with the name of your model
#Replace greensboroq.mp4 with the path to your test file or data.

yolo detect predict model=best.pt source='./greensboro1.mp4' show=True
