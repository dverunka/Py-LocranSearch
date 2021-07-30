## Results

graphs: in ```graphs/``` folder

statistics: printed on standard output (stdout)

report: ```report.pdf```

### Random search

de jong first, D = 10

```python
min=5.593590213981131
max=18.097367491869893
mean=11.976866164566825
median=12.231670805557226
stddev=2.6619891817449584
```

de jong second, D = 10

```python
min=1078.736308424624
max=4801.331026865194
mean=2738.5267393062754
median=2800.759267849512
stddev=1026.8241254579727
```

schweffel, D = 10

```python
min=-2769.479549800826
max=-2065.4463689348822
mean=-2295.9487158331485
median=-2263.7598598636923
stddev=169.39889027375946
```

### Local search

de jong first, D = 10

```python
min=1.2603861579934814
max=44.3334887667238
mean=9.244430176378952
median=4.355929184461102
stddev=11.679096119609053
```

de jong second, D = 10

```python
min=207.623314847859
max=26018.602762493963
mean=6677.44401544489
median=2371.1406374656635
stddev=8399.870233454812
```

schweffel, D = 10

```python
min=-2208.481817501992
max=-236.8687968967047
mean=-1246.0249645250353
median=-1343.274412520807
stddev=451.35479100217253
```

### Simulated annealing

de jong first, D = 10

```python
min=0.22643026056788945
max=0.6182069602158213
mean=0.42129111527380103
median=0.4195076535726737
stddev=0.11204902739684064
```

de jong second, D = 10

```python
min=22.818956481360065
max=124.93155958646132
mean=39.42947025598873
median=33.30880058924126
stddev=20.426243058050286
```

schweffel, D = 10

```python
min=-3609.2679085604327
max=-2121.8323281153953
mean=-2649.747981146476
median=-2616.150845236727
stddev=362.13204840484565
```

## Dependencies

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install:

```bash
python3 -m pip install numpy
python3 -m pip install matplotlib
```

## Usage

```python
python3 run.py
```
