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

## PX4 MultiCopter Control Architecture 
### Only POSITION and YAW setpoints sent from companion computer through the TrajectorySetpoints topic
![PX4_MC_Architecture](https://github.com/user-attachments/assets/8f2d38c6-ba3f-4e58-809e-da4585c64b25)

### POSITION, VELOCITY, ACCELERATION, YAW and YAWSPEED setpoints sent from companion computer through the TrajectorySetpoints topic
![PX4_MC_Control_Architecture_Trajectory_Setpoints](https://github.com/user-attachments/assets/7e61abd1-268f-4e1b-83f3-b22a74af0fc1)

