Copyright (C) 2018 Theia Space, Universidad Politécnica de Madrid

This file is part of Theia Space's ESAT driver setup for Windows 7.

Theia Space's ESAT driver setup for Windows 7 is free software: you
can redistribute it and/or modify it under the terms of the GNU
General Public License as published by the Free Software Foundation,
either version 3 of the License, or (at your option) any later
version.

Theia Space's ESAT driver setup for Windows 7 is distributed in the
hope that it will be useful, but WITHOUT ANY WARRANTY; without even
the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR
PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Theia Space's ESAT driver setup for Windows 7.  If not, see
<http://www.gnu.org/licenses/>.


Theia Space's ESAT driver setup for Windows 7.  Use it to connect
Theia Space's ESAT boards as USB virtual serial/COM ports to computers
running Windows 7 (not necessary for Windows 10 or other non-Windows
operating systems).

Supported boards:

  * Theia Space's ESAT Attitude Determination and Control Subsystem
    (ESAT ADCS, STM32L4-based).
  * Theia Space's ESAT Communications Subsystem
    (ESAT COM, MSP430-based).
  * Theia Space's ESAT Electrical Power Subsystem
    (ESAT EPS, MSP430-based).
  * Theia Space's ESAT On-Board Computer
    (ESAT OBC, MSP430-based).

Use ESAT.inf as the driver/device installation file for Theia Space's
ESAT boards programmed using the Theia Space's ESAT core for the
Arduino platform:

  * For MSP430-based boards, using the Arduino core for MSP430-based
    ESAT boards (Theia Space's ESAT Boards (MSP430)) version 3.0.0
    or a newer 3.x.y version.
  * For STM32L4-based boards, using the Arduino core for STM32L4-based
    ESAT boards (Theia Space's ESAT Boards (STM32L4)) version 1.0.0
    or a newer 1.x.y version.
