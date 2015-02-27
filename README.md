# FlashHacker

FlashHacker is an ActionScript Bytecode instrumentation framework. The RABCDasm tool is used for disassembling and assembling of ActionScript Bytecode. The tool uses Bytecode disassembly to inject various instrumentation instructions.

This tool is very useful when you work with malicious Flash files.

The whole concept was introduced in my previous presentation at ShmooCon 2012
   http://www.shmoocon.org/2012/presentations/Jeong_Wook_Oh_AVM%20Inception%20-%20ShmooCon2012.pdf

## Prerequisite
* PySide: https://pypi.python.org/pypi/PySide (pip install -U PySide on Windows)
* Graphviz 2.x: included in the repo\
* RABCDasm binaries: https://github.com/CyberShadow/RABCDAsm/releases

After installing prerequisites, run python FlashHacker.py and it will ask path for RABCDasm package. 

## LICENSE
Copyright (c) 2010, Jeong Wook Oh
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
   * Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
   * Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
   * Neither the name of the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

