# debugserver-ent
Entitlement file required for gadgets on iDevice
## How to use
`codesign -f -s - --entitlements entitlements.plist <file>`
for example:
`codesign -f -s - --entitlements entitlements.plist ./debugserver`
then send file to iDevice
`scp -P <port> <file> root@localhost:/path/to/dest
