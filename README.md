# GSM-Base-Module

Proteus 9.2 versiyonu ile çizilmiştir. Alt versiyon ile açamazsınız.

### Özellikler
* İşlemci ->stm32f103c8t6
* GSM Modul->sim800
* Usb port
* 5v->3v voltaj regulatoru(mcu beslemesi için)
* 5 v->4.1v voltaj regulatoru(sim800 beslemesi için önerilen güc konfigurasyonu)
* stm boot0 ve boot1 secim switch'i,
* 4 adet led
* Nano sim konnektoru


### Pin Haritası

-------------------------------------------------------------------------


-----------Sim800c------------------

sim800c_uart1_rx->stm_uart1_tx_PA2
sim800c_uart1_tx->stm_uart1_rx_PA3

sim800c_powerkey->stm_PB13

sim800c_status->stm_PB12

sim800c_Uart1_r1_Behaviors->stm_PB14

-------------STM-------------------

stm_PA13->internal_led_indicator


-------------------------------------------------------------------------









