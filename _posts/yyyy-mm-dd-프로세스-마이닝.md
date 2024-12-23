---
title: 프로세스 마이닝
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 경영전략]
published: false
#tags: []
#pin: false
#math: false
#mermaid: false
#image:
#  path: /commons/devices-mockup.png
#  lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
#  alt: Responsive rendering of Chirpy theme on multiple devices.
---

<div class="post-wrap">
  <div class="para">
    <div class="para-title">
      I. 경영관리의 필수요소, 프로세스 마이닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프로세스 마이닝의 정의
        </div>
        <div class="para-cntnt">
            비즈니스 프로세스 개선위해 누적된 이벤트로그 분석, 유용한 정보를 추출하는 마이닝기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. 프로세스 마이닝
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. 프로세스 마이닝의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/프로세스마이닝.png" alt="프로세스 마이닝">
<!--            <figcaption>Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. 프로세스 마이닝의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
프로세스 마이닝의 구성요소
이벤트 로그 (Event Log)

프로세스 마이닝의 핵심 데이터 소스.
프로세스 수행에서 기록된 활동(이벤트)들의 시퀀스 정보.
주요 구성:
Case ID: 개별 프로세스 인스턴스를 식별하는 고유 ID.
Activity: 수행된 작업 또는 활동 이름.
Timestamp: 작업이 수행된 시간 정보.
(Optional) Attributes: 추가 정보(리소스, 비용 등).
프로세스 모델 (Process Model)

이벤트 로그로부터 추출된 프로세스 구조를 나타내는 모델.
주요 종류:
Petri Net: 상태 및 전환 기반 모델.
BPMN: 비즈니스 프로세스를 시각화하는 표준화된 모델.
Directly-Follows Graph (DFG): 활동 간 직접적인 순서를 나타내는 그래프.
프로세스 디스커버리 (Process Discovery)

이벤트 로그에서 프로세스 모델을 자동으로 생성하는 단계.
사용 기법:
Alpha Algorithm
Heuristic Mining
Inductive Mining
컴포넌트 및 시각화 (Components & Visualization)

추출된 프로세스 모델을 사용자에게 이해하기 쉽게 제공.
주로 사용되는 도구:
Sankey Diagram
Gantt Chart
Performance Analysis Graph
컨퍼포먼스 분석 (Performance Analysis)

이벤트 로그와 프로세스 모델 간의 비교를 통해 병목현상, 비효율성, 규칙 위반 분석.
주요 메트릭:
프로세스 소요 시간(TAT, Throughput Time).
리소스 활용도.
활동 빈도와 대기 시간.
프로세스 개선 및 컴플라이언스 검증

실제 프로세스 수행 결과와 이상적인 모델 간의 비교로 최적화 방향 도출.
규정 준수 여부 평가 및 프로세스 최적화 방안 제안.


주요기법 발순확
  발견 - 프로세스 모델을 생성하는 기법 / 이벤트 로그
  순응도검사 - 현실이 모델에 일치하는지 확인 / 이벤트로그와 프로세스 모델
  확장 - 기존의 프로세스 모델을 확장하고 개선 / 모델과 이벤트로그를 이용

        </div>
      </div>
    </div>
  </div>

  <div class="refr-wrap">
    <div class="refr-title">
        참고자료
    </div>
    <ol class="refr-list">
    <!--    <li>(나현식, 최대선) <a target="_blank" href="https://scienceon.kisti.re.kr/commons/util/originalView.do?cn=JAKO202225948430499&oCn=JAKO202225948430499&dbt=JAKO&journal=NJOU00291864">메타버스 보안 위협 요소 및 대응 방안 검토</a></li>-->
    <!--    <li>(M. Uddin, S. Manickam, H. Ullah, M. Obaidat and A. Dandoush) <a target="_blank" href="https://ieeexplore.ieee.org/abstract/document/10138386">Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</a></li>-->
    </ol>
  </div>
</div>
