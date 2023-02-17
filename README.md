# PatchAttacks
Adversarial patch attacks


Env
```shell
$ activate deepl
$ python pretrained/*.py
```

Classification
```shell
$ python adversarial_patch.py --cuda --netClassifier inceptionv3 --max_count 500 --imag e_size 299 --patch_type circle --outf log
$ python LaVAN_V2.py
$ python camera_stickers.py  # --is_targeted (--target_label_idx 595)
```

Detection
```shell
$
```
