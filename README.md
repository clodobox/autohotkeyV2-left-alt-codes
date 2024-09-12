# autohotkeyV2-left-alt-codes
## AutoHotKey V2.0 Left Alt Codes Script
This is a fork of swinogrodzki's script “autohotkey-left-alt-codes” modified to be functional with AutoHotKey V2

## Requirements
[AutoHotKey](https://www.autohotkey.com/) v2.0 or higher.

## Description
Why is it needed? Please see the following resource that explains it.

[Microsoft Forums Issue](https://answers.microsoft.com/en-us/windows/forum/windows_10-wintop_language/left-alt-codes-with-external-numpad-in-windows-10/94ddacdc-a181-4b2c-bb24-768e8138e77f)

[AutoHotKey Documentation](https://www.autohotkey.com/docs/v1/)

[AutoHotKey Downloads](https://www.autohotkey.com/download/)

When connecting an external USB or bluetooth numpad to your Windows PC it loses the left-alt-codes functionality. It is caused by the very nature of how the input devices work.
This solution is a workaround for that problem for the people that want to have both an external numpad and still functional left alt codes.

## Other
I had to make this script because the antivirus of the company where I work detects AHKv1 as a threat but not v2... So I did my best, a bit haphazardly, to adapt swinogrodzki's great work to make it usable in my workplace.

You can add missing codes by hand:

    alt_code_map[“VAL_255”] := “U+00A0”

VAL = [Numpad numbers](https://www.alt-codes.net/)
U+xxx = [Unicode *thing*](https://www.compart.com/en/unicode/block/U+2300)

If anyone has a mega list of ALT codes and unicode *things*, I'll adapt it!
I had a few problems with alt+tab but they're normally solved.
