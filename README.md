# PYNQ DSP

PYNQ-Z2でデジタル音声処理をしたい

[https://github.com/Xilinx/PYNQ](https://github.com/Xilinx/PYNQ) からforkしたpythonのpynqパッケージです

---

この方法はだめ

## 導入

PYNQのLinux上でリポジトリをClose

```
$ git clone https://github.com/kamiyaowl/pynq_dsp.git
$ cd pynq_dsp
```

### 普通にinstallする場合

```
$ python3 setup.py develop

# uninstallしたい場合
$ python3 setup.py develop -u
```

### `~/pynq`と同様に即時反映させたい場合

```
$ ln -s ~/pynq_dsp /usr/local/lib/python3.6/dist-packages/pynq_dsp

# シンボリックリンクを消したい場合
$ unlink /usr/local/lib/python3.6/dist-packages/pynq_dsp
```
