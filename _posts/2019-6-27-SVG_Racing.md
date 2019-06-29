---
layout: page
title: 简单动画-接受男子漢的愛吧！
categories:
     - SVG制作
---

### 接受男子漢的愛吧
![jpg](/he1mo/assets/images/Love.png)
<html>
	<head>
	<style type="text/css">
@keyframes spin{
	0% {
		transform:rotate(0deg);
	}
	50 {
		transform:rotate(180deg);
	}
	100%{
		transform:rotate(360deg);
			}
}
@keyframes scale {  
            0%{
                transform: scale(1); 
            }
            25%{
                transform: scale(1.2);
            }
            50%{
                transform: scale(1.6);
            }
            75%{
                transform: scale(0);
            }
        }
div.love_p{
	animation: spin 2s 1s;
	infinite;
	transform-origin: 50% 50%;
	}
div.love_r{animation: scale 2s 1s;
	transform-origin: 40% 40%;
	}
div.love{
	display:flex;
}
</style>
	
</head>
	
<body> <div class="love"><article>
	<div class="love_p">
	<svg xmlns="http://www.w3.org/2000/svg" width="500" height="300">
 <!-- Created with Method Draw - http://github.com/duopixel/Method-Draw/ -->
 <g>
  <title>background</title>
  <rect fill="#fefaec" id="canvas_background" height="10" width="10" y="-1" x="-1"/>
  <g display="none" overflow="visible" y="0" x="0" height="100%" width="100%" id="canvasGrid">
   <rect fill="url(#gridpattern)" stroke-width="0" y="0" x="0" height="100%" width="100%"/>
  </g>
 </g>
 <g>
  <title>love</title>
  <path transform="rotate(-11.113571166992188 312.91229248046886,157.94279479980474) " id="svg_1" d="M250.624454016887,152.43046118526337 C280.9281549220593,76.82721510343657 399.6590486324842,152.43046118526337 250.624454016887,249.63463471904166 C101.58985940129023,152.43046118526337 220.32075311171457,76.82721510343657 250.624454016887,152.43046118526337 z" stroke-width="1.5" fill="rgb(237, 182, 220)"/>
  <line stroke-linecap="null" stroke-linejoin="null" id="svg_2" y2="234.4375" x2="136.5" y1="280.4375" x1="74.5" stroke-width="1.5" fill="none"/>
  <path d="m97.5,266.4375c-1,-1 -0.813995,-2.692535 1,-4c3.441811,-2.480713 5,-4 8,-7c1,-1 3,-3 4,-5c1,-2 2,-2 3,-1c2,2 4.54863,4.769928 6,9c1.654816,4.823029 2.565033,10.830994 5,20c1.308754,4.928192 2,10 2,14c0,3 0,7 0,13c0,5 0,11 0,15c0,3 1.770248,6.026764 2,7c0.513748,2.176239 2.485062,3.70575 5,5c5.4086,2.783356 13.160507,2.37851 19,1c4.352509,-1.027496 6,-5 7,-6l0,-1" id="svg_3" stroke-width="1.5" fill="none"/>
  <path id="svg_8" d="m147.5,253.4375" opacity="0.5" stroke-width="1.5" stroke="#AF84A3" fill="#AF84A3"/>
 </g>
</svg>
	</div> </article>
	<article>
		<div class="love_r">
		<svg xmlns="http://www.w3.org/2000/svg" width="500" height="300">
	 <!-- Created with Method Draw - http://github.com/duopixel/Method-Draw/ -->
	 <g>
	  <title>background</title>
	  <rect fill="#fefaec" id="canvas_background" height="10" width="10" y="-1" x="-1"/>
	  <g display="none" overflow="visible" y="0" x="0" height="100%" width="100%" id="canvasGrid">
	   <rect fill="url(#gridpattern)" stroke-width="0" y="0" x="0" height="100%" width="100%"/>
	  </g>
	 </g>
	 <g>
	  <title>Layer</title>
	  <path transform="rotate(-11.113571166992188 312.91229248046886,157.94279479980474) " id="svg_1" d="M250.624454016887,152.43046118526337 C280.9281549220593,76.82721510343657 399.6590486324842,152.43046118526337 250.624454016887,249.63463471904166 C101.58985940129023,152.43046118526337 220.32075311171457,76.82721510343657 250.624454016887,152.43046118526337 z" stroke-width="1.5" fill="red"/>
	  <line stroke-linecap="null" stroke-linejoin="null" id="svg_2" y2="234.4375" x2="136.5" y1="280.4375" x1="74.5" stroke-width="1.5" fill="none"/>
	  <path d="m97.5,266.4375c-1,-1 -0.813995,-2.692535 1,-4c3.441811,-2.480713 5,-4 8,-7c1,-1 3,-3 4,-5c1,-2 2,-2 3,-1c2,2 4.54863,4.769928 6,9c1.654816,4.823029 2.565033,10.830994 5,20c1.308754,4.928192 2,10 2,14c0,3 0,7 0,13c0,5 0,11 0,15c0,3 1.770248,6.026764 2,7c0.513748,2.176239 2.485062,3.70575 5,5c5.4086,2.783356 13.160507,2.37851 19,1c4.352509,-1.027496 6,-5 7,-6l0,-1" id="svg_3" stroke-width="1.5" fill="none"/>
	  <path id="svg_8" d="m147.5,253.4375" opacity="0.5" stroke-width="1.5" stroke="#AF84A3" fill="#AF84A3"/>
	 </g>
	</svg>
		</div> </article></div>
</body>
</html>

***

  ### 简单的SVG动画制作
SVG[制作工具][6]：
![jpg](/he1mo/assets/images/svgeditor.png)

> 画出满意的SVG图形，然后在Chrome右击检查找到该SVG图形的代码复制下来就可以了
然后放在html代码里（注意在.md文件中，HTML格式显得尤为重要，否则就会显示错误）

    <g>
      <title>love</title>
      <path transform="rotate(-11.113571166992188 312.91229248046886,157.94279479980474) " id="svg_1" d="M250.624454016887,152.43046118526337 C280.9281549220593,76.82721510343657 399.6590486324842,152.43046118526337 250.624454016887,249.63463471904166 C101.58985940129023,152.43046118526337 220.32075311171457,76.82721510343657 250.624454016887,152.43046118526337 z" stroke-width="1.5" fill="rgb(237, 182, 220)"/>
      <line stroke-linecap="null" stroke-linejoin="null" id="svg_2" y2="234.4375" x2="136.5" y1="280.4375" x1="74.5" stroke-width="1.5" fill="none"/>
      <path d="m97.5,266.4375c-1,-1 -0.813995,-2.692535 1,-4c3.441811,-2.480713 5,-4 8,-7c1,-1 3,-3 4,-5c1,-2 2,-2 3,-1c2,2 4.54863,4.769928 6,9c1.654816,4.823029 2.565033,10.830994 5,20c1.308754,4.928192 2,10 2,14c0,3 0,7 0,13c0,5 0,11 0,15c0,3 1.770248,6.026764 2,7c0.513748,2.176239 2.485062,3.70575 5,5c5.4086,2.783356 13.160507,2.37851 19,1c4.352509,-1.027496 6,-5 7,-6l0,-1" id="svg_3" stroke-width="1.5" fill="none"/>
      <path id="svg_8" d="m147.5,253.4375" opacity="0.5" stroke-width="1.5" stroke="#AF84A3" fill="#AF84A3"/>
     </g>

  [6]: https://c.runoob.com/more/svgeditor/