# SGCCcode

These codes are the demos of our SGCC approach. The recommeded enviroment for our codes is Visaul Studio 2010 on a Windows PC.

"HM_16.0_SGCC_416X240.zip" is for 416X240 sequences.

"HM_16.0_SGCC_832X480.zip" is for 832X480 sequences.

"HM_16.0_SGCC_1920X1080.zip" is for 1920X1080 sequences.

"HM_16.0_SGCC_2560X1600.zip" is for 2560X1600 sequences.

NOTICE:

1. These demo codes only support HEVC bitstreams encoded by HM with the default GOP structure in "encoder_randomaccess_main.cfg", i.e., GOP size = 8 and I frames period is 8/16/32/64/128/256. For bitstreams encoded by other settings, these codes need to be modified according to our paper. 

2. These demos are more suitable for bitstreams whose frame-level QPs are in the range of 22 to 41. For other QPs, these codes are also usable, but leading to the decrease of control accuracy. That is bacause the authors only trained the models of QPs in the range of 22 to 41.  To use these codes on other QPs, the user should train the model first. The training method can be obtained from our paper, or by contacting the auther (yangren@buaa.edu.cn).

Any questions about the code or our paper, please contact yangren@buaa.edu.cn, Maixu@buaa.edu.cn.

Thank you.

Best regards.
