# shogi-recognizer

## Image Resouces

- [Shogi images by muchonovski](http://mucho.girly.jp/bona/)
  - [Creative Commons 表示-非営利 2.1 日本 License](http://creativecommons.org/licenses/by-nc/2.1/jp/)
- [かわいいフリー素材集 いらすとや](https://www.irasutoya.com/)
- [しんえれ外部駒](http://shineleckoma.web.fc2.com/)
  - [Creative Commons 表示-非営利 2.1 日本 License](http://creativecommons.org/licenses/by-nc/2.1/jp/)
- [無料素材倶楽部](http://sozai.7gates.net/docs/japanese-chess/)


## Prerequisite

- Python `>= 3.6`
  - Tensorflow `>= 1.7`
  - Beautiful Soup `>= 4.6`
  - Pillow `>= 5.0`


## Training

```
$ pip install -r requirements.txt
```

### Prepare dataset

```
$ ./dataset.sh
```

### Train

```
$ ./train.sh
```
