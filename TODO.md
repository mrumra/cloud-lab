
1. Add 'Android Lab' for Android development.
2. Add 'IoT Lab' for IoT development.
3. Add fail2ban support: rsyslog + fail2ban
4. Reduce the lab size
   * Remove noVNC support if possible
   * Integreate noVNC outselvies and install necessary packages
5. Fix up open files limitation, up to 1000?: /proc/sys/fs/inotify/max_user_instances
6. Allow vncserver reuse the unix account for login: multi users on one container to save resources? not safety?
7. Load variables for container via environment variables, not mount the configs/ into it, require to modify tools/docker/start.
