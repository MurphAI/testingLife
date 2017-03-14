### test log
**2017/03/14**
There was an issue yesterday that test kept failing with error Element not Found. At last, I used browser.getHTML() and found that the element's parent element was displaying no item at first then trying to load the real list while the element under empty list status was loaded and visible on the page already.
