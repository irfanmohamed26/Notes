# Notes
CPU-only know Addition Basics: RAM-Primary memory storage secondary storage(hardware)->Non-volatile Memory Clock->Heart beat of CPU RAM-2 Types S-RAM : FlipFlop(made of) Static D-RAM: capacitors(made of) Dynamic ARM: Cortex A->Application Cortex R->Real time Application Cortex M->Microcontroller(Process only)

1.Static RAM is faster than Dynamic Ram BUS -> used to communicate between CPU up Computer ( Median) Pheripherals :- GPIO => To communicate environment => These are sent by ‘System Bus’ (s bus)

GPIO 1. Reading digital signals -> input 2. Issuing Interupts 3. Generating Triggers

i. Genric Pin:Values consist of one or two voltage settings.(High or Low)
ii. Behaviour can be programmed using software
Multiplexing- This pins used this method Generic part- All the pins are connected to part

output mode:open drain stage Pull up resistor ->always use 0 or 1 Gate drain source(GDS)

Pull Push Configuration(Automatic) Memory Maped : using memory to acess the I&O
Making partion in memory with address
_ _ _ _ _

15/2/24

GPTO have a memory space and address, that
memory space is called Registers.
UP108) 0×40020000-024002 O3FF
All registers for IPAD A have been inside
different address space
but only are
registers

Registers

1.Moder
2.Otyper
3.Ospeedr
4.Pudr
5.Idr
6.Odr
7.Bsrr
8.Lckr
9.Afrl
10.Afrh

MODER Register

Thin the base add

A

base address + off set :0x00

will be A (22)

stari't address will be A

OTYPER Reguter

bare addreis + offset: 0x04

inchaque by

UL>onsigned long

Pheripheral base 140020000 Pheripheral offret Loffred 20000 difference

if both addreas

ard Sarne

then the

(bare address

offset

Pheripheral Bам (periph base + AHBI periph_offlet)

will beg

[GPIOA-offt 0X0000UL

01

Number

GPIOA-BASE (AHBIPERIPH-BASE + GPIO-OFFSET)

when we we the (volatile unsigned int *) then we Call as address

Adtheer

value

The value Can be accessed by POINTER
→ GPIO A bare address will be > 0x40020000

> when we know the base address of GPIOA and we know the offset 0x00 then we can know the place.

MODER Register

Thin the base add

A

base address + off set :0x00

will be A (22)

stari't address will be A

OTYPER Reguter

bare addreis + offset: 0x04

inchaque by

UL>onsigned long

Pheripheral base 140020000 Pheripheral offret Loffred 20000 difference

if both addreas

ard Sarne

then the

(bare address

offset

Pheripheral Bам (periph base + AHBI periph_offlet)

will beg

[GPIOA-offt 0X0000UL

01

Number

GPIOA-BASE (AHBIPERIPH-BASE + GPIO-OFFSET)

when we we the (volatile unsigned int *) then we Call as address

Adtheer

value

The value Can be accessed by POINTER.
