---
layout: default
title: "About"
permalink: "/about/"
press:
  - article_date: 2021 JUN 17
    article_title: Conversations with Robby Good
    article_link: http://voyagela.com/interview/conversations-robby-good/?fbclid=IwAR2SyXmAeHqkv0Ub_YI4zXO3P9G7Xv7zeWICPsfziPXcDm9WwXCDUr2nUcE
    author: VoyageLA
  - article_date: 2021 APR 27
    article_title: Music students combine compositions, visual components in virtual spring showcase
    article_link: https://dailybruin.com/2021/04/27/music-students-combine-compositions-visual-components-in-virtual-spring-showcase
    author: Daily Bruin - David Egan
  - article_date: 2021 FEB 17
    article_title: YouthMundus Artist Spotlight - Robby Good
    article_link: https://www.innervoiceartists.com/post/robby-good
    author: Inner Voice Artists - Naomi Segal
  - article_date: 2017 MAY 5
    article_title: LA Phil Composer Fellow Robby Good Commissioned to Compose New Work for the National Children's Chorus
    article_link: https://www.laphil.com/press/releases/1634
    author: Los Angeles Philharmonic/Hollywood Bowl Press Release
header:
    image_fullwidth_staff: Kian_Header_idea_9.png
---

<div class="row t30">
	<div class="medium-10 columns medium-offset-1 end">
			<header>
				<div itemprop="name">
					<h1 class="text-center">About</h1>
				</div>
			</header>
            <div itemprop="articleSection">
                <img class="b30" src="{{ site.urlimg }}kian_homepage2_square.jpeg" alt="Headshot of Kian Ravaei" class="wrap-left" style="width:50%;">
                <p>Robby Good (b. July 2, 2000, Valencia, CA) is a current music composition and percussion performance major at UCLA. He considers himself primarily a composer for films, animations, video games, and all forms of visual media, though he composes numerous concert and chamber works as well. Robby has been playing piano from the age of 6, picking up percussion at age 9, and composing at the age of 12. During high school, he was accepted into the Nancy and Barry Sanders Los Angeles Philharmonic Composer Fellowship Program, where he studied under Andrew Norman (USC/Juilliard) and Sarah Gibson (USC/UCSB). Robby has also studied with Ian Krouse (UCLA), Derrick Skye (LACO/Bridge to Everywhere), David Lefkowitz (UCLA) and Kay Rhie (UCLA), and has been a music production mentee under the guidance of visual media composer/performer Michael A. Levine.</p>
                <p>Robby has scored over 20 films and animations from students at UCLA, CalArts, Chapman University, Pratt Institute, Sarah Lawrence College, and more. His score for the short film, <a href="{{ site.url }}{{ site.baseurl }}/visual-media/in-your-own-blood/"><i>In Your Own Blood</i></a>, won the award for Best Original Score in the London International Monthly Film Festival. Robby has also provided the scores to a number of video games developed within game jams, and is currently working on the music for the upcoming <a href="https://www.youtube.com/channel/UCoIWNv3mHri8Oy6JPp4r7qw"><i>Project: Eden's Garden</i></a>, a game heavily inspired by the <i>Danganronpa</i> series of video games.</p>
                <p>Robby’s concert works have been premiered by ensembles such as the Los Angeles Philharmonic, the International Contemporary Ensemble (ICE), the National Children’s Chorus (NCC), the Los Angeles Percussion Quartet (LAPQ), the Calder String Quartet, the Kaleidoscope Chamber Orchestra, Winsor Music, Ensemble TM+, and the CSUN Wind Ensemble.</p>
                <p>As a performer, Robby studied piano/keyboard for 10 years with Richard Parizer from Robot Nature, and has studied percussion with Matt Cook (LAPQ). He currently studies with UCLA Professors Gregory Goodall and Theresa Dimond.</p>
            </div>
            <div>
                <a href="{{ site.url }}{{ site.baseurl }}/visual-media/" class="button expand">Visual Media ›</a>
            </div>
            <div>
                <a href="{{ site.url }}{{ site.baseurl }}/works/" class="button expand">All Performative Works ›</a>
            </div>
            <div>
                <a href="https://www.imdb.com/name/nm11572939/?ref_=nv_sr_srsg_1" class="button expand">Check out my IMDB! ›</a>
            </div>
            <div>
            
            <!--Press-->


<div class="text-center t30">
					<h1 class="h1">Press</h1>
				</div>
    {% capture now %}{{'now' | date: '%s' | plus: 0 }}{% endcapture %}
                {% for item in page.press %}
                {% assign not-title = NULL %}
                {% capture date %}{{item.article_date | date: '%s' | plus: 0 }}{% endcapture %}
                {% if date < now %}
<div class="row">
                    <hr>
  <div class="small-5 columns">
    <p class="performance-date text-right">{{ item.article_date }}</p>
    </div>
  <div class="small-7 columns">
    <ul class="no-bullet">
                    <li style="font-size:20px;"><a href="{{ item.article_link }}"><b>{{ item.article_title }}</b></a></li>
                    {% if item.author %}
                    <li style="color:dimgray;">{{ item.author }}</li>
                    {% endif %}
      </ul>
      </div>
    </div>
      {% endif %}
                {% endfor %}


</div> <!-- /.row -->
</div>






<!--Saving this because of how much work it took me-->
<!--<p>His name is pronounced [<a href="https://en.wikipedia.org/wiki/Voiceless_velar_stop" target="_blank">k</a><a href="https://en.wikipedia.org/wiki/Close_front_unrounded_vowel" target="_blank">i</a><a href="https://en.wikipedia.org/wiki/Voiced_palatal_approximant" target="_blank">j</a><a href="https://en.wikipedia.org/wiki/Open_back_rounded_vowel" target="_blank">&#594;</a><a href="https://en.wikipedia.org/wiki/Voiced_dental,_alveolar_and_postalveolar_nasals" target="_blank">n</a> <a href="https://en.wikipedia.org/wiki/Voiced_dental_and_alveolar_taps_and_flaps" target="_blank">&#638;</a><a href="https://en.wikipedia.org/wiki/Near-open_front_unrounded_vowel" target="_blank">&#230;</a><a href="https://en.wikipedia.org/wiki/Voiced_labiodental_fricative" target="_blank">v</a><a href="https://en.wikipedia.org/wiki/Open_back_rounded_vowel" target="_blank">&#594;</a><a href="https://en.wikipedia.org/wiki/Vowel_length" target="_blank">&#720;</a><a href="https://en.wikipedia.org/wiki/Close_front_unrounded_vowel" target="_blank">i</a><a href="https://en.wikipedia.org/wiki/Vowel_length" target="_blank">&#720;</a>].</p>-->
