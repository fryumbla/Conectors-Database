---
layout: archive
permalink: /tolerance/
title: "Tolerance Dataset: Mating Process of Plug-in Cable Connectors for Wire Harness Assembly Tasks"
author_profile: false
header:
  image: "/images/tolerance/b1.jpg"
---

Francisco Yumbla, June-Sup Yi, Meseret Abayebas, Mahir Shafiyev, Hyungpil Moon

Journal link: https://link.springer.com/article/10.1007%2Fs11370-019-00307-5

## Resume
<P ALIGN="justify">In this research, we studied the mating tolerance of various plug-in cable connectors and provide a mating tolerance data set of 70 different connectors. 
This data set will be highly advantageous to industries for wire harness assembly tasks using robots. Understanding the mating tolerance is crucial for automating the mating process because it  is closely related to the control specifications of a robotic manipulator. Our system uses a 2-finger Robotiq adaptive gripper attached to a 6 degree-of-freedom industrial robot (ABB Robotics) to test the mating process of wire harness assembly tasks. In addition, we use 70 types of wire harness connectors with different numbers of pins widths, lengths, and thicknesses, and various shapes, to test the mating tolerance. The results indicate that the connector mating tolerance of our data set is more generous than the repeatability of conventional industrial  manipulators, and further demonstrate the suitability  of the position control methods to wire harness assembly tasks. </P>

## Mating process test
<P ALIGN="center"><img src="{{ site.url }}{{ site.baseurl }}/images/tolerance/testprocess.jpg" width="700"></P>

<iframe width="560" height="315" src="https://www.youtube.com/embed/avqnbM4VFvM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Repeatability of the mating process
<P ALIGN="justify">This section explains the test to validate the accuracy and the repeatability of the ABB robot arm of the cable in the current analysis. We use a different program path, but the final frame is the position of the female connector to the male connector at the millimeter bed. After measuring the tolerance, this test can be begun. This experiment involves moving the Robotiq Adaptive Gripper multiple times in different positions. In this experiment, the female connector always returns to the mating process (with the male connector being at the millimeter bed). The program uses 5 different robot positions with different paths. Thus, we checked the mating process 100 times, as shown in the video clip. </P>

