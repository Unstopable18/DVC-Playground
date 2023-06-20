# DVC-Playground
<b>To install DVC -></b> sudo snap install dvc --classic <br>
<b>Init DVC -></b> dvc init <br>
<b>Add Storage for GDrive -></b> dvc remote add -d storage gdrive://1kSfoD6u67LtRt28Y36XX9uG3vxsYF3b7 <br>
<b>Add Storage for DagsHub -></b> dvc remote add sdhub https://dagshub.com/vdeshmukh/DVC-Playground.dvc <br>
dvc remote modify origin auth basic  <br>
dvc remote modify origin user vdeshmukh  <br>
dvc remote modify origin password e90d548993071bf0e9d0ff193589cbe56b624d74 <br>
<b>DVC add images datasets -></b> dvc add datasets/detection/images <br>
<b>DVC add labels datasets -></b> dvc add datasets/detection/labels <br>
<b>DVC status -></b> dvc status <br>
<b>DVC commit -></b> dvc commit <br>
<b>DVC push -></b> dvc push -r sdhub <br>