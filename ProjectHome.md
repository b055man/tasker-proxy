This is a simple app that forwards intents to Tasker allowing interaction from apps that are not built with necessary Tasker permissions (i.e. net.dinglisch.android.tasker.PERMISSION\_RUN\_TASKS)

Sample usage:
```
adb shell am broadcast -a pl.bossman.taskerproxy.ACTION_TASK --es task_name <task_name>
```

Additional details on Tasker's page: http://tasker.dinglisch.net/invoketasks.html