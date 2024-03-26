# Stretch cursor

![Inspiration image (quote below)](https://cdn.discordapp.com/attachments/775405278048288818/1222299890822942740/20240326_224315.jpg?ex=6615b67b&is=6603417b&hm=761e173c2ce23fae4714e0cae039a2da2633370e1c349e53b7cabb19510af469&)

> _"bad idea: A mouse cursor that's not just a simple floating pointer, it's a cat/dog paw... but it stretches all the way to an edge of the screen like it's a really long leg"_

Holy, shit; that's a good idea! This is what that idea is, made.

## Installation & usage

Download executable from the [versions section](notavailable), run, configure, enjoy.

To end your madness, use Task manager, command prompt, or (if enabled) the key combo <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>F</kbd> to kill the `stretch-cursor` process.

> [!TIP]
> To continue your madness for all eternity, travel to your autostart  directory...
>
> **On Windows:** `C:\Users\...\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup` / `%appdata%\Microsoft\Windows\Start Menu\Programs\Startup` or just `shell:startup` from the Run (<kbd>WIN</kbd> + <kbd>R</kbd>) menu.
>
> **On MacOS:** ???, (needs contribution, or google; I'm too lazy and don't want imprecise information).
>
> **On Linux:** You should know this, not me (needs contribution, or google; I'm too lazy and don't want imprecise information).
>
> ...and place the `stretch-cursor` executable in that folder; that way you will have stretchy cursor, persistent after shutdown.

If you want to avoid the configuration screen every time the program starts; press <kbd>S</kbd> on the configuration screen after setting your settings and the program will automatically create a `stretch-settings.config` file alongside the base executable. To change setting again, modify the file or remove it to get the configuration screen again.

## Performance

This project is made with Tauri, (ew... embedded web browser); don't expect godlike performance.

Sourcing [lukaskalbertodt](http://lukaskalbertodt.github.io/2023/02/03/tauri-iced-egui-performance-comparison.html)'s research, expect load-times of ~400ms or so.

## Contributions

Whatever may you want to contribute? Go ahead I suppose.

**Report issues or suggest features** on the [issues page](notavailable), only after checking for duplicates.

**Make pull requests** if you want to contribute to creation or patching of bugs. Don't re-make my code from scratch though please; start a fork for that.

**Fork** for whatever the hell you may want to do, heck this is open-source and free code. God bless Ameri-**[REDACTED for... reasons]**

## License

I _could_ provide a proper LICENSE file, like a good github:ian should or I could be lazy and just link to <https://unlicense.org/>, if it _really_ bothers you so much that there isn't a non-legal document to tell you to do whatever you want, including: modifying, copying, selling, publishing and redistributing the compiled binary or source code of this project free of charge, then just **PR** a license file and update this section of the README.

- [x] license.

_if it weren't obvious enough; this project is memes only, if you expected a serious repo then make one yourself; and link it here so others can be spared of this godawful README file._
