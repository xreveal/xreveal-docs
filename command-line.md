# Command Line Reference

## Usage
xreveal Command [Switches] [ImageFile]

## Switches
<table>
<tr><th>Command</th><th>Usage</th><th>Action</th></tr>
<tr><td>enable</td><td>xreveal enable</td><td>Enable Xreveal</td></tr>
<tr><td>disable</td><td>xreveal disable</td><td>Disable Xreveal</td></tr>
<tr><td>rip2iso</td><td>xreveal rip2iso [driveLetter] [isoFile]</td><td>Rip to a ISO file</td></tr>
<tr><td>rip2folder</td><td>xreveal rip2folder [driveLetter] [folder]</td><td>Rip to a folder</td></tr>
<tr><td>verify</td><td>xreveal verify [driveLetter]</td><td>Verify Content Hash (for BD or UHD)</td></tr>
<tr><td>register</td><td>xreveal register</td><td>Register Xreveal or Update license</td></tr>
</table>

## Examples:
- Rip drive G: to d:\mymovie\foo.iso
xreveal rip2iso g: d:\mymovie\foo.iso
- Rip drive G: to d:\mymovie\foo\
xreveal rip2folder g: "d:\mymovie\foo\"

## Notes
- All parameters are case-insensitive
- Switches can start with a slash / or dash -
- DriveLetter with a letter from D to Z

## Installer Command Line
<table>
<tr><th>Command</th><th>Usage</th></th><th>Action</th></tr>
<tr><td>-s</td><td>xreveal_x.x.x.exe -s</td><td>Silent install mode</td></tr>
</table>
