# module2.5
&lt;html&gt;
&lt;head&gt;
&lt;title&gt;Movies&lt;/title&gt;
&lt;/head&gt;
&lt;body bgcolor=&quot;cyan&quot;&gt;
&lt;h1 align=&quot;center&quot;&gt;&lt;i&gt;ShopTime&lt;/i&gt;&lt;/h1&gt;
&lt;h2&gt;Online bookings&lt;/h2&gt;
&lt;script bgcolor=&quot;cyan&quot;&gt;
n=window.prompt(&quot;Enter a number:&quot;);
while(n&lt;=2)
{
tcost=n*150
document.write(&quot;For n tickets,you need to pay :&quot;,tcost);
}
if(n&gt;=6)
{
document.write(&quot;Bookings are not Allowed&quot;);
}
else
{
if (n==3)
{
t1=150-(150*(3/100));
t2=150-(150*(5/100));
t3=150-(150*(7/100));
tcost=t1+t2+t3;
document.write(&quot;For 3 tickets,you need to pay

:&quot;,tcost,&quot;instead of &quot;,(150*3),&quot;with discounts&quot;);
}
else if (n==4)
{
t1=150-(150*(3/100));
t2=150-(150*(5/100));
t3=150-(150*(7/100));
t4=150-(150*(9/100));
tcost=t1+t2+t3+t4;
document.write(&quot;For 4 tickets,you need to pay

:&quot;,tcost,&quot;instead of &quot;,(150*4),&quot;with discounts&quot;);
}
else
{
t1=150-(150*(3/100));
t2=150-(150*(5/100));
t3=150-(150*(7/100));
t4=150-(150*(9/100));
t5=150-(150*(11/100));
tcost=t1+t2+t3+t4+t5;
document.write(&quot;For 5 tickets,you need to pay

:&quot;,tcost,&quot;instead of &quot;,(150*5),&quot;with discounts&quot;);
}
}
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
