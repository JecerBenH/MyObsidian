
```
	 __set_MSP(0x20027FFF);
       uint32_t JumpAddress = *(volatile uint32_t*)(0x1FFF0000 + 4);
       void (*boot_loader)(void) =(void (*)(void))JumpAddress;
       SYSCFG->MEMRMP = 0x1; //Remap 0x0000 0000 to System Memory
       boot_loader();
```