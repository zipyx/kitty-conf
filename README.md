## Kitty config

This is the kitty terminal config setup for my environment.

## Structure

The below is generally my structure for anything outside of `kitty`. In this case, it's terminal applications.

```bash
# app_<component>.conf
├── app
│   ├── app.conf
│   ├── app_pane.conf
│   └── app_tab.conf
```

The below structure, represents the `modifications` I've made to customize accordingly. Notice, I've renamed `window` component to `pane` because it makes associations easier to remember for me personally.

```bash
├── mod
│   ├── mod.conf
│   ├── mod_layout.conf
│   ├── mod_pane.conf
│   ├── mod_tab.conf
│   └── mod_ui.conf
```

Next are sessions, this can be customizable according to you.

```bash
└── session
    ├── session.conf
    └── w_lumio.conf
```

Lastly, the main config file which kitty recognizes as the main config file.

```bash
# main config file
├── kitty.conf
```

The entire structure looks like the below (additional files are sample + debug).

```bash
> kitty-config
.
├── app
│   ├── app.conf
│   ├── app_pane.conf
│   └── app_tab.conf
├── debug.log
├── kitty.conf
├── mod
│   ├── mod.conf
│   ├── mod_layout.conf
│   ├── mod_pane.conf
│   ├── mod_tab.conf
│   └── mod_ui.conf
├── README.md
├── sample
│   └── sample.conf
└── session
    ├── session.conf
    └── w_lumio.conf

```

More instructions to come in the near future.

## Environment

The setup I have at the moment is due to the fact that `alacritty` did not have certain options + ligature functionality along with performance on certain parts that I decided `kitty` was the best way to go (at least for now). Feel free to have a look at my `alacritty` setup, for now at least - I'll be using `kitty` until I see the need to make changes.
