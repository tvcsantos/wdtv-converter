# wdtv-converter

> ⚠️ This project was developed in 2009 and is no longer maintained ⚠️

![](https://img.shields.io/badge/java-1.5-blue)

`WD TV Converter` is a simple Java desktop application based on Swing
Application Framework that converts a mkv video containing DTS tracks to AC3
tracks, and optionally adding more subtitles to the mkv (preventing from
crashing due to external subtitles), creating a mkv that can be played properly
at the WD TV Media Player.

## Usage

If you want to execute the pre-compiled version you can do it by issuing the
following commands:

```shell
make create-release
cd release
java -jar WDTVConverter.jar
```

For more information on the project refer to
[here](release_template/README.markdown).

## License

    WD TV Converter - Simple Java Swing application to convert DTS
	tracks to AC3, and with support for muxing additional subtitles.
    Copyright (C) 2009  Tiago Santos

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

For the full license text refer to [LICENSE.md](LICENSE.md)
