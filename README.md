# Ansible-Role: atb-ansible-loradevices

Create and configure LoRaWAN devices on TTN stack via ansible

## Requirements

- Debian or Ubuntu

## Role Variables

```yaml
ttnstack_status: "OK"
ttnstack_wrapper_path: "/usr/local/bin"
ttnstack_wrapper_mode: "0755"
```

## Example Playbook

```yaml
- hosts: localhost
  roles:
    vars:
        ttnstack_wrapper_path: "/media/health"
        ttnstack_wrapper_mode: "0777"
        ttnstack_server: 192.168.100.23
```

## License

GPL-3.0

## Author

- Erik Grafendorfer
