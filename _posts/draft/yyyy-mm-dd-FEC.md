---
title: FEC
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 네트워크]
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
      I. 데이터 전송시 오류제어기법, FEC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FEC의 정의
        </div>
        <div class="para-cntnt">
            수신 측 오류 검출/정정 위해, 오류복구를 위한 여분의 비트를 추가, 전송하는 오류제어 기법
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. FEC
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. FEC의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/FEC.png" alt="FEC">
<!--            <figcaption>Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. FEC의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          주요기법 해알길터
  블럭코드 - 블럭단위로 부호화 수행
    해밍코드 - 데이터 전송시 1비트 에러 수정을위한 오류정정부호
    RS Code - 통신상 발생하는 랜덤오류, 연집오류 정정 ReedSolomon
  넌블럭코드 - 블럭을 확장하여 부호화 수행
    길쌈부호 - 현재의 입력신호에 과거일부 신호 활용 메모리를 갖는 부호화 Convolutional
    터보코드 - 길쌈부호 중에 쉽게 부화화할 수 있는 것 조합

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
