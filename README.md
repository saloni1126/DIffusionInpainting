train:
cd /content/image-restoration-sde/codes/config/inpainting
python train.py -opt=options/train/ir-sde.yml
test:
cd /content/image-restoration-sde/codes/config/inpainting
python test.py -opt=options/test/ir-sde.yml
