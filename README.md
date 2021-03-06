## HitchHike - Practical Backscatter using Commodity WiFi
- Author: Pengyu Zhang
- Contact: pyzhang@cs.stanford.edu
- Description: This repo hosts the hardware and software needed for running the HitchHike ECG sensing demo. We demonstrate that HitchHike can inject the ECG sensor data on top existing WiFi traffic. The HitchHike system can support transmission of other sensor data with small software modification.

## Videos
- Project video: please check the HitchHike project video <a href="https://www.youtube.com/watch?v=q7fCElntD9g&t=2s">here</a>.
- Demo video: please check the ECG sensing demo video <a href="https://www.youtube.com/watch?v=r6Lh5ftg3C8">here</a>. Once you download all the software and hardware, you should be able to reproduce the ECG sensing demo.

## License
- The hardware and software source code of the HitchHike platform is distributed under academic license to ensure the reproducibility of our results. The hardware and software can NOT be used for commercial purpose.

## Hardware and software
- HitchHike_hardware includes the files needed for fabricating the HitchHike PCB board.

- HitchHike_FPGA_code includes the files needed for running the codeword translation.

- ECG_sensor_hardware inlcudes the files needed for fabricating the ECG sensing PCB board.

- ECG_sensor_software inlcudes the files needed for sending the ECG sensor data to the HitchHike hardware platform.

- apple_computer_software inlcudes the files needed for receiving the backscattered WiFi packets and extracting the ECG sensor data.

- Details of how to run the HitchHike system is shown in the following document.
https://docs.google.com/document/d/1yD-POD4OKe0HTxtUZdOaUgfRqkNDYJDK3f1_O2Xi9FA

## References
* Technical paper:<br>
HitchHike: Practical Backscatter using Commodity WiFi<br>
Pengyu Zhang, Dinesh Bharadia, Kiran Joshi, Sachin Katti<br>
SenSys 2016<br>
* Demo paper:<br>
Enabling backscatter communication among commodity wifi radios<br>
Pengyu Zhang, Dinesh Bharadia, Kiran Joshi, Sachin Katti<br>
SIGCOMM 2016<br>
