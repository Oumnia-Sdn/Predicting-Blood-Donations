# Data analysis
- Document here the project: Predicting-Blood-Donations
- Description: Blood transfusion saves lives - from replacing lost blood during major surgery or a serious injury to treating various illnesses and blood disorders. Ensuring that there's enough blood in supply whenever needed is a serious challenge for the health professionals. According to WebMD, "about 5 million Americans need a blood transfusion every year".
- Data Source: Our dataset is from a mobile blood donation vehicle in Taiwan. The Blood Transfusion Service Center drives to different universities and collects blood as part of a blood drive. We want to predict whether or not a donor will give blood the next time the vehicle comes to campus.
- Type of analysis: Machine learning using TPOT and other customized pipeplines


# Startup the project

The initial setup.

Create virtualenv and install the project:
```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv ~/venv ; source ~/venv/bin/activate ;\
    pip install pip -U; pip install -r requirements.txt
```

Unittest test:
```bash
make clean install test
```

Check for Predicting-Blood-Donations in gitlab.com/{group}.
If your project is not set please add it:

- Create a new project on `gitlab.com/{group}/Predicting-Blood-Donations`
- Then populate it:

```bash
##   e.g. if group is "{group}" and project_name is "Predicting-Blood-Donations"
git remote add origin git@github.com:{group}/Predicting-Blood-Donations.git
git push -u origin master
git push -u origin --tags
```

Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
Predicting-Blood-Donations-run
```

# Install

Go to `https://github.com/{group}/Predicting-Blood-Donations` to see the project, manage issues,
setup you ssh public key, ...

Create a python3 virtualenv and activate it:

```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```

Clone the project and install it:

```bash
git clone git@github.com:{group}/Predicting-Blood-Donations.git
cd Predicting-Blood-Donations
pip install -r requirements.txt
make clean install test                # install and test
```
Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
Predicting-Blood-Donations-run
```
