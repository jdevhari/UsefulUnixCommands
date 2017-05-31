# UsefulUnixCommands

Find the corrupted jar

find /Users/..../.m2/repository/ -name "*jar" | xargs -L 1 zip -T | grep error |  grep invalid
