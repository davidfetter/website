---
layout: default
title: What is a fast reactor?
category: reactors
description: Explains what a fast nuclear reactor is and the differences between fast and thermal reactors.
author: Nick Touran
---
<div class="row">
<div class="col-md-6" markdown="1">
    
<h2>What is a <i>fast</i> reactor? </h2>
<h5>By Nick Touran, September 2009. Editing by Jesse Cheatham, Robert Petroski, and Brian Wagner</h5>
         
Fast reactors are a class of advanced nuclear reactors that have some key advantages
over traditional reactors in safety, sustainability, and waste. While traditional
reactors contain moderators to slow down neutrons after they&rsquo;re emitted, fast
reactors keep their neutrons moving quickly (hence the name). Fast neutrons can unlock
the energy in the dominant isotope of uranium (U238) and thus extend known fuel resources
by around 200x. Your average thermal neutron moves around at about 2200 m/s while a fast
neutron might be cruising well above 9 million m/s, which is about 3% of the speed of
light.

This page discusses the pros, cons, history, and physics of fast reactors

</div>
<div class="col-md-6" markdown="1">

<p>&nbsp;</p>

<img alt="A fast neutron" title="A fast neutron... get it?" style="border:0;width:250px" src="img/fast_neutron.png"/>
### On this page:
<ul>
<li><a href="#bigdeal">What&rsquo;s the big deal with fast reactors?</a></li>
<li><a href="#history">Some history</a></li>
<li><a href="#splittingmore">Splitting more U-238 than usual</a></li>
<li><a href="#havingmore">Having more neutrons flying around</a></li>
<li><a href="#howtomake">How to make a fast reactor</a></li>
<li><a href="#refs">See also</a></li>
</ul>

</div>
</div>
<div class="row">
<div class="col-md-6" markdown="1">
<a name="bigdeal"></a>   
## Pros

* Fast reactors get more neutrons out of their primary fuel than thermal reactors,
  so many can be used to <a href="{% link recycling.md %}">breed new fuel</a>,
  vastly <b>enhancing the sustainability</b> of nuclear power.

* Fast reactors are capable of destroying the longest-lived nuclear waste, transforming
  it to waste that decays to harmlessness in <b>centuries rather than hundreds of
  millennia</b>.

* Fast reactors typically use liquid metal coolants rather than water. These have
  superior heat-transfer properties and allow natural circulation to remove the heat
  in even severe accident scenarios. The result: if something goes very wrong at the
  plant, and none of the operators are awake, AND none of the control rods work, the
  reactor can just <b>naturally shut itself down</b>. This comes with a con (see cons).

* Fast reactors can employ metallic fuel rather than oxides (thanks to chemical
  compatibility with the liquid metal coolant). Since metal has very high thermal
  conductivity, the reactor can shut itself down without surpassing temperature
  limits. This <b>enhances the safety</b> of these reactors significantly. 

</div>

<div class="col-md-6" markdown="1">
## Cons

* While fast reactors are up to 200x more resource efficient, they require 3x or more
  fissile atoms to start up initially. This is the main reason why thermal reactors were
  developed first.

* Time scales in fast reactors are typically faster than those
  in thermal reactors (mostly because there are fewer <i>delayed neutrons</i> in fast
  reactors). Thus they can  <b>go through unpredicted changes faster</b> than thermal
  reactors. 

* Bubbles in fast reactor coolant can cause the reactor to heat up rather than cool
  down, as in a traditional reactor. Higher heat makes more bubbles, which make more
  heat, and so on. This <b>positive feedback is scary</b> (but manageable, thanks to
  overpowering negative feedbacks).

* To keep the neutrons moving quickly, fast
  reactors <b>require exotic coolants</b> derived from heavy atoms. The most common coolant
  is liquid sodium, which is well known but highly reactive with air and water. Another is
  liquid lead-bismuth eutectic, which isn&rsquo;t the most pleasant material either. These
  bizarre materials require extra care and lower tolerance in many systems (such as piping),
  possibly <b>bringing costs up</b>.
</div>
</div>
 <div class="row">
<div class="col-md-8" markdown="1">
<h2 id="history">Some history</h2>

From the beginning of nuclear power, we knew the benefits of fast reactors. Uranium was
thought to be a very scarce resource, so breeder reactors were considered essential.
Enrico Fermi postulated the possibility of breeding, and this possibility was confirmed in
the EBR-1 reactor in Idaho (which, incidentally was also the first reactor to produce
electricity). Several other fast test reactors were built around the world (in France, the
UK, Japan, Russia, India, China) and today, the world has achieved around 400
reactor-years of operation with fast reactors. 

<div class="alert alert-success" role="alert" markdown="1">
**Note:** We have an elaborate <a href="{% link
reactor_history.md %}">reactor development history page</a> that covers this topic in general.
</div>

