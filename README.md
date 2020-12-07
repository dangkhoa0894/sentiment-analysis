Install environment:
```bash
conda install python=3.6
```

Dependencies guide:

```bash
pip install -r requirements.txt
cd external_lib
chmod a+x install_lib.sh
./install_lib.sh
cd ..
```

Sample run command:

```bash
python -m main -m VDCNN -e ./embeddings/baomoi.model.bin --max 40000 --mix --prob
```
