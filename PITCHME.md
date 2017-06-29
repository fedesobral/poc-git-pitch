---
#Git Pitch
###Mastering slides using markup

---
#Maybe a title
And i thing some <span style="color:#e49436">**text**<span> could be really cool to explain the idea
 ```javascript

const explanation = (idea) => <Explain idea={idea} />

```

---
##Lets try some lists
<div style="color:grey; width: 40%; position: inline-block;">
- First point to explain
- Other stuff
- Dont forget this one
</div>|
<div style="color:grey; width: 40%; position: inline-block;">
1. What abount a series
2. This one comes second
</div>

---
Ok so what are some usefull ways to use the code presenting markdown syntax 
 ```javascript
it('events', () => {
	const props = {
		onClick: jest.fn(),
		children: 'Button'
	}

	const element = mount(<Button { ...props } />)

	expect(props.onClick).not.toBeCalled();
	element.find('button').first().simulate('click');
	expect(props.onClick).toHaveBeenCalledTimes(1);
});
```
@[9]
@[10-11]