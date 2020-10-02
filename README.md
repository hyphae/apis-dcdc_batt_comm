# apis-dcdc_batt_comm

## Introduction
dcdc_batt_commはapis-mainからの指示に従って実際にハードウェアを制御し電力融通を実現するための  
Device Driverである。制御対象のDCDC ConverterとしてTDKラムダ製のEZA2500を想定し、RS485を  
使用してTDKラムダ製独自プロトコルにより通信を行う。  
制御対象のバッテリはRS485上でModbus RTU通信プロトコルを使用して通信を行う想定で作られている。   
(レジスタマップはSony CSL開発の独自仕様)  
dcdc_batt_comm上にはPython Bottleを利用してWeb Serverが立っており、apis-mainとの通信は  
そのWeb Serverを利用してSony CSL開発のWeb APIを介して通信を行う。  


## Getting Started


## Usage


## Documentation


## License
[Apache License Version 2.0](https://github.com/oes-github/apis-dcdc_batt_comm/blob/master/LICENSE)


## Notice
[Notice](https://github.com/oes-github/apis-dcdc_batt_comm/blob/master/NOTICE.md)
