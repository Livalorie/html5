# html5
Banner Notes

## Code Snippets reused: Animate CC files:
_____
### Loops:
**Second to last Frame**

if(!this.alreadyExecuted){<br/>
this.alreadyExecuted=true;<br/>
this.loopNum=1;<br/>
} else {<br/>
this.loopNum++;<br/>
if(this.loopNum==2){<br/>
this.stop();<br/>
}<br/>
}<br/>
<br/>
 **Last Frame:**<br/>
 this.gotoAndPlay(2) - or whatever dramenumber you want loop to begin on.
 
____ 

### Click-Tag code:
**Frame 1**

this.background.addEventListener("click", fl_MouseClickHandler.bind(this));

function fl_MouseClickHandler()
{

}

this.background.addEventListener("click", fl_ClickToGoToWebPage);

function fl_ClickToGoToWebPage() {
	javascript:window.open(window.clickTag);
}
_____


