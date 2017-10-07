# Diode Rectifier
## Half Wave Rectifier
## Full Wave Rectifier
## Bridge Rectifier
## Solid State Bridge Rectifier

### Digital voltmeter using ICL7107

<b>Description:</b>

The circuit given here is of a very useful and accurate digital voltmeter with LED display using the ICL7107 from Intersil. The ICL7107 is a high performance, low power, 3.5 digit analog to digital converter. The IC includes internal circuitry for seven segment decoders, display drivers, reference voltage source1 and a clock. The power dissipation is less than 10mW and the display stability is very high.

The working of this electronic circuit is very simple. The voltage to be measured is converted into a digital equivalent by the ADC inside the IC and then this digital equivalent is decoded to the seven segment format and then displayed. The ADC used in ICL7107 is dual slope type ADC. The process taking place inside our ADC can be stated as follows. For a fixed period of time the voltage to be measured is integrated to obtain a ramp at the output of the integrator. Then a known reference voltage of opposite polarity is applied to the input of the integrator and allowed to ramp until the output of integrator becomes zero. The time taken for the negative slope to reach zero is measured in terms of the IC’s clock cycle and it will be proportional to the voltage under measurement. In simple words, the input voltage is compared to an internal reference voltage and the result is converted in a digital format.

The resistor R2 and C1 are used to set the frequency of IC’s internal clock. Capacitor C2 neutralizes the fluctuations in the internal reference voltage and increases the stability of the display.R4 controls the range of the voltmeter. Right most three displays are connected so that they can display all digits. The left most display is so connected that it can display only “1” and “-“.The pin5(representing the dot) is connected to ground only for the third display and its position needs to be changed when you change the range of the volt meter by altering R4. (R4=1.2K gives 0-20V range, R4=12K gives 0-200V range ).

<i>Circuit Diagram:</i>
