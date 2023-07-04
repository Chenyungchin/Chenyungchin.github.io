---
layout: page
title: Intelligent Dining Table
description: Arduino / Python / Raspberry Pi / Several Sensors
img: assets/img/makentu_table/cover.png
importance: 1
category: Maker Designs
---

    In collaboration with 吳瑋倫、蔡東翰、陳宥辰.

Intelligent Dining Table is our work for MakeNTU 2022 (the largest student makeathon in Taiwan), and it received the top award (Best Solver Award) and NXP enterprise award.
As everything has to be made from scratch within 24hr in makeNTU, we focused on prototyping each function to demonstrate its versatility, instead of pursuing the completeness of the work.

<h4><strong>Overview</strong></h4>
<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        <p><strong>Auto Water Filling:</strong> Place your empty cup on the conveyor, the cup will be carried to the water dispenser, filled with water, and carried back to you automatically!</p>
        <p><strong>IoT Menu:</strong> Order Here! Info will be sent to the backend!</p>
        <p><strong>Auto Illumination:</strong> Light up when human is detected!</p>
        <p><strong>Smart Tableware Placing:</strong> Distribute different tablewares based on the dish on the table!</p>
        <p><strong>Sustainable Leg:</strong> Reduce, Reuse, Recycle lol</p>
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/makentu_table/overview_mark.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<h4><strong>Auto Water Filling</strong></h4>
<strong>Weight Sensor / Arduino / Servo</strong>

<div class="row">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/makentu_table/water_filler.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="https://www.youtube.com/embed/oG9dLqHQQQQ?mute=1" width="230" height="350" title="example image" class="rounded z-depth-1"%}
    </div>
</div>

<h4><strong>IoT Menu</strong></h4>
<strong>LCD module / Arduino</strong>
<div class="row">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/makentu_table/menu.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<h4><strong>Auto Illumination</strong></h4>
<strong>NXP image sensor / Python / Arduino</strong>
<div class="row">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/makentu_table/auto_illumination.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<h4><strong>Smart Tableware Placement</strong></h4>
<strong>Pi Camera & Raspberry Pi / Python / Arduino / Servo</strong>
<div class="row">
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/makentu_table/tableware_placement.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<h4><strong>🌸 Photo Dump 🌸</strong></h4>
<div class="row justify-content-sm-center">
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.html path="assets/img/makentu_table/1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/makentu_table/2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
==================== 😎 我是分隔線 😎 tl;dr 😎 ====================
<h4><strong>🌸 作品理念 🌸 Spirit of Our Work 🌸</strong></h4>
<p>對「美」的體察往往源自生活中的寬裕。</p>
<p>試想你背負著一天份的沉重走出電子設計自動化導論課的教室，昏黃的斜陽流淌在大王椰子樹間，把時間拉得很悠長，在從總圖書館通往臺大正門的路彷彿成為了這一生的縮影。你刻意的放緩踩踏板的頻率、想起了太宰筆下的這樣的一句話:「這是生命的黃昏、藝術的黃昏，人類的黃昏。」霎時，你意識到這個世界是充滿活力的，整個夏季都為你鼓譟了起來。總是有這樣的一個瞬間，在平淡庸碌的人生裡，這一個瞬間就能讓人振奮。即使身心俱疲，卻感到無比富足。</p>
<p>你走進夕陽盡頭的那家餐館，在窗台邊的座位坐下準備療癒今日的疲憊，或望向窗外揣測臺北落日後的喧囂、或膚淺的掠過餐廳的裝潢擺設，最後聚焦在模仿拙劣的盜版名畫、或翻開已些微泛黃的書頁，耽溺在村上春樹筆下寧靜卻深邃的汪洋中，在餐點送至桌前的空閒，有意識的攝取生活中的美。</p>
<p>然而，「請你到前台點餐喔!」服務員急促而不耐煩的話語硬生生的劃開了烏托邦的簾幕，悉心建構的世界瞬間琉璃成了碎片。你才想到，自哪一天起，餐廳為了節省人力成本，把所有的服務改成自助式了，顧客不僅要自己去櫃檯點餐，還要自己裝水、拿餐具、收餐盤、結帳，原先充滿閒情逸致、讓人盡心享受的一頓晚餐，如今已然成為一場追求效率的戰鬥，時間被細碎的像是睡過頭後一手刷著牙、一手刮著鬍子，拎著尚未收好的公事包和襯衫就趕著上班的一連串競速賽，無以喘息。</p>
<p>「真的需要這樣狼狽的吃一餐嗎?」此作品的主旨，便是提供你餐前的那份寬裕，讓你能有心思去體察生活中的美。</p>