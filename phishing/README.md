#!/bin/bash
killall php 2>/dev/null
cd web || exit 1
php -S 127.0.0.1:8080 > /dev/null 2>&1 &
sleep 3