Uranium was found to be plentiful, and the commercial nuclear industry favored the
already-developed and operating thermal reactors. Also, <a href="{% link recycling.md
%}">recycling nuclear fuel</a> (as is often but not always called for in fast reactor fuel
cycles) brings up <a href="{% link non-proliferation.md %}">proliferation concerns</a>
that inspired the Jimmy Carter administration to cancel a large US effort to develop a
fast-reactor system. Nowadays, with talk of expanding the share of nuclear power in the
electricity-producing world, debate about the remaining amount of uranium on earth has
resurfaced. Why switch from coal to uranium if we might run out in a few centuries anyway?
Also, one of the only ways to really destroy nuclear waste is to burn it in fast reactors.
So, by providing good responses to the sustainability and the waste toxicity, fast
reactors have maintained the interest of much of the forward-looking nuclear crowd. 


<h2 id="details">Technical Details</h2>
It might be wise to go read <a href="{% link moderation.html %}">our moderation
page</a> for a second and come back when you understand that neutrons emerge from
fission reactions at high speeds and that we typically like to slow them down to thermal
energies in order to increase their chances of continuing the chain reaction. This is what
is done in thermal reactors.  

Splitting atoms is not the only thing neutrons do. In nuclides such as Uranium-238,
thermal neutrons are readily absorbed without causing a fission -- resulting in what we
call a capture. The probability for capture also increases dramatically at thermal
energies. We have measured through experiments that the chances that a neutron will cause
a capture rather than a fission in Uranium-238 are high at thermal energies and become
smaller at faster energies. Take a look at these two graphs showing the probability
(called the cross-section in nuclear lingo) of capture and the probability of fission as a
function of neutron energy for U-235 and U-238. By the way, the units of energy used here
are electron-volts (eV), where 1 eV is the energy that an electron would gain in an
electric field with 1 Volt.

<table style="border:0;margin:0.0em 0 0.0em 0px;"><tr>
<td style="height:0.0em; padding:0px 0px 0px 0px; border-left:solid 0px rgb(0,0,0); border-right:solid 0px rgb(255,255,255); border-top:solid 0px rgb(255,255,255); border-bottom:solid 0px rgb(255,255,255); background-color:rgb(255,255,255); text-align:left; font-weight:normal; color:rgb(80,80,80); font-size:110%;"><img style="width:400px;float:left;" src="img/u235-cap-fiss.png" alt="capture and fission cross sections of U235"/></td><td style="height:0.0em; padding:0px 0px 0px 0px; border-left:solid 0px rgb(0,0,0); border-right:solid 0px rgb(255,255,255); border-top:solid 0px rgb(255,255,255); border-bottom:solid 0px rgb(255,255,255); background-color:rgb(255,255,255);"><img style="width:400px;" src="img/u238-capture-fission.png" alt="capture and fission cross sections of U-238" /></td>
</tr>
</table>

<h2 id="splittingmore">Fast reactors split more atoms of U-238 than usual</h2>
Depending on the enrichment, our fuel&rsquo;s properties will be a mixture of these
two plots. In order to sustain a chain reaction, the number of neutrons produced from
fissions needs to be higher than the number of neutrons lost to capture (and a few
other loss mechanisms like leakage out of the reactor). As you can see, if all our
neutrons had more than 10<sup>6</sup> eV, U-238 would be nearly as good a fuel as
U-235. In reality, it&rsquo;s very difficult to keep the neutrons moving that quickly
so fast reactors still need a bit of enriched uranium to operate, but U-238 is
fissioned to much more of a degree than in thermal reactors. As an added bonus, many
of the very long-lived nuclides larger than Uranium (Neptunium, Plutonium, Americium,
Curium, etc.) have the same trend, and fast reactors can split and destroy these
actinides as fuel rather than let them accumulate as in thermal reactors. This makes
the nuclear waste coming out of fast reactors decay to natural radiation levels much
faster than traditional nuclear waste. 



<h2 id="havingmore">Fast reactors have high breeding ratios and more neutrons going around</h2>

<table><tr><td>
<a href="img/breeding_ratio.png"><img style="width:400px" src="img/breeding_ratio.png" alt="plot of U238 absorption and Pu239 fission vs. energy" /></a>	</td><td>
<a href="img/nubar.png"><img style="width:400px" src="img/nubar.png" alt="plot of neutrons per fission as a function of energy for uranium and plutonium" /></a></td></tr></table>

The breeding ratio is a measure of how much new fissile fuel a reactor is capable of
producing as it runs. It is the ratio of the number of fissile atoms created with the
number of fissions occurring. 

Fast reactors using uranium fuel inherently create more fissile atoms per fission that
uranium-fueled thermal reactors. The reason can be seen in the image to the right labeled
&quot;breeding ratio&quot;. In thermal reactors, Pu239 fissions as soon as it is created
because the Pu239 fission rate is so much higher than the U238 absorption rate (which is
what creates fissile material). Conversely, fast reactors have U238 absorption rates that
are comparable to Pu239 fission rates. Thus, the fissile material can be replenished as it
burns. This also explains why initial enrichment of fast reactors has to be higher than
comparable thermal reactors. 

