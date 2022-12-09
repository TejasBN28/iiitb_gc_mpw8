# iiitb_gc - gray counter
The focus of this project is to implement an 8-bit gray code counter in skywater 130nm and determine its functional, pre-layout and post layout characteristics (namely power, performance and area). <br><br>

# 1. Introduction
Gray code counter is a digital counter that counts such that each successive bit patterns differs by only one bit. Unlike normal counters, there are no glitches in the count pattern (0 -> 1 -> 3 -> 2 -> 6 -> 7 ......... ). Since switching is less in gray code counters (i.e., exactly one-bit switches in one clock cycle), the power consumption of the gray code counter is significantly less compared to the normal counter.


# 2. Application of Gray Counter
Gray code finds application in multiple electromechanical applications due to its error resilient property. This is achieved due to the single bit change from one code word to the adjacent next code word. This article lists down few more applications of Gray code. 
 - Since the Gray code reduces the likelihood of mistakes, it is employed in the transmission of digital signals.
 - In angle-measuring equipment, the Gray code is chosen over the simple binary code. The likelihood of an angle being misread is virtually eliminated when using the Gray code, compared to when using straight binary to express the angle. The Gray code's cyclic characteristic comes in handy for this application.
 - The axes of Karnaugh maps, a graphical method for minimising Boolean equations, are labelled using the Gray code.
 - Gray codes are used to access programme memory in computers in a way that uses the least amount of electricity. Less address lines are changing state as the programme counter advances as a result.
 - Given that mutations in the code often only allow for gradual modifications, grey codes are also particularly helpful in genetic algorithms. On occasion, though, a little adjustment might cause a significant jump, giving rise to novel traits.
 - The gray code counter has applications in analog to digital converters.
