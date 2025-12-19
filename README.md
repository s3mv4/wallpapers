# ImageGoNord
## Website (sometimes does not work properly)
[ImageGoNord](https://ign.schroedinger-hat.org/)

## CLI
Clone the repo
```bash
git clone https://github.com/schroedinger-Hat/ImageGoNord-cli

cd ImageGoNord-cli
```
Set up virtual environment (Arch Linux)
```bash
python3 -m venv venv

source venv/bin/activate
```

Change `requirements.txt` from:
```text
image-go-nord==0.1.5
Pillow==9.2.0
```
To:
```text
image-go-nord==0.1.5
Pillow>=9.2.0
```
Installing the requirements
```bash
pip install -r requirements.txt
```
Usage
```bash
export PYTHONPATH=$PYTHONPATH:$PWD/src:$PWD/tests

python src/image_go_nord_client --img='...'
```
