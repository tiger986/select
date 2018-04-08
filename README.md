## Select default style changes and click events
#### HTML code
```html
<div>
		<select>
            <option value="第一个">第一个</option>
            <option value="第二个">第二个</option>
            <option value="第三个">第三个</option>
            <option value="第四个">第四个</option>
        </select>
	</div>
```
#### CSS code
```css
div{
			width: 200px;
			height: 400px;
			margin: 200px auto 0;
		}
		
		select::-ms-expand { display: none; } 
		select{
			width: 300px;
			height: 42px;
			box-sizing: border-box;
		    font-size: 14px;
			color: #666666;
			line-height: 40px;
			padding: 0px 20px 0 10px;
			border: 1px solid #E5E5E5;
			outline: none;
			appearance:none;
			-moz-appearance:none;
			-webkit-appearance:none;
			-ms-appearance:none;
			background-color: #F5F5F5;
			background-image: url(img/down.png);
			background-repeat: no-repeat;
			background-size: 12px 13px;
			background-position: 282px center;
			-webkit-border-radius: 4px;
			-moz-border-radius: 4px;
			border-radius: 4px;
			margin-top: 10px;
		}
		select option{
			background-color: #FFFFFF;
			text-align: center;
		}
