---
layout: default
title: "About"
permalink: "/about/"
header:
    image_fullwidth_staff: Robby_Header.png
---

<div class="row t30">
	<div class="medium-10 columns medium-offset-1 end">
			<header>
				<div itemprop="name">
					<h1 class="text-center">About</h1>
				</div>
			</header>
            <div itemprop="articleSection">
                <img class="b30" src="{{ site.urlimg }}robby_about.jpg" alt="Robby Good playing vibraphone" class="wrap-left" style="width:50%;">
                <p>Robby Good (b. July 2, 2000, Valencia, CA) is a current master's student at the UCLA Herb Alpert School of Music for composition in visual media. He graduated from UCLA's undergraduate music program in 2022 with a double degree in composition and percussion performance, with a minor in film. During high school, he was accepted into the Nancy and Barry Sanders Los Angeles Philharmonic Composer Fellowship Program, where he studied under Andrew Norman (USC/Juilliard) and Sarah Gibson (USC/UCSB). Robby has also studied with Peter Golub (UCLA), Ian Krouse (UCLA), Derrick Skye (LACO/Bridge to Everywhere), David Lefkowitz (UCLA) and Kay Rhie (UCLA), and has been a music production mentee under the guidance of visual media composer/performer Michael A. Levine and an intern of film and television composer Charles Fox.</p>
                <p>Robby has scored over 30 films and animations from students at UCLA, CalArts, Chapman University, Pratt Institute, Sarah Lawrence College, and more. His score for the short film, <a href="{{ site.url }}{{ site.baseurl }}/visual-media/in-your-own-blood/"><i>In Your Own Blood</i></a>, won the award for Best Original Score in the London International Monthly Film Festival. Robby has also provided the scores to a number of video games developed within game jams, and is currently working on the music for the upcoming <a href="https://www.youtube.com/channel/UCoIWNv3mHri8Oy6JPp4r7qw"><i>Project: Eden's Garden</i></a>, a game heavily inspired by the <i>Danganronpa</i> series of video games. Outside of virtual mediums for visual media, Robby was also the primary composer and orchestrator for the musical theater production <a href="{{ site.url }}{{ site.baseurl }}/songs/distopia/"><i>Dis-Topia</i></a>, which premiered at Chapman University in November 2021.</p>
                <p>Robby’s concert works have been premiered by ensembles such as the Los Angeles Philharmonic, the International Contemporary Ensemble (ICE), the National Children’s Chorus (NCC), the Los Angeles Percussion Quartet (LAPQ), the Calder String Quartet, the Kaleidoscope Chamber Orchestra, Winsor Music, Ensemble TM+, Diotima Quartor, and the CSUN Wind Ensemble.</p>
                <p>As a performer, Robby studied piano/keyboard for 10 years with Richard Parizer from Robot Nature, and has studied percussion with Matt Cook (LAPQ), and with Professors Gregory Goodall and Theresa Dimond at UCLA.</p>
            </div>
            <div>
                <a href="{{ site.url }}{{ site.baseurl }}/visual-media/" class="button expand">Visual Media ›</a>
            </div>
            <div>
                <a href="{{ site.url }}{{ site.baseurl }}/works/" class="button expand">All Performative Works ›</a>
            </div>
            <div>
                <a href="{{ site.url }}{{ site.baseurl }}/songs/" class="button expand">Songs and Other Projects ›</a>
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
{% for item in site.press reversed %}
    {% assign not-title = NULL %}
    {% capture date %}{{item.date | date: '%s' | plus: 0 }}{% endcapture %}
    {% if date < now %}
        <div class="row">
            <hr>
            <div class="small-5 columns">
                <p class="performance-date text-right">{{ item.date | date_to_string }}</p>
            </div>
            <div class="small-7 columns">
                <ul class="no-bullet">
                    <li style="font-size:20px;"><a href="{{ item.link }}"><b>{{ item.title }}</b></a></li>
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
