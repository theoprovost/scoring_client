# Project : Scoring client

## Status
<br>

|   |   |  comments   |
|---|---| :---: |
|__Part 1__|  |  |
| Model | ✅ | Perfectible |
|  | |   |
|__Part 2__||
|Display score|❌| Score is in a table but not displayed right now |
|Display descriptive|✅|Not every info is displayed|
|Display comparison|❌|  |

<br>

## Deliverables
[ Subject](https://simplonline.co/briefs/a1e3b434-ff7f-477c-9354-e052fd1a85f7) <br>
[Data source](https://drive.google.com/file/d/1G5EgIa41qFm8UzS-A1OQez5HMkPksaQQ/view) <br>
[Work notebook](https://github.com/theoprovost/scoring_client/blob/master/nb.ipynb) <br>
[Previsional retroplanning](#planning) <br>
[Dashboard (Not online for now, this a archive of a pbix file)](https://drive.google.com/file/d/1Xp6HO2V6PwGo1uc-R9-tuomScuk4ojpw/view?usp=sharing)

## Get started

> Development system : <br><br>
> OS : MacOS Big Sur 11.6.5 <br>
> Python v3.9.12 <br>
> Pip v22.0.4

### 1 - Clone project
```text
# HTTPS
git clone https://github.com/theoprovost/scoring_client.git <dst_folder>

# SSH
git clone git@github.com:theoprovost/scoring_client.git <dst_folder>
```

### 2 - Install dependencies
```text
cd <dst_folder>
python3.9 -m pip install -r requirements.txt
```

### 3 - Run jupyter kernel
```text
# If not already installed -> https://jupyter.org/install, then...
jupyter lab --notebook-dir $PWD
```

### 4 - Open the Power BI file / browse if applicable

## <a name='planning'></a>Retroplanning

||MONDAY|TUESDAY|WEDNESDAY|THURSDAY|FRIDAY|
|--|--|--|--|--|--|
|<p style="transform:rotate(-90deg)">PREVISIONNEL</p>| - Subject analysis <br> - GPU support documentation <br> - Base model exploration| - Base model improvement <br> - Model selection/validation| - Dashboard creation| - Dashboard (#2) + deployment + containerisation (?) <br> - Presentation and deliverables redaction | / |
|<p style="transform:rotate(-90deg)">REALITY</p><td colspan=2>GPU / Hardware troubleshoot|- Dashboard creation <br>- Base model <br>- Dependencies troubleshoot|Same|Same|
