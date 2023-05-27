
# taskerctl

A simple CLI to manage [tasker_service][1].


# installation
## install tasker service
`
cargo install tasker_service
`
## install taskerctl
`
cargo install taskerctl
`


# usage
### to enable tasker_service:

`
cd ~.cargo/bin/
`

`
taskerctl enable
`

`
systemctl --user start tasker
`
### list all possible commands:
`
./taskerctl help
`

OR

`
./taskerctl add --help
`
# roadmap
- [x]  working prototype
- [ ]  add option for execution as root
- [ ]  easier installation
- [ ]  GUI interface
- [ ]  better documentation

[1]:<https://crates.io/crates/tasker_service> "link to crate"
