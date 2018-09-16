# README

Main entry-point for documentation

```javascript
("GET")[on](repopath+ "/issues")
(	function()
	{					
		var issues = JSON.parse(this.responseText);
		var Reviews_;
		
		for(var k in issues)
			if("Reviews" == issues[k].title)
				Reviews_  = issues[k].url;
				
		if(!Reviews_)
			return;

("GET")[on](Reviews_ +"/comments")
(	function()
	{	
		var Reviews = JSON.parse(this.responseText);
		var Review;
		
		for(Reviews.max=5
		;  (Review = Reviews.pop())
		&& (Reviews.max--);
		)	{
				console.log
				(	Reviews.max
				,	Review.user.login
				,	Review.body
				);
			}
		;
	}
);	}
);
```

```javascript
cmmd = cmmd || '';
data = data || {};
type = type || 
(	function (coerce)
	{	
		if (typeof data === 'string')
			return (coerce=document.getElementById(data)) ? (data=coerce,'element') : 'string';

		if (data.type && (data.srcElement||data.target))
			return 'event';

		if (data.nodeType != void 0)
			return 'element';

		if (data[0] != void 0 && data[0].nodeType != void 0)
			return 'hostlist';

		if (util['typeof'].call(data) === '[object Array]')
			return 'array';

		if (data/1 === data)
			return 'number';

		return 'object';
	}
)();
```

adding support for `new` keyword, string `prototype`, and `console` wiki!


> this man's under oppression
> you just have to let go
> shrapnel through your retinal
> passin' through the ghetto
> mister have'm'rested
> imprisoned adolescence
> listen to the message
> written on the west bridge
> inner-city text-books
> bills for the electric
> deal just to collect rent
> here's another neglected
> kill up in the residence
> hills are for the rednecks
> pills are for the rich kids
> steal to have your medicince
> really how's it different
> imported by the dea
> hormones in vegetables
> pharmaceutical mafia
> that's not even the half of it
> monopolizin the oil too
> outsourcin the oil too
> armin forces of terror groups
> allocatin your data used
> it's captain america