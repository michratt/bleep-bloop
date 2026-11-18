# bleep-bloop
Nav{
  text-align:center;
  background-color:pink;
  margin-bottom:-5px;
}

/** This will modify only the unordered lists inside the div Nav **/
#Nav ul { 
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  display: inline-block;

}

#Nav li {
  float: left;
}

#Nav a:link, a:visited {
  display: block;
  width: 120px;
  font-weight: bold;
  color: rgb(34, 31, 71);
  background-color: rgb(84, 91, 97);
  text-align: center;
  padding: 4px;
  text-decoration: none;
  text-transform: uppercase; 
}
/**changes the color of the a tag when something happens to it **/
#Nav a:hover, a:active {
  background-color: rgb(77, 152, 223);
}/**end of nav stuff**/
