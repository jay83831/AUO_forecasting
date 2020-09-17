# AUO_forecasting #
Day-ahead forecasting for AUO power load demand

## Globle library & usuage ##
Globle library : util.py <br />
Usuage : `python3 main.py`
<br /><br />
## Moduel 1 : Multi-Scale CNN ##
雋為's work : creat a build_ms_model.py
<br />
### Library usage for moduel ###
ms_util.py
<br />
### Reference ###
https://arxiv.org/pdf/1603.06995.pdf
<br /><br />
## Moduel 2 : Muti EEMD-AE-LSTM ##
翔祐's work : creat a build_CEEMDAELSTM_model.py
<br />
### Library usage for moduel ###
ceemdae_util.py(in progress)
<br />
### Reference ###
https://ieeexplore.ieee.org/document/8996379
<br /><br />
## Environment building ##
step 1:<br />
Use `git clone https://github.com/jay83831/AUO_forecasting.git -b develop` to your local folder<br />
step 2:<br />
activate anaconda with a new python3.6 workspace<br />
step 3:<br />
install the package by pip3 install -r doc/requirements.txt
<br /><br />

