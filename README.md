This is basically [vbextreme's repo](https://github.com/vbextreme/Scheduler), just with a [tiny typo fix](https://github.com/Letsric/Arduino-Scheduler/commit/f187566fc40e3aa9ac4a79d92147dfeacf69b301) merged from [upstram](https://github.com/arduino-libraries/Scheduler). With this, it's functionally up to date with upstream, as they didn't change the actual `src`-Directory since the mentioned commit. (see [here](https://github.com/arduino-libraries/Scheduler/commits/master/src))

I just made this to use it until the [official PR](https://github.com/arduino-libraries/Scheduler/pull/1) gets merged.

Check out the example project on Wokwi: <https://wokwi.com/projects/434992178008162305>

# Scheduler Library for Arduino

The Scheduler library enables the Arduino to run multiple functions at the same time. This allows tasks to happen without interrupting each other.

For more information about this library visit <http://www.arduino.cc/en/Reference/Scheduler>

## How-to-use

1. [Download the library](https://github.com/Letsric/Arduino-Scheduler/archive/refs/heads/main.zip)
2. Open Arduino IDE and Select `Sketch -> Include Library -> Add .ZIP Library...`
3. Select the downloaded file
4. You will see `Successfully installed library from Arduino-Scheduler-main.zip archive`
5. Go to `File -> Examples -> Scheduler -> MultipleBlinks` to try it out

## License

Copyright (c) 2012 The Android Open Source Project. All right reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
