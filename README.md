# Docker-Selenium-

docker run -d -e SCREEN_WIDTH=1366 -e SCREEN_HEIGHT=768 -e SCREEN_DEPTH=24 -e SCREEN_DPI=74 -p 4444:4444 -p 5900:5900 -v /dev/shm:/dev/shm selenium/standalone-chrome-debug:latest
