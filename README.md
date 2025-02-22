# Icod.Deflate
Console program to compress files using the Deflate algorithm.

## Usage
`Deflate.exe --help`
Displays this text.

`Deflate.exe --copyright`
Displays copyright and licensing information.

`Deflate.exe inputFilePathName [outputFilePathNam]`
Compresses the specified file.
inputFilePathName and outputFilePathName may be relative or absolute paths.
If outputFilePathName is omitted then it will be generated in the current directory and named the same as inputFilePathName but with '.lz77' appended to the end.
If the outputFilePathName is an existing directory, then it will be generated in that directory and named the same as inputFilePathName but with '.lz77' appended to the end.

## Copyright and Licensing
Deflate.exe compresses files using the Gzip compression algorithm.
Copyright( C ) 2025 Timothy J. Bruce

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published 
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
