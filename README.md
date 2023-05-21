# KESSER KKA-2002 infrared remote protocol
Describes the infrared remote protocol of a KESSER KKA-2002 air conditioning unit.

## Turn on / off

Protocol=NEC Address=0xFF00 Command=0xB946 Raw-Data=0xB946FF00 32 bits LSB first

## Temperature
### Up
Protocol=NEC Address=0xFF00 Command=0xF807 Raw-Data=0xF807FF00 32 bits LSB first

### Down
Protocol=NEC Address=0xFF00 Command=0xF30C Raw-Data=0xF30CFF00 32 bits LSB first

## Mode
Protocol=NEC Address=0xFF00 Command=0xF609 Raw-Data=0xF609FF00 32 bits LSB first

(Toggles through all modes available)

## Timer
Protocol=NEC Address=0xFF00 Command=0xDB42 Raw-Data=0xBD42FF00 32 bits LSB first

## Sleep
Protocol=NEC Address=0xFF00 Command=0xE31C Raw-Data=0xE31CFF00 32 bits LSB first

## Swing
Protocol=NEC Address=0xFF00 Command=0xB54A Raw-Data=0xB54AFF00 32 bits LSB first

## Speed
Received=NEC Address=0xFF00 Command=0xA15E Raw-Data=0xA15EFF00 32 bits LSB first

Thanks to https://github.com/Arduino-IRremote/Arduino-IRremote, helping to decode the ir protocoll.

THE INFORMATION IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE INFORMATION.
