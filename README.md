# concept
the same app implemented in multiple frameworks, to figure out what I want to use

## meta
- each framework will be on a separate branch
- upon creation each framework will be ranked & noted with each up & downside

why not include payments?
- stripe is a nightmare everywhere

why not include emails?
- maybe later

## features I want in the apps
1. auth (ideally avoiding external paid APIs, ideally SQLite so I don't have to fuck with setting up postgres)
2. user customization with pfps & names
3. Markdown blog cms
4. blog search 
5. Live chat "lobbies" between users (not stored, only in non-persistent redis like) 

## Frameworks to try (in order) 
- [ ] Nuxt
- [ ] SvelteKit
- [ ] Next
- [ ] Django? 
- [ ] Pheonix? (my gf will do this one)
- [ ] Rails? (I hated this but I need to try the more stock reactivity model instead of Alpine) (Rails is a key reason I insist on rolling my "own" auth, because I know how easy it can be with stuff like [devise](https://github.com/heartcombo/devise)) 
