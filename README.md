# Marko

The event handler works if, why?

```diff
static function handler() {
	console.log("click");
	alert("click");
}

+ <let/count=0/>

+ <button onClick() { handler(); }>
+ 	${count}
+ </button>

<button onClick=handler>
	Yoooo
</button>

```