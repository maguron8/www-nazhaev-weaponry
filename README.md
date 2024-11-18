# main objective
create a website that allows the user to browse the company (~~nazhaev~~ Vulcan) store.
make a nice website using css, js, and do backend stuff with php and sql.

# issues
## first issue:
how am i gonna include mysql to this??? i'm writing this in vs code with no actual knowledge on how to host a local website. i should probably figure this out first.
- (Index-1A) i have moved this from using an extension (Live Server) in vs code to using the WAMP project.
    i do not have a linux machine (as of yet, I'll probably end up converting my server to it, soon.) so I had to use WAMP to suffice.
> issue solved.
## css / html
i just now realized that i actually don't know anything about CSS or HTML. so i'm gonna have to learn all of this real quick. this shouldn't be a problem, just give me a day or so.

# things i learned
## !DOCTYPE
i thought this thing was not that important, apparently i was wrong; it is used for making sure that a browser formats the page in a standard fashion. from now on, i'll properly have my HTML files in such a fashion.

## git accounts
for a good day, I had trouble connecting my github to vs code. this prevented me from continuing this project, since i decided i wanted to learn more git while i was making this.

after that day, i was reasoning within my head trying to figure it out, and i realized it was probably because visual studio (not code) was connected to my git (and it used my microsoft account i believe). so i went to visual studio and changed the git settings there.

upon arriving at the git configuration, i discovered that it doesn't actually connect to a github account and whatnot. instead, they do "credentials" by giving a *username* and *email*. so i just set it to my appropriate credentials, and it was fixed. now it shows the right account when I push my changes (i believe that's the right term).

## css notes
- grids are pretty cool
- in order to override styles in a specific class/id, use the > *operator*. for example, in the *bannerGrid* id, all div items have their styles overwritten in the css page file by doing: #bannerGrid > div
- learned that '>' is a combinator. so is ' ', '+', '~', and ','
