Run:
```
ansible-playbook playbook.yml
```

It works !
Then edit, `collections/ansible_collections/namespace/foobar/playbooks/entrypoint.yml`
to enable the `import_playbook`; It breaks because it cannot found the `do_stuff` roles (located in foobar)
More ! It can now found `common_ping` (located in `common` collection)
