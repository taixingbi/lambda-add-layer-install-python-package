

```
python3 -m venv myvenv
source myvenv/bin/activate
pip install --upgrade pip
mkdir python
cd python
pip install -t . pandas
pip install -t . robin_stocks
rm -r *dist-info __pycache__
cd ..
zip -r layer.zip python
```






https://www.gcptutorials.com/post/how-to-use-pandas-in-aws-lambda