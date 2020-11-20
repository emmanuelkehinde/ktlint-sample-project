#!/bin/bash

echo "Running test..."

./gradlew app:test --daemon

status=$?

# return 1 exit code if running checks fails
[ $status -ne 0 ] && exit 1
exit 0
