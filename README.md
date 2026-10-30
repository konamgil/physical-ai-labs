# 피지컬 AI 실습

대학생 특강 「피지컬 AI: 기초부터 실습 심화까지」의 실습 자료입니다.
모두 **Google Colab**에서 CPU만으로 돌아갑니다. Google 계정만 있으면 됩니다.

| 실습 | 내용 | 열기 |
|---|---|---|
| 0 | 막대 세우기: 사람 vs AI. 직접 조종, 반응 지연, AI의 시행착오 학습, 신경망 두뇌 | **[웹페이지로 바로 열기](https://konamgil.github.io/physical-ai-labs/lab0_balance.html)** · [Colab](https://colab.research.google.com/github/konamgil/physical-ai-labs/blob/main/lab0_balance.ipynb) |
| 1 | 2관절 로봇팔: 정기구학 · 역기구학 · PID 제어 | [![Colab에서 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/konamgil/physical-ai-labs/blob/main/lab1_robot_arm_basics.ipynb) |
| 2 | 강화학습(PPO)으로 균형 잡기, 제어 지연과 도메인 랜덤화 | [![Colab에서 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/konamgil/physical-ai-labs/blob/main/lab2_reinforcement_learning.ipynb) |
| 3 | 모방학습(행동 복제 · DAgger)과 미니 VLA | [![Colab에서 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/konamgil/physical-ai-labs/blob/main/lab3_imitation_and_vla.ipynb) |

## 사용법

1. 위 표의 **Colab에서 열기**를 누릅니다.
   - 셀을 처음 실행할 때 **"경고: 이 노트북은 Google에서 작성하지 않았습니다"** 창이 뜨면 **무시하고 계속하기**를 누릅니다.
2. 고친 내용을 저장하려면 Colab 메뉴에서 **파일 → Drive에 사본 저장**을 누릅니다.
3. 셀을 위에서부터 순서대로 실행합니다 (Shift+Enter).

- 실습 0은 **웹페이지로 바로 열기**가 가장 간단합니다(설치·로그인 없음). Colab으로 열면 셀 하나만 실행하면 화면이 뜹니다. 화면을 한 번 클릭한 뒤 키보드 ← → 로 조종합니다. 휴대폰은 화면의 밀기 버튼을 누르고 있으면 됩니다.
- 실습 2는 첫 코드 셀의 `!pip install ...` 줄 앞의 `#`을 지우고 실행합니다.
- 인터넷이 없을 때 실습 0은 [lab0_balance.html](lab0_balance.html)을 내려받아 브라우저로 열면 됩니다.
