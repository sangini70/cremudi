# CREMUDI_VIDEO_PROMPT_SKILL.md

# CREMUDI VIDEO PROMPT SKILL

## 1. Purpose

이 문서는 CREMUDI 쇼츠의 이미지 및 영상 품질을 높이기 위한
재사용 가능한 영상 연출 지식을 축적한다.

이 문서의 기법은 고정 템플릿이 아니다.

Codex는 대본과 실제 이미지를 분석한 뒤
장면에 적합한 기법만 선택한다.


# 2. Natural Human Motion

사람의 자연스러운 행동이나 일상적 장면에서는
다음 영상 문법을 우선 검토한다.

- handheld
- vlog style
- subtle natural camera shake
- natural subject tracking
- natural body movement
- subtle facial movement

Handheld와 Vlog는
카메라가 완벽하게 고정된 인공적인 느낌을 줄이고
사람이 실제로 촬영하는 듯한 자연스러움을 만드는 데 사용할 수 있다.

그러나 모든 장면에 적용하지 않는다.


# 3. Fast Cuts

짧은 시간 안에 많은 정보,
행동 또는 과정을 전달해야 하는 경우 검토한다.

적합한 예:

- 정보형 쇼츠
- 빠른 과정 설명
- 여러 단계의 변화
- 광고형 전개
- 요리나 제작 과정

활용할 수 있는 표현:

- fast cuts
- rapid cuts
- short shot duration
- close-up
- insert shots
- detail shots

Fast Cut은 단순히 영상을 빠르게 만드는 것이 아니라
짧은 시간 안에 여러 중요한 정보를 보여주기 위한 연출이다.


# 4. One Take / Long Take

하나의 행동을 계속 따라가야 하거나
연속성·긴장·몰입이 중요한 장면에서는
One Take 또는 Long Take를 검토한다.

적합한 예:

- 추격
- 전투
- 이동
- 긴장되는 행동
- 감정적으로 이어지는 행동
- 공간을 따라가는 장면

활용할 수 있는 표현:

- one take
- long take
- continuous shot
- uninterrupted camera movement
- continuous subject tracking

컷을 많이 넣는 것보다
하나의 행동을 끝까지 보여주는 것이 효과적인 경우 사용한다.


# 5. Controlled Motion

숫자,
계산,
그래프,
구조,
금융 개념처럼
정확한 이해가 중요한 장면에서는
과도한 카메라 움직임을 피한다.

검토할 수 있는 방식:

- locked camera
- slow push-in
- slow pull-back
- controlled pan
- controlled tracking
- subtle motion

정보를 이해해야 하는 순간에는
영상의 화려함보다 가독성을 우선한다.


# 6. Close-Up and Detail

시청자가 특정 행동이나 변화를 정확히 봐야 하는 경우
Close-Up 또는 Detail Shot을 사용한다.

예:

- 손의 행동
- 숫자의 변화
- 특정 오브젝트
- 표정
- 작은 구조적 변화

전체 화면에서 중요한 정보가 묻히지 않게 한다.


# 7. Camera Movement Must Follow Meaning

카메라를 이유 없이 움직이지 않는다.

카메라 움직임은 다음 기능 중 하나를 가져야 한다.

- 대상을 따라간다.
- 중요한 요소를 발견하게 한다.
- 공간을 보여준다.
- 변화에 접근한다.
- 결과를 강조한다.
- 다음 장면으로 연결한다.


# 8. Image-Aware Motion

영상 프롬프트 작성 전에 실제 이미지를 본다.

현재 이미지에서 확인한

- 인물 위치
- 몸의 방향
- 시선
- 손의 위치
- 오브젝트 위치
- 공간의 깊이
- 카메라 각도

를 기준으로 움직임을 설계한다.

이미지와 충돌하는 움직임을 지시하지 않는다.


# 9. Scene-to-Scene Continuity

현재 장면만 멋있게 만드는 것이 목표가 아니다.

Scene N-1
→ Scene N
→ Scene N+1

을 함께 본다.

가능하면 현재 장면의 움직임 또는 카메라 방향이
다음 장면으로 자연스럽게 이어지도록 한다.


# 10. Start and End State

영상 프롬프트는 움직임만 설명하지 않는다.

필요한 경우 다음을 고려한다.

START:
현재 이미지의 실제 상태

ACTION:
장면에서 발생할 자연스러운 변화

END:
다음 장면으로 이어지기 좋은 상태

영상의 끝을 다음 장면의 시작을 준비하는 상태로 만들 수 있다.


# 11. Motion Hierarchy

한 장면에서 모든 것을 동시에 움직이지 않는다.

우선순위를 판단한다.

1. 이야기상 가장 중요한 피사체
2. 그 피사체의 행동
3. 필요한 카메라 움직임
4. 보조적인 환경 움직임

주요 행동을 방해하는 불필요한 움직임을 줄인다.


# 12. Natural Does Not Mean Busy

자연스러운 영상은
많이 움직이는 영상이 아니다.

자연스러움은

실제 이미지 상태
+
물리적으로 가능한 행동
+
적절한 카메라
+
적절한 속도
+
적절한 컷 길이

의 일치에서 나온다.


# 13. Skill Selection

장면마다 내부적으로 묻는다.

사람의 자연스러운 행동인가?
→ Handheld / Vlog 검토

짧은 시간에 여러 정보를 전달해야 하는가?
→ Fast Cuts 검토

하나의 행동을 계속 따라가야 하는가?
→ One Take / Long Take 검토

정확한 정보 이해가 중요한가?
→ Controlled Motion 검토

작은 변화가 핵심인가?
→ Close-Up / Detail 검토

어느 것도 필요하지 않다면
불필요한 기법을 추가하지 않는다.


# 14. Prompt Principle

영상 프롬프트는 키워드 목록으로 끝내지 않는다.

다음 구조를 자연어로 명확하게 전달한다.

- 무엇이 보이는가
- 무엇이 움직이는가
- 어떻게 움직이는가
- 카메라는 어떻게 반응하는가
- 움직임의 속도와 분위기는 어떤가
- 장면이 어떻게 끝나는가

필요한 영상 문법 키워드는
이 연출 설명을 보강하는 용도로 사용한다.


# 15. Learning Rule

새로운 영상 제작 기법이 실제 제작에서 유용하다고 확인되면
이 Skill에 추가할 수 있다.

추가할 때는 가능하면 다음을 함께 기록한다.

- 기법 이름
- 어떤 상황에서 유용한가
- 어떤 효과가 있는가
- 어떤 상황에서는 사용하지 않는가
- 필요한 프롬프트 표현

새로운 발견 때문에 Constitution이나 Workflow를
불필요하게 수정하지 않는다.


# CURRENT CORE SKILLS

- Handheld
- Vlog
- Fast Cuts
- One Take
- Long Take
- Continuous Tracking
- Controlled Motion
- Close-Up
- Detail Shot
- Scene-to-Scene Continuity
- Image-Aware Motion
- Start → Action → End
