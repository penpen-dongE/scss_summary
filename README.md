SCSS Layout에 대하여 정리 및 클론 코딩: Flexbox & Grid (updating...)

참고 URL)
https://flexboxfroggy.com/#ko
https://cssgridgarden.com/#ko

220221
- main axis / cross axis
- justify-content : move items on the main axis
- align-items : move items on the cross axis

220222
- child option : align-self & order 
- wrap(same size), nowrap, reverse, align-content(line)
- flex-grow(default:0), flex-shrink(default:1)
- flex-basis : applies to the child / give the initial size / works main axis / could be width or height depending on the flex-direction

220223
- Grid 
- grid-template-columns / grid-template-rows
- column-gap / row-gap  || gap 
- grid-template-area

220224
- fr = fraction(available space)
- grid-template 
- place-item  : vertical horizontal

220225
- place-content : vertical horizontal
- place-self : 개별적으로 vertical horizontal
- ** .item*20>{$}
- Auto columns and rows : 크기 / grid-auto-flow : (방향, default=row)
- min/max ,주 용례 => repeat(4, minmax(100px, 1fr))
- auto-fit / auto-fill(dont have empty spaces) , repeat(auto-fit/auto-fill, minmax(100px, 1fr))
- min-content / max-content