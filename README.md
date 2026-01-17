openairinterface5g/openair1/PHY/NR_UE_TRANSPORT/csi_rx.c 파일을 수정하였습니다.

1. Legacy code의 2CSI ports 방식 -> 4CSI ports로 수식을 변경하였습니다
2. [NR_PHY] [CSI-IN] f=31 s=13 abs=633 ports=4 row=5 dens=2 rb=51@0 l0=3 rxP=195710 hP=120972 hMax=3187328 zeroH=96% rsrp=195710 noise=9415 intfN=4291025884 RI=2 rankInd=1 PMI=12 sinr=18dB CQI=13
[NR_PHY] [TEST-LOG] RI=2 N_ports=4 rank_ind=1 i2=12
[NR_PHY] RI = 2 i1 = 0.0.0, i2 = 12, SINR = 18 dB, CQI = 13
ULLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLL[NR_PHY] RSRP = 291267 (-146 dBm)
와 같이 Legacy보다 볼 수 있는 symbol 값의 종류를 추가하였습니다.
3. MT-8000 장비와 통신 시 RTD 프로그램에서 측정되는 BLER 범위가 20 - 50에서 8 - 30로 개선되었습니다.
