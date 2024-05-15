---
layout: page
title: 프로덕트
permalink: /products
comments: false
---



<div class="row justify-content-between">
    <div class="col-md-8 pr-5">
        <h2>ZZOM 번역서</h2>
        프로젝트를 통해 출간한 도서는 다음과 같습니다.

        <ul>
            <li><a href="https://zzom.io/zzom-character-illustration-with-procreate/" target="_blank">캐릭터 일러스트 강좌 with 프로크리에이트</a></li> (크라우드펀딩 준비 중)
            <li><a href="https://zzom.io/scrum-master/" target="_blank">출근했더니 스크럼 마스터가 된 건에 관하여</a></li>
            <li><a href="https://zzom.io/graphic-recording/" target="_blank">처음 배우는 그래픽 레코딩</a></li>
        </ul>

        <h2>ZZOM 굿즈</h2>
        프로젝트를 통해 기획된 굿즈는 다음과 같습니다.

        <ul>
            <li><a href="https://zzom.io/planning-hwatu/" target="_blank">플래닝 화투</a></li>
            <li><a href="https://tumblbug.com/scrum-master" target="_blank">개발자 팔찌</a></li>
            <li><a href="https://tumblbug.com/graphicrecording" target="_blank">그래픽 레코딩 워크북</a></li>
        </ul>
        
    </div>

    <div class="col-md-4">
        <div class="sticky-top sticky-top-80">
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/7xxa6D8Otrw?si=IG5VibJzhbAVxuLj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <br/>
            <div class="video-container">
                <iframe src="https://www.youtube.com/embed/x3_9hbuEhG4?si=XH4Mu9x58TXdntGf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
        </div>
    </div>
</div>

<!-- Products 
================================================== -->
<section class="featured-posts">
    <div class="section-title">
        <h2><span>관련 기사</span></h2>
    </div>
    <div class="row">
    {% for post in site.posts %}
        {% if post.product == true %}
            {% include productbox.html %}
        {% endif %}
    {% endfor %}
    </div>
</section>
