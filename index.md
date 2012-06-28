---
layout: page
title: Welcome To adhown Notes
tagline: Learn For BETTER future
tags: [adhown]
---
{% include JB/setup %}

Belajar, menjadi salah satu alasan mengapa blog ini saya buat, 
sebenarnya sebelum ini saya sudah pernah membuat blog yang diantaranya 
menggunakan CMS (Content Management System) seperti joomla, Wordpress dan blogger. Lalu sekarang mengapa saya mau buat blog lagi? Ya tadi alasannya buat `BELAJAR` gan.. :-P. 

Bermula saat saya di tugaskan untuk memasang GIT di server development untuk menggantikan SVN yang sudah lama ada di server oleh pak Bos.karena saya sama sekali belum tahu apa itu `GIT`, jadi dimulailah proses pencarian apa itu GIT dengan menyelam ke dunia maya menggunakan [google]. Dalam proses pencarian ini akhirnya sedikit demi sedikit saya tahu apa itu git. GIT adalah aplikasi yang di buat untuk mengatur versi pembuatan aplikasi yang di buat oleh Om Linus Torvald, lebih lanjut baca di
[GIT][]
[GIT]: http://id.wikipedia.org/wiki/Git/ . :D .
Jadi saya mulai eksperiment memasang GIT dengan user interface nya dari gitorious seperti apa yang di sarankan si boss, seharian pun saya habiskan untuk ekplorasi tentang gitorious itu, tentunya diselingi dengan buka facebook, twitter dan youtube. :P, gitorious sendiri dibangun menggunakan bahasa pemrograman ruby di atas framework RoR (Roby on Rails) yang pada dasarnya saya sama sekali tidak mengerti, maklum masih `BELAJAR` gan. Langkah demi langkah memasang gitorious saya jalankan tapi selalu saja menemui kendala, lalu saya mencoba mencari alternatif selain gitorious, akhirnya menyelam kembali menggunakan google dan kutemukan gitlabhq. Seperti sebelumnya saya lakukan eksperimen dengan gitlabhq, dan yang ini kendalanya bisa saya lewati sampai akhirnya selesai GIT untuk server development pun berhasil dibuat dengan menggunakan gitlabhq :) .

Itu proses awalnya mengapa saya bisa bertemu dengan github ini karena gitorious dan gitlabhq sumbernya berada disini. Ketertarikan saya muncul untuk menyelam ke dalam lautan pemrograman, saat itu pula si Bos mengenalkan saya dengan bahasa yang disebut ruby, dikenalkan dengan framework ruby yang diantaranya Ruby on Rails dan Sinatra. Saya tambah semangat untuk menyelam, walau sampai sekarang belum bisa-bisa. Tapi saya belum berhenti untuk belajar menyelam, yaa kan namanya juga `BELAJAR` gak akan langsung bisa. :) #Berkilah.

Lalu, gimana ceritanya bisa bikin blog di github?? oia basa-basi nya terlalu gak nyambung ya.. :P . jadi ini juga proses belajar. Blog ini di buat dengan menggunakan jekyll. Jekyll adalah generator web statis yang dibuat dengan ruby di dukung oleh MarkDown dan Liquid. Jadi sebelum bikin web aplikasi menggunakan ruby nya, saya belajar menggunakn produk yang dibuat menggunakan ruby dulu, agar terbiasa melihat atau menggunakan syntax ruby selain itu juga, dengan membuat blog di github ini saya jadi terbiasa menggunakan `GIT`, jadi begitu alasannya. :D . makanya blog nya masih berantakan, namanya juga masih `BELAJAR`. hhee. :D

Terima kasih sudah mampir di blog saya

####Adhown Malakian
Follow me on twitter [@adhown][]
[@adhown]: http://twitter.com/adhown/

<hr>
<hr>
   
# Recent Notes :
<hr>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
