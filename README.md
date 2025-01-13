## llama2.c_dos
<p align="center">
  <img src="assets/llama_dos.webp " width="300" height="300" alt="Cute Llama">
</p>
這是一個 llama2.c 推理的 DOS 實做版本，主要作者是各種 LLM 模型，上传者做修改让其可以正常在 DOS 上执行，并且加上DEMO。

[DEMO](https://yl01inve.github.io/test001/demo/)

This is a DOS implementation version of llama2.c for inference. The main authors are various LLM models. The uploader modified it to run properly on DOS and added a [DEMO](https://yl01inve.github.io/test001/demo/).
## ch1
 

## 疑難排解(Troubleshooting)
### 1. DJGPP 在 DOSBox 下无法编译的问题 / DJGPP Compilation Issue in DOSBox

在使用 **DJGPP** 编译器时，有时会遇到无法在 **DOSBox** 环境中正常编译的情况。此时，可以通过修改 **DOSBox** 配置文件来解决该问题。当使用 **DJGPP** 编译器时，可能会遇到无法正常在 **DOSBox** 环境中编译的问题。这个问题可以通过修改 **DOSBox** 配置文件来解决。

When using the **DJGPP** compiler, sometimes compilation fails to work properly in the **DOSBox** environment. This issue can be solved by modifying the **DOSBox** configuration file.

解决方法 / Solution:

1. 打开 **DOSBox** 配置文件 `~/.dosbox/dosbox.conf`。  
   Open the **DOSBox** configuration file `~/.dosbox/dosbox.conf`.

2. 在 `[dos]` 部分加入 `longnames=true`。  
   Add `longnames=true` under the `[dos]` section.
   
3. 在 `[autoexec]` 部分加入 `set dos=lfn`。  
   Add `set dos=lfn` under the `[autoexec]` section.
   
4. 保存文件并重新启动 **DOSBox**。  
Save the file and restart **DOSBox**.

完成上述设置后，**DJGPP** 编译器应该能够在 **DOSBox** 中正常工作，且能够支持长文件名（LFN）。

After completing the above steps, the **DJGPP** compiler should work properly in **DOSBox**, and long file names (LFN) will be supported.
