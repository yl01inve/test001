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
請注意，由於 DJGPP 編譯器可能存在某些未知的問題（可能是 bug），當你在 **DOSBox** 環境下使用 **DJGPP** 編譯程式碼時，請務必確保 **檔案名使用小寫字母**。  這是因為在某些情況下，DJGPP 可能會無法正確識別包含大寫字母的檔案名稱，導致編譯失敗或錯誤。  
Please note that due to some unknown issues (possibly a bug) with the DJGPP compiler, when using **DJGPP** in a **DOSBox** environment, make sure the **file names are in lowercase**.This is because, in some cases, DJGPP may fail to correctly recognize file names with uppercase letters, causing compilation failures or errors.
