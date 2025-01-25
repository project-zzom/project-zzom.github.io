---
layout: page
title: 프로덕트
permalink: /products
comments: false
---

<div class="row">
    <div class="col">
        <h2>ZZOM 제품 공식 페이지</h2>
        <ul>
            <li><a href="https://zzom.io/character-illustration-with-procreate/" target="_blank">캐릭터 일러스트 강좌 with 프로크리에이트</a></li> 
            <li><a href="https://zzom.io/scrum-master/" target="_blank">출근했더니 스크럼 마스터가 된 건에 관하여</a></li>
            <li><a href="https://zzom.io/graphic-recording/" target="_blank">처음 배우는 그래픽 레코딩</a></li>
            <li><a href="https://zzom.io/planning-hwatu/" target="_blank">플래닝 화투</a></li>
        </ul>
    </div>
</div>

<!-- Products 
================================================== -->
<section class="featured-posts">
    <h2>관련 기사</h2>
    <div class="row">
    {% for post in site.posts %}
        {% if post.product == true %}
            {% include productbox.html %}
        {% endif %}
    {% endfor %}
    </div>
</section>
