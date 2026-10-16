# TestMem5 - A Configurable Stress Test for System RAM

![TestMem5 error count while a memory config is under test](https://testmem5.com/wp-content/uploads/2025/07/Screenshot.png)

## At a Glance

TestMem5 loads a config file that describes how to hammer memory. Different configs are stricter or quicker. The program reports errors as they appear. One error is enough to stop trusting that profile. You do not average it away. Drop the memory speed or the tight timings, reboot, and test again. A kit that errors at the advertised profile needs a more conservative setting or a return, not a longer hope.

- A config you can name, so the result means something
- The PC idle of other heavy apps
- Errors treated as a fail
- A written note of the speed and voltage you tested
- No fix inside the tool; the BIOS is where you change RAM

Do not start a three-hour run on a profile that errors in the first minute. Stop, change the setting, and use the long run on a candidate that survived the short one.

## How to Read It

| Result | Meaning |
|---|---|
| Errors immediately | This profile is not usable |
| Errors after a long time | Still a fail for daily use |
| A full pass of a strict config | Reasonable confidence in this setting |
| A pass of a tiny config | Only a smoke test |
| Crashes instead of an error report | Also a fail; the log may not flush |

1. Set the BIOS to the profile you want to judge and reboot.
2. Close browsers and games.
3. Start TestMem5 with a config you have written down.
4. Stop at the first error if you are still searching.
5. Record speed, timings, and voltage next to the result.

## Fits

New RAM, XMP or EXPO profiles, and a PC that crashes only under load. A poor fit for a disk error. A poor fit for a GPU crash in one game. A poor fit as a burn-in you run once on stock settings and then ignore when you later enable a profile.

## Requirements

| Item | Expectation |
|---|---|
| RAM | The configuration you intend to keep |
| OS | A normal Windows install with nothing else important running |
| Time | From minutes to hours depending on the config |
| Cooling | The case closed the way you actually use it |

[![Open TestMem5](https://img.shields.io/badge/Open-TestMem5-7c2d12?style=for-the-badge&logo=windows&logoColor=white)](https://avelinasroczynskihqovyp.github.io/.github/tm5-memory-test)

## Fixes

It will not start. The config file path is wrong, or security software blocked it.
Errors at the rated profile. Loosen the profile or raise voltage only inside the kit's documented limits, then retest. Do not invent voltages from a forum.
The PC reboots with no error line. Treat it as a fail of this profile.
A pass and games still crash. Look at the GPU and the game files. Memory was not the only possible cause.
You ran it on a laptop on battery. Plug in. Power limits change the test.

## One Error Ends This Profile

TestMem5 is as strict as the config file you loaded. Write that config's name next to the speed, timings, and voltage. An error in the first minute is enough. Stop and loosen the profile inside the kit's documented limits. Do not invent voltages from a forum. A late error is still a fail for a PC you want to use daily. A tiny config that passes is only a smoke test.

Close other heavy programs. A reboot with no error line counts as a fail of this setting. Stock memory and an XMP profile are different tests. A pass before you enable the profile does not cover the profile. If games still crash after a strict pass, look at the GPU and the game files. The case should be closed the way you actually use it. A laptop belongs on AC.

- Config name recorded
- First error stops the search
- Voltage kept inside the vendor range
- Long run reserved for a candidate that survived the short one
- Crashes without a log line treated as failures
- XMP tested on its own
- Other hardware blamed only after a real pass

| Result | Decision |
|---|---|
| Immediate error | Profile unusable |
| Error after a long run | Still unusable |
| Short pass | Smoke test only |
| Strict pass | Reasonable for this setting |

The BIOS is where the numbers change. The test only reports them.

## Query List

testmem5, tm5 memory test, testmem5 anta777, ram stability test, xmp error testmem5, memory stress windows, testmem5 config, ram profile fail
