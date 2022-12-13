# Andrii Mordovets          
<div id="top"></div>

## Contacts:
* +380972124845
* andreymordovets@gmail.com
* Menix#1427

---

## Skills:
* Adobe Photoshop
* Word
* Excell
* JS (basics)
* Python (basics)

## Code Excemple
### **Task**: Convert number of seconds to days:hours:minutes:seconds format
``` 
def get_seconds_in_format(count_seconds):
  days = 0
  hours = 0
  minutes = 0
  seconds = 0
  if count_seconds >= 0:
    seconds = count_seconds
    if count_seconds >= 60:
      minutes = (count_seconds - seconds % 60) / 60
      seconds -= minutes * 60
      if count_seconds >= 3600:
        hours = (count_seconds - minutes * 60 % 3600 - seconds) / 3600
        minutes = (count_seconds - hours * 3600 - seconds) / 60
        if count_seconds >= 86400:
          days = (count_seconds - hours * 3600 % 86400 - minutes - seconds) / 86400
          hours =  (count_seconds - days * 86400 - minutes - seconds) / 3600
  else: 
    print(False)
        
  format = f'{round(days)}:{round(hours)}:{round(minutes)}:{round(seconds)}'
  print(format)
```

## Courses:
* RS School «JavaScript/Front-end. Stage 0» (in progress)

## Languages:
* English (B1)
* Ukrainian (Native)
* Russian (Native)
* Polish (A2)