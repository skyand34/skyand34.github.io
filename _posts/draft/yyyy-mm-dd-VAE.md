---
title: VAE
#author: 
date: 2023-09-27 00:00:10 +0800
categories: [PE, 인공지능]
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
      I. 가우시안 분포 활용, VAE 의 정의
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. VAE의 정의
        </div>
        <div class="para-cntnt">
            평균(μ)과 표준편차(σ)를 학습하고 입력 데이터와 유사한 새로운 데이터를 생성하는 오토인코더
        </div>
      </div>
    </div>
  </div>
  
  <div class="para">
    <div class="para-title">
      II. VAE
    </div>
    <div class="para-cntnt">
      <div class="para">
        <div class="para-title">
          가. VAE의 아키텍처
        </div>
        <div class="para-cntnt">
          <figure class="post-figure">
            <img src="/assets/img/posts/VAE.png" alt="VAE">
<!--            <figcaption>Unveiling the Metaverse: Exploring Emerging Trends, Multifaceted Perspectives, and Future Challenges</figcaption>-->
          </figure>
        </div>
      </div>
      <div class="para">
        <div class="para-title">
          나. VAE의 구성요소
        </div>
        <div class="para-cntnt">
          <table class="post-table">
          </table>
          구성요소 인디라정변증
  모델구조
    Encoder - 입력데이터 저차원 표현 압축
    Decoder - 입력 동일크기 출력데이터 생성
  잠재공간
    정규분포 - 입력특징의 평균과 분산
    Latent Vector - Sampling통한 Overfitting제거
  모델학습
    변분추론
    증거하한

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
