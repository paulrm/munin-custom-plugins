# munin-custom-plugins

- create a cron job that output to /tmp/useractivity.json
- copy the useractivity file to /usr/share/munin/plugins/
- `chmod 755 /usr/share/munin/plugins/useractivity`
- `ln -s /usr/share/munin/plugins/useractivity /etc/munin/plugins/useractivity`
- restart munin-node

