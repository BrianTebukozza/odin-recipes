# odin-recipes

lessons so far
headings
bold (strong)
italics/ emphasis (em)
images (img src="" alt="" height= width=)
anchor/links (a src="" alt="")
target inside links open into new page if openned
paragraph (p)
unordered list (ul
li)
ordered list (ol
li)
comments (<!--comments in between here-->)

git
create a repo on github
copy code - ssh
clone
git clone ssh press enter (this makes the repo accessible on your local machine)
git add .
git status
git commit (for detailed commits)
git commit -m "message"
git push origin main to push to github

cd . to home directory
cd .. back to previous directory
cd Documents to documents directory
cd ~ to home directory
rm -rf directory name. deletes the folder and the contents
mv (target folder to be moved) (destination)
mkdir (name) new directory
touch (file name) new file

css
follows the following syntax: selector: property: value
div {
color: white
}
in this case div is the selector, color is the property and white is the value.
use : to separate property from value
put the selector our of curly barackets and put the property and value inside

types of selectors
universal selector: use (\*) as the selector

class selector:
here you assign a class with the elements you want to work on in the css
eg: HTML <p class="click-this">click here</p>
CSS: .click-this {
color: red;
}
put a dot(.) when calling that selector in CSS

you can use mulitple classes to a singe element
class="mobile-money money-transfer"

avoid spaces in separate words that belong to one class. use spaces to separate classes. classes are case sensitive. dont begin with numbers while naming classes

type selector:
use a particular type assigned for example
div for all divs
p for all paragraphs
ol for all ordered lists

CSS: div {
color: blue;
}
all divs will become blue

note: always terminate on the last property and value with ;

ID selectors
similar to class selectors

eg: HTML <p id="click">paint a ball</p>
CSS: #click {
color: red;
}
put a dot(#) when calling that selector in CSS

note each element an ID is attributed to a particular element.
you have to use it once. Use them sparingly

dont start an ID with a number

THE GROUPING SELECTOR
.read {
color: white;
background-color: black;
/_ several unique declarations _/
}

.unread {
color: white;
background-color: black;
/_ several unique declarations _/
}

if 2 groups of elements share some of their style declarations
you can group them and separate them with a comma

.read,
.unread {
color: white;
background-color: black;
}

.read {
/_ several unique declarations _/
}

.unread {
/_ several unique declarations _/
}

chain selectors
you can chain 2 different selectors and use .to call the class selector or #to call the ID selector

.word.use {
color: white;
}
you are call all class elements with the class selector word and all with the selector use

.world#oil {
color: blue;
}
you are calling all the elements with the class selector word and ID selector oil

i have forked a repo
cloned it to my local machine
used the git remote -v command
used the git remote add upstream (SSH code) command

css
used external, internal and inline css

external css - make a separate file of css. link it in the head
internal css - in the head create a style section and add attributes in between the tags
inline css - in the first tag, at the put the attributes starting with a style and separate with a ;
