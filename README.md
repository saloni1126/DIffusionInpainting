
## 📌 Setup  
Ensure you have all dependencies installed before running the training or testing scripts.
```bash
pip install -r requirements.txt
```

## 🚀 Training  
To start training, execute the following commands:  
```bash
cd /content/image-restoration-sde/codes/config/inpainting
python train.py -opt=options/train/ir-sde.yml

```

## 🚀 Testing
To start testing, execute the following commands:  
```bash
cd /content/image-restoration-sde/codes/config/inpainting
python test.py -opt=options/test/ir-sde.yml
```
