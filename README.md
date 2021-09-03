# Password Strength Predictor

This is an ML model whicha analyse some data & predict strength of passwords with 82% accuracy.

# Download Code

## Linux
### Installing
<li>Install python3 on your device. Then run</li>

```cmd
sudo apt-get install -y python3-pip
sudo apt-get install -y python3-venv
```

<li>Now run these commands to download & run code</li>

```cmd
git clone https://github.com/cybersaksham/Password-Strength-Predict
cd Password-Strength-Predict
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
jupyter notebook
```

### Uninstalling
First stop jupyter notebook by ctrl+C

```cmd
deactivate
cd ..
rm -rf Password-Strength-Predict
```

## Windows
### Installing
<li>Install python3 & pip3 on your device.</li>

<li>Now run these commands to download & run code</li>

```cmd
git clone https://github.com/cybersaksham/Password-Strength-Predict
cd Password-Strength-Predict
python3 -m venv venv
.\venv\Scripts\activate
pip3 install -r requirements.txt
jupyter notebook
```

### Uninstalling
First stop jupyter notebook by ctrl+C

```cmd
deactivate
cd ..
rmdir /S Password-Strength-Predict
```

