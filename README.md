### Feedback

### fib.py

* Your fib.py didn't seem to be working (it still had a call to fibbb() instead of fib() in it). Were you able to revert the file back to its latest working version as seen on the git log? 
* ./fib.py converge output.txt should write the output to a text file instead of the terminal. Look again in your phi_converge() function. It doesn't look like you ever open the file or write to it. Check out open(filename, 'w+') and f.write(). What does the 'w+' argument mean in the open() function?