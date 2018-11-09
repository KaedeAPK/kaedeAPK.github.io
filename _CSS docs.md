# CSS Reference

## Unit of the Char
    px : 1px;
    pt : 1.33px;
    em : 
        default 16px.
        1.2em: x1.2 of parent element.
        same as '%'.
    rem: 
        1 rem is same as root element font-size.
        


## body
    max-width: 800px;
    margin: N% auto;
    // automaticaly centeralise N% window width.

## bottun
    // id="btn"
    background-color: #4CAF50;
    border: none;
    color: white;
    // Char Color
    padding: 15px 32px;
    // 
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;

## OVER FLOW
    overflow: hidden;
    // can't see anything over the container.
    visible;
    // can see, but out of the border.
    auto;
    // make scroll var!


## a
    a {
        text-decoration: none;
        color: #fff;
    }
    a:hover {
        color: red;
    }
## active or not
    li a {
        display: block;
        color: #000;
        padding: 8px 16px;
        text-decoration: none;
    }

    li a.active {
    background-color: #4CAF50;
    color: white;
    }

    li a:hover:not(.active) {
        background-color: #555;
        color: white;
    }
## flex
.flex-container {
  display: flex;
  flex-direction: row;
  <!-- 1 2 3 4 -->
}
## id selector
    #para1 {
        text-align: center;
        color: red;
    } 