<iframe width="560" height="315" src="https://www.youtube.com/embed/VYBXj_857Lg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Tolerance Database
<P ALIGN="justify">We used a different class of cable connectors for this experiments. Commonly, these connectors have been used in wiring harness assembly system. All connectors tested in our system and we made a tolerance database.</P>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;border-color:#aaa;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:0px 7px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aaa;color:#333;background-color:#fff;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:0px 7px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:#aaa;color:#fff;background-color:#f38630;}
.tg .tg-9j82{background-color:#FCFBE3;border-color:#000000;text-align:center}
.tg .tg-obcv{border-color:#000000;text-align:center}
</style>
<table class="tg">
  <tr>
    <th class="tg-obcv">N.</th>
    <th class="tg-obcv">Picture</th>
    <th class="tg-obcv">Class</th>
    <th class="tg-obcv">Brand</th>
    <th class="tg-obcv">Part Number</th>
    <th class="tg-obcv">Pines</th>
    <th class="tg-obcv">Tolerance in <br>Z direction(mm)</th>
    <th class="tg-obcv">Tolerance in <br>X direction(mm)</th>
  </tr>
  <tr>
    <td class="tg-9j82">1</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/1.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C1</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82"><a href="https://www.molex.com/molex/products/datasheet.jsp?part=active/2451320205_CABLE_ASSEMBLIES.xml&channel=Products&Lang=en-US">2451320205</a></td>
    <td class="tg-9j82">2</td>
    <td class="tg-9j82">0.49</td>
    <td class="tg-9j82">0.49</td>
  </tr>
  <tr>
    <td class="tg-obcv">2</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/2.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C1</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv"><a href="https://www.molex.com/molex/products/datasheet.jsp?part=active/2451320405_CABLE_ASSEMBLIES.xml&channel=Products&Lang=en-US">2451320405</a></td>
    <td class="tg-obcv">4</td>
    <td class="tg-obcv">0.50</td>
    <td class="tg-obcv">0.45</td>
  </tr>
  <tr>
    <td class="tg-9j82">3</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/3.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C1</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82"><a href="https://www.molex.com/molex/products/datasheet.jsp?part=active/2451320605_CABLE_ASSEMBLIES.xml&channel=Products&Lang=en-US">2451320605</a></td>
    <td class="tg-9j82">6</td>
    <td class="tg-9j82">0.41</td>
    <td class="tg-9j82">0.55</td>
  </tr>
  <tr>
    <td class="tg-obcv">4</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/4.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C2</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv"><a href="https://www.digikey.com/product-detail/en/molex-llc/2451350205/WM15748-ND/6564765">2451350205</a></td>
    <td class="tg-obcv">2</td>
    <td class="tg-obcv">0.63</td>
    <td class="tg-obcv">0.58</td>
  </tr>
  <tr>
    <td class="tg-9j82">5</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/5.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C2</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82"><a href="https://www.digikey.com/product-detail/en/molex-llc/2451350405/WM15751-ND/6564768">2451350405</a></td>
    <td class="tg-9j82">4</td>
    <td class="tg-9j82">0.61</td>
    <td class="tg-9j82">0.58</td>
  </tr>
  <tr>
    <td class="tg-obcv">6</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/6.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C2</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv"><a href="https://www.digikey.com/product-detail/en/molex-llc/2451350605/WM15754-ND/6564771">2451350605</a></td>
    <td class="tg-obcv">6</td>
    <td class="tg-obcv">0.64</td>
    <td class="tg-obcv">0.66</td>
  </tr>
  <tr>
    <td class="tg-9j82">7</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/7.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C3</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82"><a href="https://www.molex.com/molex/products/datasheet.jsp?part=active/0436450200_CRIMP_HOUSINGS.xml&channel=Products">0436450200</a></td>
    <td class="tg-9j82">2</td>
    <td class="tg-9j82">0.35</td>
    <td class="tg-9j82">0.43</td>
  </tr>
  <tr>
    <td class="tg-obcv">8</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/8.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C3</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv"><a href="https://www.molex.com/molex/products/datasheet.jsp?part=active/0436450400_CRIMP_HOUSINGS.xml&channel=Products&Lang=en-US">0436450400</a></td>
    <td class="tg-obcv">4</td>
    <td class="tg-obcv">0.43</td>
    <td class="tg-obcv">0.42</td>
  </tr>
  <tr>
    <td class="tg-9j82">9</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/9.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C3</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82"><a href="https://www.digikey.com/product-detail/en/molex-llc/0436450600/WM1849-ND/268978">0436450600</a></td>
    <td class="tg-9j82">6</td>
    <td class="tg-9j82">0.35</td>
    <td class="tg-9j82">0.27</td>
  </tr>
  <tr>
    <td class="tg-obcv">10</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/10.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C4</td>
    <td class="tg-obcv">Amphenol SINE Systems</td>
    <td class="tg-obcv"><a href="https://www.digikey.com/product-detail/en/amphenol-sine-systems-corp/AT2PS-CKIT/889-1234-ND/4415018">AT2PS-CKIT</a></td>
    <td class="tg-obcv">2</td>
    <td class="tg-obcv">0.70</td>
    <td class="tg-obcv">1.23</td>
  </tr>
  <tr>
    <td class="tg-9j82">11</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/11.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C4</td>
    <td class="tg-9j82">Amphenol SINE Systems</td>
    <td class="tg-9j82"><a href="https://www.digikey.com/product-detail/en/amphenol-sine-systems-corp/AT3PS-CKIT/889-1235-ND/4415019">AT3PS-CKIT</a></td>
    <td class="tg-9j82">3</td>
    <td class="tg-9j82">1.15</td>
    <td class="tg-9j82">1.13</td>
  </tr>
  <tr>
    <td class="tg-obcv">12</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/12.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C4</td>
    <td class="tg-obcv">Amphenol SINE Systems</td>
    <td class="tg-obcv"><a href="https://www.digikey.com/product-detail/en/amphenol-sine-systems-corp/AT6PS-CKIT/889-1237-ND/4415021">AT6PS-CKIT</a></td>
    <td class="tg-obcv">6</td>
    <td class="tg-obcv">1.03</td>
    <td class="tg-obcv">1.05</td>
  </tr>
  <tr>
    <td class="tg-9j82">13</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/13.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C5</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82"><a href="https://www.digikey.com/product-detail/en/molex-llc/0528520570/WM11072CT-ND/5171187">0528520570</a></td>
    <td class="tg-9j82">5</td>
    <td class="tg-9j82">0.84</td>
    <td class="tg-9j82">0.70</td>
  </tr>
  <tr>
    <td class="tg-obcv">14</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/14.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C5</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv"><a href="https://www.digikey.com/product-detail/en/molex-llc/0528521070/WM11076CT-ND/5171195">0528521070</a></td>
    <td class="tg-obcv">10</td>
    <td class="tg-obcv">1.13</td>
    <td class="tg-obcv">0.51</td>
  </tr>
  <tr>
    <td class="tg-9j82">15</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/15.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C5</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82"><a href="https://www.digikey.com/product-detail/en/molex-llc/0528521670/WM3395CT-ND/2405613">0528521670</a></td>
    <td class="tg-9j82">16</td>
    <td class="tg-9j82">1.13</td>
    <td class="tg-9j82">0.53</td>
  </tr>
  <tr>
    <td class="tg-obcv">16</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/16.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C5</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv"><a href="https://www.digikey.com/product-detail/en/molex-llc/0528522070/WM11080CT-ND/5171203">0528522070</a></td>
    <td class="tg-obcv">20</td>
    <td class="tg-obcv">1.08</td>
    <td class="tg-obcv">0.53</td>
  </tr>
  <tr>
    <td class="tg-9j82">17</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/17.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C5</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82"><a href="https://www.digikey.com/product-detail/en/molex-llc/0528522670/WM20339CT-ND/8638604">0528522670</a></td>
    <td class="tg-9j82">26</td>
    <td class="tg-9j82">1.18</td>
    <td class="tg-9j82">0.33</td>
  </tr>
  <tr>
    <td class="tg-obcv">18</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/18.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C6</td>
    <td class="tg-obcv">Digilent</td>
    <td class="tg-obcv">6-pin MTE Cable</td>
    <td class="tg-obcv">3</td>
    <td class="tg-obcv">1.00</td>
    <td class="tg-obcv">1.40</td>
  </tr>
  <tr>
    <td class="tg-9j82">19</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/19.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C6</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82">5239-04</td>
    <td class="tg-9j82">4</td>
    <td class="tg-9j82">1.70</td>
    <td class="tg-9j82">2.05</td>
  </tr>
  <tr>
    <td class="tg-obcv">20</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/20.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C6</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv">5239-05</td>
    <td class="tg-obcv">5</td>
    <td class="tg-obcv">1.55</td>
    <td class="tg-obcv">1.90</td>
  </tr>
  <tr>
    <td class="tg-9j82">21</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/21.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C6</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82">5239-06</td>
    <td class="tg-9j82">6</td>
    <td class="tg-9j82">1.65</td>
    <td class="tg-9j82">1.75</td>
  </tr>
  <tr>
    <td class="tg-obcv">22</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/22.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C6</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv">5239-08</td>
    <td class="tg-obcv">8</td>
    <td class="tg-obcv">1.60</td>
    <td class="tg-obcv">2.05</td>
  </tr>
  <tr>
    <td class="tg-9j82">23</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/23.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C6</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82">5239-09</td>
    <td class="tg-9j82">9</td>
    <td class="tg-9j82">1.40</td>
    <td class="tg-9j82">1.90</td>
  </tr>
  <tr>
    <td class="tg-obcv">24</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/24.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C6</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv">5239-10</td>
    <td class="tg-obcv">10</td>
    <td class="tg-obcv">1.60</td>
    <td class="tg-obcv">2.00</td>
  </tr>
  <tr>
    <td class="tg-9j82">25</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/25.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">YEONHO</td>
    <td class="tg-9j82">SMH250-05</td>
    <td class="tg-9j82">5</td>
    <td class="tg-9j82">1.65</td>
    <td class="tg-9j82">1.20</td>
  </tr>
  <tr>
    <td class="tg-obcv">26</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/26.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C7</td>
    <td class="tg-obcv">ELEPARTS</td>
    <td class="tg-obcv">PM1802</td>
    <td class="tg-obcv">2</td>
    <td class="tg-obcv">1.65</td>
    <td class="tg-obcv">1.25</td>
  </tr>
  <tr>
    <td class="tg-9j82">27</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/27.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">YEONHO</td>
    <td class="tg-9j82">SMH250-04</td>
    <td class="tg-9j82">4</td>
    <td class="tg-9j82">1.50</td>
    <td class="tg-9j82">1.00</td>
  </tr>
  <tr>
    <td class="tg-obcv">28</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/28.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C7</td>
    <td class="tg-obcv">YEONHO</td>
    <td class="tg-obcv">SMH250-08</td>
    <td class="tg-obcv">8</td>
    <td class="tg-obcv">1.50</td>
    <td class="tg-obcv">0.95</td>
  </tr>
  <tr>
    <td class="tg-9j82">29</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/29.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">ELEPARTS</td>
    <td class="tg-9j82">SMH250-03</td>
    <td class="tg-9j82">3</td>
    <td class="tg-9j82">1.45</td>
    <td class="tg-9j82">0.85</td>
  </tr>
  <tr>
    <td class="tg-obcv">30</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/30.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C7</td>
    <td class="tg-obcv">YEONHO</td>
    <td class="tg-obcv">SMH250-10</td>
    <td class="tg-obcv">10</td>
    <td class="tg-obcv">1.55</td>
    <td class="tg-obcv">0.85</td>
  </tr>
  <tr>
    <td class="tg-9j82">31</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/31.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">YEONHO</td>
    <td class="tg-9j82">SMH250-12</td>
    <td class="tg-9j82">12</td>
    <td class="tg-9j82">0.68</td>
    <td class="tg-9j82">0.53</td>
  </tr>
  <tr>
    <td class="tg-obcv">32</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/32.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C7</td>
    <td class="tg-obcv">YEONHO</td>
    <td class="tg-obcv">SMH250-11</td>
    <td class="tg-obcv">11</td>
    <td class="tg-obcv">0.65</td>
    <td class="tg-obcv">0.65</td>
  </tr>
  <tr>
    <td class="tg-9j82">33</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/33.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">YEONHO</td>
    <td class="tg-9j82">SMH250-10</td>
    <td class="tg-9j82">10</td>
    <td class="tg-9j82">0.77</td>
    <td class="tg-9j82">0.60</td>
  </tr>
  <tr>
    <td class="tg-obcv">34</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/34.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C7</td>
    <td class="tg-obcv">YEONHO</td>
    <td class="tg-obcv">SMH250-09</td>
    <td class="tg-obcv">9</td>
    <td class="tg-obcv">0.73</td>
    <td class="tg-obcv">0.55</td>
  </tr>
  <tr>
    <td class="tg-9j82">35</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/35.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">YEONHO</td>
    <td class="tg-9j82">SMH250-08</td>
    <td class="tg-9j82">8</td>
    <td class="tg-9j82">0.80</td>
    <td class="tg-9j82">0.68</td>
  </tr>
  <tr>
    <td class="tg-obcv">36</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/36.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C7</td>
    <td class="tg-obcv">YEONHO</td>
    <td class="tg-obcv">SMH250-07</td>
    <td class="tg-obcv">7</td>
    <td class="tg-obcv">0.77</td>
    <td class="tg-obcv">0.60</td>
  </tr>
  <tr>
    <td class="tg-9j82">37</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/37.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">YEONHO</td>
    <td class="tg-9j82">SMH250-06</td>
    <td class="tg-9j82">6</td>
    <td class="tg-9j82">0.70</td>
    <td class="tg-9j82">0.55</td>
  </tr>
  <tr>
    <td class="tg-obcv">38</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/38.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C7</td>
    <td class="tg-obcv">YEONHO</td>
    <td class="tg-obcv">SMH250-05</td>
    <td class="tg-obcv">5</td>
    <td class="tg-obcv">0.68</td>
    <td class="tg-obcv">0.51</td>
  </tr>
  <tr>
    <td class="tg-9j82">39</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/39.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">YEONHO</td>
    <td class="tg-9j82">SMH250-04</td>
    <td class="tg-9j82">4</td>
    <td class="tg-9j82">0.73</td>
    <td class="tg-9j82">0.50</td>
  </tr>
  <tr>
    <td class="tg-obcv">40</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/40.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C7</td>
    <td class="tg-obcv">YEONHO</td>
    <td class="tg-obcv">SMH250-03</td>
    <td class="tg-obcv">3</td>
    <td class="tg-obcv">0.75</td>
    <td class="tg-obcv">0.43</td>
  </tr>
  <tr>
    <td class="tg-9j82">41</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/41.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C7</td>
    <td class="tg-9j82">YEONHO</td>
    <td class="tg-9j82">SMH250-02</td>
    <td class="tg-9j82">2</td>
    <td class="tg-9j82">0.78</td>
    <td class="tg-9j82">0.58</td>
  </tr>
  <tr>
    <td class="tg-obcv">42</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/42.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C8</td>
    <td class="tg-obcv">ELEPARTS</td>
    <td class="tg-obcv">MO0101</td>
    <td class="tg-obcv">1</td>
    <td class="tg-obcv">1.10</td>
    <td class="tg-obcv">1.85</td>
  </tr>
  <tr>
    <td class="tg-9j82">43</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/43.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C8</td>
    <td class="tg-9j82">ELEPARTS</td>
    <td class="tg-9j82">MO0102</td>
    <td class="tg-9j82">2</td>
    <td class="tg-9j82">1.60</td>
    <td class="tg-9j82">1.40</td>
  </tr>
  <tr>
    <td class="tg-obcv">44</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/44.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C8</td>
    <td class="tg-obcv">ELEPARTS</td>
    <td class="tg-obcv">MO0103</td>
    <td class="tg-obcv">3</td>
    <td class="tg-obcv">1.65</td>
    <td class="tg-obcv">1.85</td>
  </tr>
  <tr>
    <td class="tg-9j82">45</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/45.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C8</td>
    <td class="tg-9j82">ELEPARTS</td>
    <td class="tg-9j82">MO0104</td>
    <td class="tg-9j82">4</td>
    <td class="tg-9j82">0.95</td>
    <td class="tg-9j82">1.00</td>
  </tr>
  <tr>
    <td class="tg-obcv">46</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/46.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C9</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv">0340620025</td>
    <td class="tg-obcv">2</td>
    <td class="tg-obcv">1.26</td>
    <td class="tg-obcv">1.68</td>
  </tr>
  <tr>
    <td class="tg-9j82">47</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/47.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C9</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82">0334710206</td>
    <td class="tg-9j82">2</td>
    <td class="tg-9j82">1.16</td>
    <td class="tg-9j82">1.01</td>
  </tr>
  <tr>
    <td class="tg-obcv">48</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/48.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C9</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv">0334710306</td>
    <td class="tg-obcv">3</td>
    <td class="tg-obcv">0.88</td>
    <td class="tg-obcv">0.87</td>
  </tr>
  <tr>
    <td class="tg-9j82">49</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/49.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C9</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82">0334710406</td>
    <td class="tg-9j82">4</td>
    <td class="tg-9j82">0.63</td>
    <td class="tg-9j82">0.79</td>
  </tr>
  <tr>
    <td class="tg-obcv">50</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/50.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C10</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv">5557-16R</td>
    <td class="tg-obcv">8</td>
    <td class="tg-obcv">0.95</td>
    <td class="tg-obcv">0.95</td>
  </tr>
  <tr>
    <td class="tg-9j82">51</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/51.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C10</td>
    <td class="tg-9j82">MOLEX</td>
    <td class="tg-9j82">5557-10R</td>
    <td class="tg-9j82">10</td>
    <td class="tg-9j82">0.95</td>
    <td class="tg-9j82">0.75</td>
  </tr>
  <tr>
    <td class="tg-obcv">52</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/52.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C10</td>
    <td class="tg-obcv">MOLEX</td>
    <td class="tg-obcv">5557-12R</td>
    <td class="tg-obcv">12</td>
    <td class="tg-obcv">0.90</td>
    <td class="tg-obcv">0.80</td>
  </tr>
  <tr>
    <td class="tg-9j82">53</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/53.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C11</td>
    <td class="tg-9j82">ELEPARTS</td>
    <td class="tg-9j82">PC1802</td>
    <td class="tg-9j82">2</td>
    <td class="tg-9j82">1.00</td>
    <td class="tg-9j82">1.05</td>
  </tr>
  <tr>
    <td class="tg-obcv">54</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/54.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C12</td>
    <td class="tg-obcv">ELEPARTS</td>
    <td class="tg-obcv">PC1602</td>
    <td class="tg-obcv">2</td>
    <td class="tg-obcv">1.60</td>
    <td class="tg-obcv">1.65</td>
  </tr>
  <tr>
    <td class="tg-9j82">55</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/55.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C11</td>
    <td class="tg-9j82">ELEPARTS</td>
    <td class="tg-9j82">PC1603</td>
    <td class="tg-9j82">3</td>
    <td class="tg-9j82">1.10</td>
    <td class="tg-9j82">1.25</td>
  </tr>
  <tr>
    <td class="tg-obcv">56</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/56.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C12</td>
    <td class="tg-obcv">ELEPARTS</td>
    <td class="tg-obcv">PC1604</td>
    <td class="tg-obcv">4</td>
    <td class="tg-obcv">2.10</td>
    <td class="tg-obcv">1.60</td>
  </tr>
  <tr>
    <td class="tg-9j82">57</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/57.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C11</td>
    <td class="tg-9j82">ELEPARTS</td>
    <td class="tg-9j82">PC1606</td>
    <td class="tg-9j82">6</td>
    <td class="tg-9j82">1.25</td>
    <td class="tg-9j82">1.40</td>
  </tr>
  <tr>
    <td class="tg-obcv">58</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/58.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C13</td>
    <td class="tg-obcv">DEVICEMART</td>
    <td class="tg-obcv">DJ7021A-2.8</td>
    <td class="tg-obcv">2</td>
    <td class="tg-obcv">0.40</td>
    <td class="tg-obcv">0.83</td>
  </tr>
  <tr>
    <td class="tg-9j82">59</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/59.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C13</td>
    <td class="tg-9j82">DEVICEMART</td>
    <td class="tg-9j82">DJ7031A-2.8</td>
    <td class="tg-9j82">3</td>
    <td class="tg-9j82">0.58</td>
    <td class="tg-9j82">1.06</td>
  </tr>
  <tr>
    <td class="tg-obcv">60</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/60.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C13</td>
    <td class="tg-obcv">DEVICEMART</td>
    <td class="tg-obcv">DJ7041A-2.8</td>
    <td class="tg-obcv">4</td>
    <td class="tg-obcv">0.46</td>
    <td class="tg-obcv">0.37</td>
  </tr>
  <tr>
    <td class="tg-9j82">61</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/61.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C13</td>
    <td class="tg-9j82">DEVICEMART</td>
    <td class="tg-9j82">DJ7061A-2.8</td>
    <td class="tg-9j82">6</td>
    <td class="tg-9j82">0.26</td>
    <td class="tg-9j82">0.85</td>
  </tr>
  <tr>
    <td class="tg-obcv">62</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/62.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C13</td>
    <td class="tg-obcv">DEVICEMART</td>
    <td class="tg-obcv">DJ7091A-2.8</td>
    <td class="tg-obcv">9</td>
    <td class="tg-obcv">0.45</td>
    <td class="tg-obcv">0.77</td>
  </tr>
  <tr>
    <td class="tg-9j82">63</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/63.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C14</td>
    <td class="tg-9j82">DEVICEMART</td>
    <td class="tg-9j82">DJ7011A-6.3</td>
    <td class="tg-9j82">1</td>
    <td class="tg-9j82">1.47</td>
    <td class="tg-9j82">1.29</td>
  </tr>
  <tr>
    <td class="tg-obcv">64</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/64.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C14</td>
    <td class="tg-obcv">DEVICEMART</td>
    <td class="tg-obcv">DJ7021A-6.3</td>
    <td class="tg-obcv">2</td>
    <td class="tg-obcv">1.94</td>
    <td class="tg-obcv">1.37</td>
  </tr>
  <tr>
    <td class="tg-9j82">65</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/65.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C14</td>
    <td class="tg-9j82">DEVICEMART</td>
    <td class="tg-9j82">DJ7031A-6.3</td>
    <td class="tg-9j82">3</td>
    <td class="tg-9j82">0.90</td>
    <td class="tg-9j82">0.93</td>
  </tr>
  <tr>
    <td class="tg-obcv">66</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/66.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C14</td>
    <td class="tg-obcv">DEVICEMART</td>
    <td class="tg-obcv">DJ7041A-6.3</td>
    <td class="tg-obcv">4</td>
    <td class="tg-obcv">1.47</td>
    <td class="tg-obcv">1.14</td>
  </tr>
  <tr>
    <td class="tg-9j82">67</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/67.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C14</td>
    <td class="tg-9j82">DEVICEMART</td>
    <td class="tg-9j82">DJ7061A-6.3</td>
    <td class="tg-9j82">6</td>
    <td class="tg-9j82">1.54</td>
    <td class="tg-9j82">1.27</td>
  </tr>
  <tr>
    <td class="tg-obcv">68</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/68.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C15</td>
    <td class="tg-obcv">DEVICEMART</td>
    <td class="tg-obcv">DJ7031A-6.3</td>
    <td class="tg-obcv">3</td>
    <td class="tg-obcv">0.31</td>
    <td class="tg-obcv">0.65</td>
  </tr>
  <tr>
    <td class="tg-9j82">69</td>
    <td class="tg-9j82"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/69.jpg" height="400" width="400"></td>
    <td class="tg-9j82">C15</td>
    <td class="tg-9j82">DEVICEMART</td>
    <td class="tg-9j82">DJ7041A-6.3</td>
    <td class="tg-9j82">4</td>
    <td class="tg-9j82">0.38</td>
    <td class="tg-9j82">0.76</td>
  </tr>
  <tr>
    <td class="tg-obcv">70</td>
    <td class="tg-obcv"><img src="{{ site.url }}{{ site.baseurl }}/images/cables/70.jpg" height="400" width="400"></td>
    <td class="tg-obcv">C15</td>
    <td class="tg-obcv">DEVICEMART</td>
    <td class="tg-obcv">DJ7061A-6.3</td>
    <td class="tg-obcv">6</td>
    <td class="tg-obcv">0.36</td>
    <td class="tg-obcv">0.50</td>
  </tr>
</table>