# shiro_custom
modify some configure of shiro in jar

"shiro-quartz-1.2.3.jar" doesn't support the package "quartz-x.x.x.jar" that version above 1.6 bacause of the SimpleTrigger class.(SimpleTrigger cann't be new after 1.6)<br>
here is the new jar package with the override code.<br>
it should be work if you use the "shiro-quartz-1.2.3.jar" and "quartz-2.2.3.jar" together!<br>

for more detail,[click](http://blog.csdn.net/myproudcodelife/article/details/50116479)