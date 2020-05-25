環境構築
------------

docker使えるようにしておく

```bash
sudo python3 -m pip install virtualenv
mkdir ~/virtualenv/molecule
virtualenv ~/virtualenv/molecule
source ~/virtualenv/molecule/bin/activate
python -m pip install "molecule[lint]"
molecule init role molecule-sandbox-role
```

moleculeコマンド
--------------

`molecule test`
