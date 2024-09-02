# AAP2 automated scheduling

## Create / delete schedules

See `schedule.yml` and `schedule_delete.yml`.

Those can be used within Ansible Automation Platform.

## Disable / Enable schedule on demand

For example when patching a system, you might want to disable some schedules jobs against the node.

Use `schedule_enable.yml` and `schedule_disable.yml`.

## Update default values for a survey

Edit default values in `survey.json`

Run:

```sh
ansible-playbook survey.yml
```



