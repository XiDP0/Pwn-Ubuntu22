# Pwn-Ubuntu22
这是一个Ubuntu 22.04版本的VMware虚拟机，里面安装了常用的入门阶段PWN所需要的绝大部分工具。

百度网盘链接：通过网盘分享的文件：VM22XiDP_ovf
链接: https://pan.baidu.com/s/1NYJ7NywYab6LUC_kZgRxPQ?pwd=xidp 提取码: xidp 
--来自百度网盘超级会员v1的分享

### 目前包含的工具：

1. **pwntools**：用于编写和调试利用代码的Python库。
2. **Python 3.10.12**：Python编程语言的版本（使用 `python3` 指令运行）。
3. **gcc 11.4.0**：GNU编译器集合的版本。
4. **glibc-all-in-one**：包含GNU C库的所有组件。
5. **Pwngdb**：GDB插件，增强调试体验。
6. **pwndbg**：GDB插件，提供额外的调试功能。
7. **Ropper**：用于分析和利用二进制文件的工具。
8. **patchelf**：用于修改ELF文件的工具。
9. **LibcSearcher**：用于查找和使用C库函数的工具。
10. **checksec**：检查二进制文件的安全特性。
11. **cyclic**：生成和处理循环数据的工具。
12. **patlibc**：Libc的patchelf替代工具。
13. **peda**：GDB插件，提供额外调试功能（可与pwndbg切换）。
14. **seccomp-tools**：用于安全计算机操作的工具集。
15. **ROPgadget**：用于ROP（Return-Oriented Programming）分析的工具。
16. **one_gadget**：查找并利用漏洞的工具。

已换源为`清华源`

此外修改了部分快捷键：

复制:`ctrl + c`

粘贴:`ctrl + v`

全选:`ctrl + a`


此虚拟机安装各工具后，仅简单测试过一次，确保没有报错。如果后续出现任何Bug请于github下留言，收到会定期进行修复
