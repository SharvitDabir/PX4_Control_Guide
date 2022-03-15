# PX4_Autopilot_Firmware_Guide
This documentation was started as part of CERLAB-Control team at Carnegie Mellon University, for the educational purpose of understanding and documenting the PX4 multicopter control architecture. This documentation (for "PX4 Stable Release v1.12.3") is a work-in-progress and is expected to be completed by May 2022. All rights reserved by PX4 Development Team. 
# Disclaimer as seen on PX4-Autopilot github repository:
/****************************************************************************
 *
 *   Copyright (C) 2018 - 2019 PX4 Development Team. All rights reserved.
 *
 * Redistribution and use in source and binary forms, with or without
 * modification, are permitted provided that the following conditions
 * are met:
 *
 * 1. Redistributions of source code must retain the above copyright
 *    notice, this list of conditions and the following disclaimer.
 * 2. Redistributions in binary form must reproduce the above copyright
 *    notice, this list of conditions and the following disclaimer in
 *    the documentation and/or other materials provided with the
 *    distribution.
 * 3. Neither the name PX4 nor the names of its contributors may be
 *    used to endorse or promote products derived from this software
 *    without specific prior written permission.
 *
 * THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
 * "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
 * LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
 * FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
 * COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
 * INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
 * BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS
 * OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED
 * AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
 * LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
 * ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
 * POSSIBILITY OF SUCH DAMAGE.
 *
 ****************************************************************************/
 
# Some illustrations from the Document:
<img width="1457" alt="for_github2" src="https://user-images.githubusercontent.com/73812796/158051219-385dc9b2-8f55-42d9-83af-f53f0362f4b6.PNG">

<img width="914" alt="for_github" src="https://user-images.githubusercontent.com/73812796/158051174-1acb7b42-85d8-4aa4-b245-7b662b0c5d72.PNG">
 
# Some illustrations related to Thrust-Update:
 <img width="679" alt="for_git" src="https://user-images.githubusercontent.com/73812796/158295317-54b58bd6-9370-4e91-83b2-5c096558a325.PNG">

# Some illustrations related to Attitude-Controller:
<img width="1009" alt="for_git2" src="https://user-images.githubusercontent.com/73812796/158295356-fa9d119c-9cd2-4a96-9274-1eb267f2d00b.PNG">

