# NGP-HashEncoding
More efficient hash encoding method in instant-NGP

We propose a new hash encoding method in instant-NGP, achieve 30% speed up and almost 10% quality up！ 

## Here are the install steps:

Firstly, pulling down the code in your own workspace

Secondly, create a conda virture environments, you can follow the command below:

```  conda create -n NGP++ python=3.9 ```

Thirdly, activate the environment, and install the necessary packages, you can follow the command below:

``` pip install -r requirements.txt```

If everything goes right, you can successfully start the training by the follow example command:

```python run_nerf.py --config configs/chair.txt --finest_res 512 --log2_hashmap_size 19 --lrate 0.01 --lrate_decay 10```
