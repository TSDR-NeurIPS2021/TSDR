## Code Structure

* `main.py`: the main function for the experiment
* `TSDR_P.py`: the TSDR-P algorithm
* `TSDR_T.py`: the TSDR-T algorithm
* `data.py`: the data preprocessing script

## Dataset

* For choosing a dataset, set `--dataset [mnist|adult|covertype|MagicTelescope|mushroom|statlog]`.

## Examples

```
python3 main.py --model 'TSDR_P' --dataset 'mnist'
```

```
python3 main.py --model 'TSDR_T' --dataset 'mnist'
```
