TEST PLAN

   ->If passengers seated on the car button sensor will be activated  button sensor switch closed  Button sensor on  Button sensor on  Requirement based 
   ->After passenger and driver seated, the user needs to enable the heater sensor  Heater sensor switch closed Heater sensor on Heater sensor on | Requirement based 
   ->Enabling both button and heater sensor, LED will be ON (binary output)  Both switches closed    LED ON  LED ON  Requirement based 
   ->Enabling any one of sensor not both  Any one of switche open  LED OFF LED OFF  Boundary based 
   ->Reads temperature information from temperature sensor and convert analong inputs to digital using ADC  Read ADC from temperature sensor  Successfully read and covert digital values   Successfully read and covert digital values  Requirement based 
   ->Display CDD-CRO will give the temperature value by showing PWM  Read ADC values  Successfully displayed temperature  Successfully displayed temperature  Requirement based  
  -> Display digital temperature values in serial monitor using USART communication protocol Read ADC values  Successfully displayed temperature  Successfully displayed temperature Requirement based 
