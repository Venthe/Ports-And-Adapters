# Ports and adapters

## Sample package / namespace subdivision

```plain
eu.venthe:
  [project_name]:
    sharedkernel:
      model: {}
    adapters:
      user_interface: {}
      # Infra utils
      infrastructure: {}
    core:
      [component_name]:
        user_interface:
          adapters: {}
        infrastructure:
          adapters: {}
        application:
          services: {}
          ports: {}
        domain:
          model: {}
          services: {}
          ports: {}
```
