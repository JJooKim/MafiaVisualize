# MafiaVisualizeProject

## 프로젝트 소개
* 마피아는 남들의 정체를 모르는 시민과, 서로의 정체를 아는 마피아가 서로 죽이는 게임이다.
* 이 게임은 러시아에 있는 모스크바 대학의 심리학 교수 드미트리 다비도프가 1986년에 발명했다.

* 이 프로젝트는 마피아를 확률 시뮬레이션으로 실험해보는 프로젝트다.

1. 마피아 게임 규칙을 정의하고 파이썬으로 구현한 후
2. 다양한 변인통제를 하며 마피아의 승리 확률을 시각화 및 분석 하고
3. 수식적으로 마피아가 이길 확률을 구하고 시각화한다.



## 마피아 게임 규칙
* 시민과 마피아 딱 두 종류의 집단만 있다고 생각한다.
* 하루는 낮과 밤으로 이루어져 있다.
    * 게임은 낮을 먼저, 밤을 나중에 한다.: 1일차 낮 → 1일차 밤 → 2일차 낮 → 2일차 밤 → ... 
    * 낮에는 모든 사람이 무작위적으로 한 사람을 죽인다. 마피아는 서로를 알고 있지만, 사람을 죽이는 것은 무작위적이라고 가정한다.
    * 밤에는 마피아가 시민 중에 한 명을 죽인다.
    * 시민 승리 조건: 마피아가 모두 죽으면 시민이 승리한다.
    * 마피아 승리조건: 마피아의 수가 시민의 수 보다 같거나 많으면 마피아가 승리한다.
