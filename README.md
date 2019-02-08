# wm-temp
Watchman Monitoring plugin that uses SMCkit to monitor temperature sensors and fan speed.

[Binary](https://github.com/macitpros/wm-temp/tree/master/MonitoringClient/Utilities) built from SMCkit: https://github.com/beltex/SMCKit (requires macOS (Mac OS X) 10.9 or later)

Custom plugin for [Watchman Monitoring](https://www.watchmanmonitoring.com) to provide a warning (email or ticket) when a single sensor temperature is running above 100ºC (212ºF). Over 100ºC indicates a physical inspection of the computer should be done as it may be overheating (or getting very close). 

Fan speed of less then 200 RPM indicates a fan that _may_ be having issue, but not necessarly. Some Macs will idle fans at 0 RPM. Fan speed is for informational purposes only, it _may_ indicate a need to physically inspect the Mac or a fan cleaning may be required due to excessive dust in the fans.

New for v.0.7.1.0 Average temperature reported. An informational warning will be provided if average is above 60ºC. High average temperature, plus low fan speed is a good indicator of a potenial overheating issue that warrants further physical inspection.

Installer package available [here](https://github.com/macitpros/wm-temp/raw/master/wm-temp-fans/build/wm-temp-fans.pkg)

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
