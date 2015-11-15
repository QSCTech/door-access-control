# door-access-control

A CLI tool under Linux / FreeBSD written in C, in order to communicate with wiegand-card doors using a special protocol.

Author: Senorsen <sen@senorsen.com>

Started from 2014-07.

## Installation

First, copy `config.sample.h` to `config.h` and edit the configurations to fit your needs.

Then, try `make`. Note: clang is needed, but you can replace clang to gcc in Makefile by your self.

Just execute `./doorsend`, there would be a help message. Enjoy it!

## Copyright

Copyright 2014, 2015 Senorsen (Zhang Sen) <sen@senorsen.com> 

## License

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE. 
