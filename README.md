# robertYAG
A set of YAGPDB Custom Commands to facilitate the use of Robert's Rules for assemblies done on Discord. 

## Installation
1. Add YAGPDB to your Discord server.
2. Create a new custom command group titled according to your needs.
3. Add each custom command, triggered by RegEx with the pattern indicated in the comment before each command.
4. Set the whitelist/blacklist users and channels to ensure no abuse.

## Inclusions
* motion (non-persistent)
* seconds
* objections
* manifestations
* bagsakan
* point of information
* point of inquiry
* point of privilege
* point of order
* direct responses

## TODO
- Use database to keep track of motions.
- Add default Points of Orders.
- Add default Points of Privilege.
- Add -help flag for commands.
- Make more flexible with name-stripping (currently strips username to first whole word).
- Convert into modular format (one command per file)