The number of neutrons per fission changes in fast reactors as well. When atoms
fission, they release a few neutrons that continue a chain reaction. When a faster neutron
splits a Uranium atom, odds are that more neutrons will come out than if a thermal neutron
hit it. This effect means that fast reactors have extra neutrons around that aren&rsquo;t
necessary for maintaining the chain reaction. Additionally, since more U-238 is directly
fissioning, there are neutrons being produced from non-fissile  material. These two
effects increase the breeding ratio even further. It can be larger than 1 in fast
reactors. This means that the bonus neutrons can be used to <a href="{% link recycling.md
%}">breed new fuel</a> in <i>fast breeder reactors</i>. The big picture effect is that
U238 is usable as fuel instead of just U235. There is over 100x more U238 in nature than
U235, so the time that 200 years of uranium can last humanity turns into 20,000.

There are also significantly more free neutrons in fast reactors. Since the probability of
fission is lower for faster energies for every actinide, the neutron density is higher in
fast reactors than it is in most thermal reactors of the same power (since power is
effectively the neutron density multiplied by the fission probability). Structural
materials inside fast reactors thus undergo higher radiation damage rates than those in
thermal reactors. 

<h2 id="howtomake">How to we make a reactor fast or thermal?</h2>
Nuclear reactors need to cool fuel as they undergoes the fission chain reaction.
Water is the standard coolant of other power plants for various reasons (it plays well
with steam turbines, is clean, is plentiful, has decent thermal properties, etc.), so
it was an obvious candidate for nuclear reactors. Luckily, it doesn&rsquo;t eat up too
many neutrons through capture, so it turned out to be a feasible choice. Water
contains lots of hydrogen atoms, with mass of 1 atomic mass unit. Being the same
weight as neutrons, conservation of momentum and energy tell us that a neutron
striking a hydrogen atom can slow down all the way from super fast to zero in one
collision (imagine a billiard ball striking a stationary one), so water coolant is
very good at slowing fast neutrons down to thermal energies. If you want to keep your
neutrons moving quickly, you don&rsquo;t want any small atoms around, so you choose a
heavier coolant, like sodium (imagine a billiard ball striking a bowling ball). So to
make a fast reactor, just take all the small atoms out. Some fast reactors use oxide
fuels, but those made with metallic fuel are even faster, since oxygen is a fairly
light atom.


<h1>Why do fast reactors use hexagonal assemblies?</h1>
Ok, this isn&rsquo;t really a commonly asked question in public, but whatever. Of all
the geometric shapes in the world, hexagons can be packed closest together, in an
arrangement known as <a
href="https://en.wikipedia.org/wiki/Sphere_packing#Circle_packing">hexagonal close-packing
[wikipedia]</a>. In order to get nuclear fuel as close together as possible, to make the
chain reaction easy, hexagons are the obvious choice. So the real question is why are
thermal reactor assemblies square? Since they require moderation, designers don&rsquo;t
want thermal fuel as close as possible to itself. The extra room is specifically to be
filled with moderator, which is usually water. 

Another good reason to use hexagons is that fast reactors can become more reactive when
fuel is pushed closer together. To minimize the possibility of this, we like to get it as
close together to begin with.  


<!--<div class="column1-unit">
<h1>What is our operating experience with fast reactors?</h1>
<p>The first nuclear reactor that generated electricity was a fast breeder reactor. </p>
</div>
<hr class="clear-contentunit" />-->


<h2 id="refs">See Also</h2>
<ul> 
<li>Our <a href="{% link recycling.md %}">breeding and recycling page</a></li>
<li><a href="https://en.wikipedia.org/wiki/Fast_neutron_reactor">Fast neutron reactor [wikipedia]</a> - Wikipedia has a decent page on these guys, with a list of all that have operated. </li>
<li><a href="http://www.nndc.bnl.gov/sigma/index.jsp">The National Nuclear Data Center</a>, from where all the cross-section data are taken (Happy, <a href="http://atomicinsights.blogspot.com/2008/05/imagining-scale-of-energy-storage.html">Rod</a>?)</li>

</ul>
<p> Questions? Comments? Send us <a href="contact.html">a note</a>.</p>

<h2>References</h2>
<p>Here are some good overview references for continued learning</p>
<ol>
<li><a href="http://www-pub.iaea.org/books/IAEABooks/7581/Fast-Reactor-Database-2006-Update">The Fast Reactor Database, IAEA-TECDOC-1531</a></li>
<li><a href="http://www-pub.iaea.org/books/IAEABooks/8667/Status-of-Fast-Reactor-Research-and-Technology-Development">Status of Fast Reactor Research and Technology Development, IAEA TECDOC 1691</a></li>
</ol>
</div>
</div>
     
      
