To test pix2pix

```bash
$ git clone https://github.com/J-TKim/GAN.git
$ cd data 
$ bash download_pix2pix_dataset.sh facades
$ cd ../GAN/pix2pix
$ python3 pix2pix.py --dataset_name facades
```