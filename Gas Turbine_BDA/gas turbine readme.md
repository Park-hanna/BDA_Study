# Dataset Information
<hr>
* 실험은 가스 터빈 추진 장치를 특징으로 하는 해군 함정의 수치 시뮬레이터를 통해 수행됨. 
완전한 시뮬레이터 (Properller, Hull, GT, Gear Box 및 Controller)를 구성하는 다양한 블록이 여러 유사한 실제 추진 플랜트에서 개발되고 미세 조정됨.
이런 관찰을 고려할 때 사용 가능한 데이터는 가능한 실제 선박과 일치합니다.


이 시뮬레이터 릴리스에서는 GT 압축기 및 터빈과 같은 GT 구성 요소의 시간 경과에 따른 성능 저하를 고려 할 수 있음

###The propulsion system behaviour has been described with this parameters:
* Ship spped :: 선속 (linear function of the lever position lp).
* Compressor degradation coefficient kMc.(압축기 열화 계수)
* Turbine degradation coefficiednt kMt.(터빈열화계수)
각 가능한 


###Attribute Information :
A 16-feature vector containing the GT measures at steady state of the physical asset:
* Lever posirion (lp) [ ]
* Ship spped (v) [knots]
* Gas Turbine (GT) shaft torque (GTT) [kN m]
* GT rate of revolutions (GTn) [rpm]
* Gas Generator rate of revolutions (GGn) [rpm]
* Starboard Propeller Torque (Ts) [kN]
* Port Propeller Torque (Tp) [kN]
* Hight Pressure (HP) Turbine exit temperature (T48) [C]
* GT Compressor inlet air temperature (T1) [C]
* GT Compressor outlet air temperature (T2) [C]
* HP Turbine exit pressure (P48) [bar]
* GT Compressor inlet air pressure (P1) [bar]
* GT Compressor outlet air pressure (P2) [bar]
* GT exhaust gas pressure (Pexh) [bar]
* Turbine injection Control (TIC) [%]
* Fuel flow (mf) [kg/s]

