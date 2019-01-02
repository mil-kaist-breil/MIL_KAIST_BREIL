# Bi-HLED-VAE


## Update 11.27.2018


On repository for MIL_MSREP Project, by KAIST BREIL lab


## Setup


* Create temporary working directory prior to training

```bash
mkdir working_dir
```

* Download test/train data from Cornell Movie Dialog Corpus

```bash
cd data/
bash pull_data.sh
```

## Training

```bash
# edit BiHLED_VAE.ini file to set 
#		mode = train
python execute.py
# or use custom ini file
#		python execute.py my_custom_conf.ini
```

## Testing

```bash
# edit BiHLED_VAE.ini file to set 
#		mode = test
python execute.py
```

## Extra note

On extra update after 11.27, couple directories might not have been updated on GitHub. Need check
on working directory
