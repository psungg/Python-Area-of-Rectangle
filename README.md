# Python-Area-of-Rectangle

## Code

```
import sys
from tkinter import Tk, simpledialog, messagebox

def recArea(width, height):
    area = width * height
    return area

root = Tk()
root.withdraw()

query_width = simpledialog.askfloat('Area Calculator', 'Enter width: ')
query_height = simpledialog.askfloat('Area Calculator', 'Enter height')

result = recArea(query_width, query_height)
messagebox.showinfo('Area Calculator', 'Area of Rectangle is: ' + str(result))

root.destroy()
sys.exit()
```

## Result

![Fig01](https://github.com/psungg/Python-Area-of-Rectangle/blob/main/Images/Fig01.png)

![Fig02](https://github.com/psungg/Python-Area-of-Rectangle/blob/main/Images/Fig02.png)

![Fig03](https://github.com/psungg/Python-Area-of-Rectangle/blob/main/Images/Fig03.png)
