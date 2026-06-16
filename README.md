This repository contains two PINN experiment notebooks:

- `FP32/PINN.ipynb` - FP32 version
- `FP64/mypinn.ipynb` - FP64 version

Download the dataset from:

https://parfenyev.itp.ac.ru/data/2d-turb-PINN/

Put these files into the folder you want to run, for example into both `FP32/` and `FP64/`:

- `vort-prod.h5`
- `vel-u-prod.h5`
- `vel-v-prod.h5`
- `p-prod.h5`

Install dependencies:

```bash
pip install numpy scipy h5py matplotlib pillow opencv-python tqdm notebook torch
```

Run FP32:

```bash
cd FP32
jupyter notebook PINN.ipynb
```

Run FP64:

```bash
cd FP64
jupyter notebook mypinn.ipynb
```

Run notebook cells from top to bottom. GPU is recommended, especially for FP64.
