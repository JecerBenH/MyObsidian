- `STATUS`: This register contains various status flags and control bits that control the operation of the PIC.
    
    ​
    
    Some of the important bits in the STATUS register are:
    
    ​
    
    - Bit 5 (RP0): This bit is used to select the bank of memory that is being accessed.
        
        When RP0 is set to 1, Bank 1 is selected.
        
        ​
        
        When RP0 is set to 0, Bank 0 is selected.
        
        ​
    - Bit 4 (TO): This bit is set when a Timer0 overflow occurs.
    - Bit 3 (PD): This bit is used to put the PIC into sleep mode.
    - Bit 2 (Z): This bit is set when the result of an arithmetic or logic operation is zero.
        
        ​
    - Bit 0 (C): This bit is set when there is a carry or borrow in an arithmetic or logic operation.
        
        ​
- `TRISA`: This register is used to configure the individual pins of Port A as either inputs or outputs.
    
    ​
    
    Each bit in the TRISA register corresponds to a pin on Port A.
    
    ​
    
    When a bit is set to 1, the corresponding pin is configured as an input.
    
    ​
    
    When a bit is set to 0, the corresponding pin is configured as an output.
    
    ​
    
- `TRISB`: This register is used to configure the individual pins of Port B as either inputs or outputs.
    
    ​
    
    Each bit in the TRISB register corresponds to a pin on Port B.
    
    ​
    
    When a bit is set to 1, the corresponding pin is configured as an input.
    
    ​
    
    When a bit is set to 0, the corresponding pin is configured as an output.
    
    ​
    
- `PORTA`: This register is used to read the state of the individual pins of Port A when they are configured as inputs.
    
    ​
    
    Each bit in the PORTA register corresponds to a pin on Port A.
    
    ​
    
    When a bit is set to 1, the corresponding pin is high.
    
    ​
    
    When a bit is set to 0, the corresponding pin is low.
    
    ​
    
- `PORTB`: This register is used to read the state of the individual pins of Port B when they are configured as inputs.
    
    ​
    
    Each bit in the PORTB register corresponds to a pin on Port B.
    
    ​
    
    When a bit is set to 1, the corresponding pin is high.
    
    ​
    
    When a bit is set to 0, the corresponding pin is low.
    
    ​
    
- `W`: This register is a general-purpose register that can be used for temporary storage of data.
    
    ​
    
    It is commonly used for arithmetic and logic operations.
    
    ​
    
- `COUNT`: This register is a user-defined variable that can be used to store a count or a value.
    
    ​
    
    Its purpose and usage depend on the specific program being written.
    
    ​
    
- `TEMP`: This register is a user-defined variable that can be used to store temporary data.
    
    ​
    
    Its purpose and usage depend on the specific program being written.
    
    ​
    
- `INTCON`: This register contains various interrupt control bits that control the behavior of interrupts in the PIC.
    
    ​
    
    Some of the important bits in the INTCON register are:
    
    ​
    
    - Bit 7 (GIE): This bit enables or disables all interrupts in the PIC.
        
        ​
    - Bit 4 (INTE): This bit enables or disables the RB0/INT external interrupt.
        
        ​
    - Bit 1 (INTF): This bit is set when the RB0/INT external interrupt occurs.
        
        ​
- `OPTION_REG`: This register contains various control bits that configure the behavior of the PIC's internal peripherals.
    
    ​ Some of the important bits in the OPTION_REG register are:
    
    - Bit 7 (NOT_RBPU): This bit enables or disables the weak pull-up resistors on Port B.
        
        ​
    - Bit 3 (T0CS): This bit selects the source for Timer0. When T0CS is set to 1, Timer0 uses the external clock on the T0CKI pin.
        
        When T0CS is set to 0, Timer0 uses the internal instruction clock.
        
        ​
    - Bit 2 (T0SE): This bit selects the edge on which Timer0 increments. When T0SE is set to 1, Timer0 increments on the falling edge of the external clock. When T0SE is set to 0, Timer0 increments on the rising edge of the external clock.
    - Bit 0 (PSA): This bit selects whether the prescaler is assigned to Timer0 or Timer1.
        
        ​
        
        When PSA is set to 1, the prescaler is assigned to Timer0.
        
        ​
        
        When PSA is set to 0, the prescaler is assigned to Timer1.
        
        ​