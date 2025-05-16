<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Periodic Table of the Elements</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: white;
    }
      .attribution{
      margin-top: auto;
      padding: 10px 20px;
      text-align: right;
      font-size: 14px;
    }
    .attribution a{
    
      color: blue;
      text-decoration: underline;
    }
    h1 {
      text-align: center;
    }
    .periodic-table {
      display: grid;
      grid-template-columns: repeat(18, 60px);
      gap: 2px;
      justify-content: center;
      margin: 20px auto;
    }
    .element {
      border: 1px solid #000;
      height: 60px;
      width: 60px;
      text-align: center;
      font-size: 11px;
      padding: 2px;
    }
    .placeholder {
      border: none;
      height: 60px;
      width: 60px;
    }
    .footer {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 20px;
    }
    .footer-row {
      display: flex;
      gap: 2px;
    }
    .footer-label {
      
      font-weight: bold;
      margin: 5px 0;
    }
  </style>
</head>
<body>
  <h1>Periodic Table of the Elements</h1>
  <div class="attribution">
    <p><a href="http://chemistry.about.com" target="_blank">http://chemistry.about.com</a></p>
    <p>&copy;2012 todd helmenstine <br> about chemistry</p>
  </div>
  <div class="periodic-table">
    <div class="element">H<br>1<br>1.00794</div>
    <div class="placeholder" style="grid-column: span 16"></div>
    <div class="element">He<br>2<br>4.002602</div>
    <div class="element">Li<br>3<br>6.941</div>
    <div class="element">Be<br>4<br>9.012182</div>
    <div class="placeholder" style="grid-column: span 10"></div>
    <div class="element">B<br>5<br>10.811</div>
    <div class="element">C<br>6<br>12.0107</div>
    <div class="element">N<br>7<br>14.0067</div>
    <div class="element">O<br>8<br>15.9994</div>
    <div class="element">F<br>9<br>18.9984032</div>
    <div class="element">Ne<br>10<br>20.1797</div>
    <div class="element">Na<br>11<br>22.989770</div>
    <div class="element">Mg<br>12<br>24.3050</div>
    <div class="placeholder" style="grid-column: span 10"></div>
    <div class="element">Al<br>13<br>26.9815386</div>
    <div class="element">Si<br>14<br>28.0855</div>
    <div class="element">P<br>15<br>30.973762</div>
    <div class="element">S<br>16<br>32.065</div>
    <div class="element">Cl<br>17<br>35.453</div>
    <div class="element">Ar<br>18<br>39.948</div>

    
    <div class="element">K<br>19<br>39.0983</div>
    <div class="element">Ca<br>20<br>40.078</div>
    <div class="element">Sc<br>21<br>44.955912</div>
    <div class="element">Ti<br>22<br>47.867</div>
    <div class="element">V<br>23<br>50.9415</div>
    <div class="element">Cr<br>24<br>51.9961</div>
    <div class="element">Mn<br>25<br>54.938045</div>
    <div class="element">Fe<br>26<br>55.845</div>
    <div class="element">Co<br>27<br>58.933195</div>
    <div class="element">Ni<br>28<br>58.6934</div>
    <div class="element">Cu<br>29<br>63.546</div>
    <div class="element">Zn<br>30<br>65.38</div>
    <div class="element">Ga<br>31<br>69.723</div>
    <div class="element">Ge<br>32<br>72.64</div>
    <div class="element">As<br>33<br>74.92160</div>
    <div class="element">Se<br>34<br>78.96</div>
    <div class="element">Br<br>35<br>79.904</div>
    <div class="element">Kr<br>36<br>83.798</div>
    

    <div class="element">Rb<br>37<br>85.4878</div>
    <div class="element">Sr<br>38<br>87.62</div>
    <div class="element">Y<br>39<br>88.90585</div>
    <div class="element">Zr<br>40<br>91.224</div>
    <div class="element">Nb<br>41<br>92.90638</div>
    <div class="element">Mo<br>42<br>95.98</div>
    <div class="element">Tc<br>43<br>[98]</div>
    <div class="element">Ru<br>44<br>101.07</div>
    <div class="element">Rh<br>45<br>102.90550</div>
    <div class="element">Pd<br>46<br>106.42</div>
    <div class="element">Ag<br>47<br>107.8682</div>
    <div class="element">Cd<br>48<br>112.411</div>
    <div class="element">In<br>49<br>114.818</div>
    <div class="element">Sn<br>50<br>118.710</div>
    <div class="element">Sb<br>51<br>121.760</div>
    <div class="element">Te<br>52<br>127.60</div>
    <div class="element">I<br>53<br>126.90447</div>
    <div class="element">Xe<br>54<br>131.293</div>


    <div class="element">Cs<br>55<br>85.4878</div>
    <div class="element">Ba<br>56<br>87.62</div>
    <div class="element"><br>57-71<br>Lanthanide</div>
    <div class="element">Hf<br>72<br>91.224</div>
    <div class="element">Ta<br>73<br>92.90638</div>
    <div class="element">W<br>74<br>95.98</div>
    <div class="element">Re<br>75<br>[98]</div>
    <div class="element">Os<br>76<br>101.07</div>
    <div class="element">Ir<br>77<br>102.90550</div>
    <div class="element">Pt<br>78<br>106.42</div>
    <div class="element">Au<br>79<br>107.8682</div>
    <div class="element">Hg<br>80<br>112.411</div>
    <div class="element">TI<br>81<br>114.818</div>
    <div class="element">Pb<br>82<br>118.710</div>
    <div class="element">Bi<br>83<br>121.760</div>
    <div class="element">Po<br>84<br>127.60</div>
    <div class="element">At<br>85<br>126.90447</div>
    <div class="element">Rn<br>86<br>131.293</div>
    


    <div class="element">Fr<br>87<br>[223]</div>
    <div class="element">Ra<br>88<br>[226]</div>
    <div class="element"><br>89-103<br>Actirides</div>
    <div class="element">Rf<br>104<br>[267]</div>
    <div class="element">Db<br>105<br>[268]</div>
    <div class="element">Sg<br>106<br>[271]</div>
    <div class="element">Bh<br>107<br>[272]</div>
    <div class="element">Hs<br>108<br>[270]</div>
    <div class="element">Mt<br>109<br>[276]</div>
    <div class="element">Ds<br>110<br>[281]</div>
    <div class="element">Rg<br>111<br>[280]</div>
    <div class="element">Cn<br>112<br>[285]</div>
    <div class="element">Uut<br>113<br>[284]</div>
    <div class="element">FI<br>114<br>[289]</div>
    <div class="element">Uup<br>115<br>[288]</div>
    <div class="element">Lv<br>116<br> [293]</div>
    <div class="element">Uus<br>117<br>[294]</div>
    <div class="element">Uuo<br>118<br>[294]</div>
  </div>
  
  <div class="footer">
    <div class="footer-label">Lanthanides</div>
    <div class="footer-row">
      <div class="element">La<br>57<br>138.90547</div>
      <div class="element">Ce<br>58<br>140.116</div>
      <div class="element">Pr<br>59<br>140.90765</div>
      <div class="element">Nd<br>60<br>144.24</div>
      <div class="element">Pm<br>61<br>[145]</div>
      <div class="element">Sm<br>62<br>150.36</div>
      <div class="element">Eu<br>63<br>151.964</div>
      <div class="element">Gd<br>64<br>157.25</div>
      <div class="element">Tb<br>65<br>158.92535</div>
      <div class="element">Dy<br>66<br>162.5</div>
      <div class="element">Ho<br>67<br>164.93032</div>
      <div class="element">Er<br>68<br>167.259</div>
      <div class="element">Tm<br>69<br>168.93421</div>
      <div class="element">Yb<br>70<br>173.04</div>
      <div class="element">Lu<br>71<br>174.967</div>
    </div>

    <div class="footer-label">Actinides</div>
    <div class="footer-row">
      <div class="element">Ac<br>89<br>[227]</div>
      <div class="element">Th<br>90<br>232.03806</div>
      <div class="element">Pa<br>91<br>231.03588</div>
      <div class="element">U<br>92<br>238.02891</div>
      <div class="element">Np<br>93<br>[237]</div>
      <div class="element">Pu<br>94<br>[244]</div>
      <div class="element">Am<br>95<br>[243]</div>
      <div class="element">Cm<br>96<br>[247]</div>
      <div class="element">Bk<br>97<br>[247]</div>
      <div class="element">Cf<br>98<br>[251]</div>
      <div class="element">Es<br>99<br>[252]</div>
      <div class="element">Fm<br>100<br>[257]</div>
      <div class="element">Md<br>101<br>[258]</div>
      <div class="element">No<br>102<br>[259]</div>
      <div class="element">Lr<br>103<br>[262]</div>
    </div>
  </div>
</body>
</html>
