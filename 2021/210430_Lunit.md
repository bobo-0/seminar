# 의료 진단과 치료 영역에서의 루닛 인공 지능

**박성윤 박사님**

### Lunit Inc

- 회사 2013년 월에 창업
- 180명의 employees (Boston, Amsterdam, Shanghai, Seoul)
- Medical + deep learning
- 투자자 : LG CNS, Soft Bank, Mirae Asset, Fujifilm, , ,
- 건강검진 결과 —> 영상의학과 교수님들이 영상 데이터를 보고 판단 (이때 Lunit INSIGHT와 함께 보이면서 판독을 도와줌)
- 건강검진은 매년 30%늘지만, 이를 판독할 영상 의학과 선생님은 4%에 불과
  —>AI 기반의 medical detection을 만들어서 진단의 효율성을 높혀서 medical cost를 줄이는것을 목표로 하는 회사
- 서울대병원, 세브란스병원, 삼성병원 등등에서 여러 데이터를 받음
- Closing the loop 를 사용해서 의사들이 선택할지말지 결정할 수 있고, 의사들의 선택을 바탕으로 또 machine 이 학습 가능
- 문제: 3D인 우리 몸이 2D로 보임, 실제 detect 되어야 하는 부분이 잘 안될 수 있음

### **Global Extension**

- Fujifilm의 PACS(Picture Archiving Communicatin System) + Lunit INSIGHT를 합치면
- 위급한 경우를 라벨링을 해줘서 위급한 환자들을 먼저 볼 수 있게 해준다.
- 병명에 대해 검색이 가능해서 의사가 해당 케이스의 다른 환자들을 보고싶을때 볼 수 있게 해준다.
- PHILIPS 등등과 함께 협력하면서 Global out 을 시도하는 중
- 이동 가능한 엑스레이를 만들어내고있고, (COVID 19로 인해서도)
  X-RAY + Lunit Engine을 탑재, 촬영이 되자마자 분석을 해서 결과를 띄워줌 ==> 응급 환자들은 찍자마자 detect 가능, corona 환자들은 ai로 selection 해서 격리 가능
- WHO에서도 결핵을 진단할때는 이런 AI를 사용하는것이 도움이 된다. 라고도 했데

### Future..

- Lunit —> 진단의 영역을 넘어서서 prediction의 영역으로 넘어가려고 한다.(Lunit SCOPE)
- 암을 Screening 하는 것, 빠르게 찾아내는 것이 암을 극복하는데 중요하니까 (Lunit INSIGHT)
- 미리 예측하고, 효율적으로 치료하기 위한 것, 예측하는 영역 (Lunit SCOPE)
  —> Lunit Mission : Concure cancer 하는 것

### QnA

- 개인정보 이슈
  의료영상은 이미지, 이미지는 개인정보라고 보기에는 바로 식별할 수 없기 때문에 그렇게 개인정보 민감성이 떨어진다고 본다.. 
  Data를 병원에서 트레이닝하기때문에 회사가 개인정보를 알 지는 못한다,,
  암호화 관련해서는 knowledge가 부족해서 생각을 못하는 중
