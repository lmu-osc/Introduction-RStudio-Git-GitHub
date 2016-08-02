# Making a change

The next version of our code will do a little more. From domain knowledge of the data, we know that a good model for it is the equation **p1\*cos(p2\*xdata) + p2\*sin(p1*xdata)**.

We just need to find the values for the parameters **p1** and **p2**. Add the following code to the end of your R script.

```
# some guesses for the parameters.
p1 = 1
p2 = 0.2

# do the fit
fit = nls(ydata ~ p1*cos(p2*xdata) + p2*sin(p1*xdata), data = mydata, start = list(p1=p1,p2=p2))

#Plot the fitted line
new = data.frame(xdata = seq(min(mydata$xdata),max(mydata$xdata),len=200))
lines(new$xdata,predict(fit,newdata=new))

```

For this version, we are also going to change the command that plots our data. Change the lines

```
plot(mydata$xdata,mydata$ydata)
```

to

```
plot(mydata$xdata,mydata$ydata,col='red')
```

We do this so we can illustrate how git handles modifications of existing lines as well as simply adding extra lines of code.

Make sure the code runs before proceeding further.
