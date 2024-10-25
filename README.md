# DalitzPlotDKpipi
#**Dalitz plot simulation for a** $D^{+}→k^{-}\pi^{+} \pi^{+}$ **decay**
19/11/2023,

Author: Elser Lopez, Contact: elser.adolfo.lopez@gmail.com

General information

This code makes a Montecarlo simulation through the Metropolis-Hastings algorithm, following the equations for a three body decay showing into the  [PDG Kinematics review](https://pdg.lbl.gov/2023/reviews/contents_sports.html), and using the masses as: $M=m_{D}=1870$ MeV, $m_1=m_{k^{-}}=494$ MeV,  $m_{k^{*0}}=890$ MeV, $m_{2}=m_{3}=m_{\pi^{+}}=140$ MeV.  

On the other hand, the aceptance ratio uses the probability amplitud as

|M $(m_{12_{i→j}})|^2=$ $A^2$ $\frac{m_{k^{*}}^4}{(m_{12_{j}}^2-m_{k^{*}}^2)^2 +m_{k^{*}}^2\Gamma_{k^{*}}^2  }$,

where $A^2=2.18 \times 10^{-17}$ and $Γ_{k*}=50$ MeV.


In order to run this code you need the following Python Libraries:

*   numpy
*   random
*   matplotlib
*   mpl_scatter_density

This code saves two figures corresponding to the Dalitz plot from the equations and a Dalitz plot from the Montecarlo simulation. The first one is called "DalitzPlot.pdf" and the second "DalitzPlotMontecarlo.pdf"

***Finally, this code was built using Python 3.10.12; Other versions may not work.***
