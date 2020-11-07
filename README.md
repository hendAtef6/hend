body {
    margin: 0;
    padding: 0;
}

header {
    padding: .1em 0;
    background-color: #222222;
}

nav {
    text-align: center;
}

header nav ul li{
    font-family: 'Courier New', Courier, monospace;
    list-style: none;
    display: inline;
    margin: 0 10%;
}        

.header_link{
    color: white;
    text-decoration: none;
}

.header_link:hover{
    color: gold;
}

#sub_title {
    text-align: center;
    background-color: gold;
    padding: 6em;
}

#sub_title h4{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    text-transform: uppercase;
    font-size: 4em;
    margin: 0;
}

#sub_title span{
    color: white;
}

.img_section{
    border-top: white solid 1px;
}

#main_img {
    background: url("../images/hend_1.jpg") center no-repeat ;
    background-size: cover;
    margin: 0;
    height: 26em;
    width: 100%;
}

#content_div{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-column-gap: 1.4em;
    grid-row-gap: 1.4em;
}

#content_section{
    display: block;
    margin: 0;
    margin-top: 0;
    background-color: black;
    border-top: gold solid 1px;
    border-bottom: gold solid 1px;
    padding: 2em;
}

#content_div .content_item{
    /* width: fit-content; */
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    border-radius: 1em;
    font-size: 1.3em;
    text-transform: uppercase;
    padding: 4em;
}

#content_div .content_item:nth-child(1){
     background: url("../images/hend_2.jpg") center;
}

#content_div .content_item:nth-child(3){
     background: url("../images/hend3.jpg") center;
}

#content_div .content_item:nth-child(5){
     background: url("../images/hend_4.jpg") center;
}

#content_div .content_item:nth-child(even){ 
    /* justify-content: center; */
    /* justify-self: center; */
    background-color: wheat;
}

#contact_info{
    height: 12.5em;
    border-radius: 10px;
    margin:4em auto 2em;
    background: orange;
    width: 50%;
    float: right;
    padding: 3em;
}

#sign_up{
    float: left;
    border-radius: 10px;
    margin:4em auto 2em;
    background: salmon;
    width: 33%;
    padding: 3em;
}

#sign_up fieldset{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-weight: 600;
    border: none;
}

#sign_up fieldset label{
color: gold;
    display: inline-block;
    width: 5em;
}

#contact_info h1, #sign_up h1{
    display: block;
    width: fit-content;
    margin: auto;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 20px;
}

#sign_up #button{
    padding: 4px 10px;
    display:block;margin: 10px auto; background-color: white; border: none; border-radius: 5px;
}

#sign_up h1{
    color: black;
    margin-bottom: 1.4em;
}
#contact_info ul{
    list-style: none;
}

#contact_info ul li{
    color: white;
    margin: 4px 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

#contact_info ul li span{
    color: black;
    font-weight: bold;
}
