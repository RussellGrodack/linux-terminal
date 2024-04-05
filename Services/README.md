**Restart=** directive in systemd unit files.
  - **Restart=no**: The service will not be restarted automatically.
  - **Restart=on-success**: Restart only if the service process exits with a success code.
  - **Restart=on-failure**: Restart if the service process exits with a non-zero exit code, is terminated by a signal.
  - **Restart=on-abnormal**: Restart if the process is terminated by a signal, times out, or enters a failed state.
  - **Restart=on-abort**: Restart if the process is terminated by an uncaught signal.
  - **Restart=on-watchdog**: Restart the watchdog timer for the service expires.
  - **Restart=always**: Restart regardless of why it was stopped, except if explicitly stopped by an administrator.
