
#[Dec 17 2014 00:00:06]    ......    00:00:06




import re
import datetime

with open("log.txt") as text:
        for line in text:
                date = set(re.findall("\[([^]]+)\]", line))
                for i in date:
                         do = datetime.datetime.strptime(i, "%b %d %H:%M:%S")
                         line = line.replace("[%s]"%i, "%s"%(do.strftime("%H:%M:%S")) )
                         print line

