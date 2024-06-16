```
conda install -c conda-forge nodejs yarn
```

```
cd lumino
yarn && yarn build
```

```
cd jupyterlab
yarn link ..\lumino --all
yarn && yarn build
pip install -ve .
```

```
cd jupyterlab
juypter lab build
```

```
cd ipydatagrid
jlpm link ..\lumino --all
jlpm && jlpm build
pip install -ve .
```
