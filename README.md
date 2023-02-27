


## POS Screen Security Authentication Module (research) | Jan 2019

• Developed a POS screen security authentication model (research)

• Used the POS system module using WPF technology and logic touch pad algorithm that simulate same a digital analog light logic.


 Password is `1234`


![wpf](https://user-images.githubusercontent.com/75975280/221505122-45a9cc5f-14f4-4602-bbc9-120702bea5fa.png)

 >WPF provides a comprehensive set of application-development features that include Extensible Application Markup Language (XAML), controls, data binding, layout, 2D and 3D graphics, animation, styles, templates, documents, media, text, and typography. WPF is part of .NET, so you can build applications that incorporate other elements of the .NET API.
 

 

`Coming soon more animation features`


 

 
<table  cellspacing="0" cellpadding="0">
<tr>
<th align="center">
<img width="441" height="1">
<p> 
<small>
Code Example
</small>
</p>
</th>
<th align="center">
<img width="441" height="1">
<p> 
<small>
UI
</small>
</p>
</th>
</tr>
<tr>
<td>
<!-- REMOVE THE BACKSLASHES -->

``` C#
   private void StepByStepStopAnimation(string symbol, Button btn)
        {
            if (stop1)
            { //MessageBox.Show("0");
                stop1 = false; numberOne.SetNumber(14); pressedPassword += symbol;
            }
            else if (stop2)
            {// MessageBox.Show("1"); 
                stop2 = false; numberTwo.SetNumber(15); pressedPassword += symbol;
            }
            else if (stop3)
            { //MessageBox.Show("2"); 
                stop3 = false; numberThree.SetNumber(14); pressedPassword += symbol;
            }
            else if (stop4)
            { //MessageBox.Show("3"); 
                stop4 = false; numberFour.SetNumber(15); pressedPassword += symbol;
            }
            else
            {

                isLock = false;

                if (symbol == "►")
                {

                    PressButton(symbol, btn);
                }
            }
        }
```

  
</td>
<td>
<!-- REMOVE THE BACKSLASHES -->

<a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/75975280/221501847-4f072ab5-babd-4464-b027-776d581ff13e.png"><img src="https://user-images.githubusercontent.com/75975280/221501847-4f072ab5-babd-4464-b027-776d581ff13e.png" alt="numricpad" style="max-width: 100%;"></a>

</td>
</tr>
 
</table>
