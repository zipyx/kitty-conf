## Kitty config

This is the kitty terminal config setup for my environment.

## Structure

The below is generally my structure for anything outside of `kitty`. In this case, it's terminal applications.

```bash
# app_<component>.conf
.
├── app_pane.conf
├── app_tab.conf
```

The below structure, represents the `modifications` I've made to customize accordingly. Notice, I've renamed `window` component to `pane` because it makes associations easier to remember for me personally.

```bash
├── mod_layout.conf
├── mod_pane.conf
├── mod_tab.conf
├── mod_ui.conf
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
├── app_pane.conf
├── app_tab.conf
├── debug.log
├── kitty.conf
├── mod_layout.conf
├── mod_pane.conf
├── mod_tab.conf
├── mod_ui.conf
├── README.md
└── sample.conf
```

More instructions to come in the near future.
