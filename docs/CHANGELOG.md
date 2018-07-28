# CHANGELOG:
### v20180623:
- Single arg: `--output['cli', 'csv', 'json', 'idle' (without any DNS checks)]`

### v20180528:
- Step of progress % decreased
- Increased coverage of the homoglyph fuzzing function (experimental)
- Http, https, https-www, ww, www variants to the dictionary
- New chars in homoglyph fuzzer
- Changed validation of generated domains
- Changed format for whois queries (.split(' ')[0])
- Improved hyphenation fuzzer to generate multi-hyphenated domains
- IDN encoded in csv and json output
- Reorganized help screen
- Minor fixes

### v0.4b (20161123):
- New options: `--all, --nameservers, --port`
- Other fixes