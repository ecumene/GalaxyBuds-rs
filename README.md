# GalaxyBudsLive-rs
A reverse engineered rust wrapper for the GalaxyBudsLive bluetooth protocol. Can be used to communicate with your earbuds from rust.

#### To use:
Add this to your Cargo.toml
```
galaxy_buds_live_rs = "0.1.2"
```
Or if you have `cargo edit`:
```
cargo add galaxy_buds_live_rs
```

# Features

### Receiving
- [x] Statusupdate
- [x] Extended statusupdate
- [x] Touch updated
- [x] Voice wakeup listening update
- [x] Touchpad tap action
- [ ] Version info

### Sending
- [x] Un/Lock touchpad
- [x] Set noisereduction
- [x] Set Equalizer
- [x] Adjust sound sync
- [x] Mute earbud
- [x] Find my earbuds
- [x] Prepare voice notification (notifications TTS)
- [ ] Set touchpad option
- [ ] Update time

# Examples

### Receive
Set the `address` value in `examples/receive.rs` to your Buds' mac address and run following:
```bash
cargo --example receive
```

### Send
Set the `address` value in `examples/send.rs` to your Buds' mac address and run following:
```bash
cargo --example send
```
