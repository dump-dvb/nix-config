# Traffic Stop Box

Is a mobile radio antenna which is built to capture traffic stop telegrams which are sent
by trams or buses in the dresden germany area.


## Building with nix

This will build a vm which can be used for integration testing.

```
    $ nix build
```

for building the `traffic-stop-box-${n}` config.


## Todos

- [x] easily create and deploy new boxes
- [ ] systemd unit running gnu radio scripts
- [ ] decode server
- [ ] secrets managment
- [ ] monitoring
- [ ] remote deploying

### Rad10 Experimental radio antenna

- Joystick Left
- Turn On
- Joystick Down
- Joystick Puch In

