#readme 
set-up tailwind:
    npm install -D tailwindcss postcss autoprefixer vite 
    npx tailwindcss init -p 
    in tailwind.css:content["*"]
    in package.json: add script

          "scripts": 
          {
                "start":"vite"
          },
    add a main.css file and add three lines in it:
        @tailwind base;
        @tailwind components;
        @tailwind utilities;

    add html file and link css file inside it
>------we  can create class of our own<-----
>-----website will not be slow-----< 
first section:
nav{
    div{
        div     
        image-link to home page
        (div
            text
            div)x5
        div{
            image
            button
            div
                button img
        }
        
    }
    
}


hero section:

div(width-full background-color-dark blue/background gradient flex justify-center){
    left section:
        text:
            h1
            green underline(bg-color)
            paragraph(text-size,family,padding,line-height,color)
            button(color,bg-color,rounded,hover:transition)
    right section:
        image(max-width)

}

shape-section{
    img{
        width:100%
    }
    div(absolute width:100%){

    }
}

next section:
2 images(absolute)
2 div
div{
    left section{
        heading-span
        list
        div{
           2 button
        }
    }
    right section{
        background image
    }
}

card section:

div{
    div{
        image
        div{
            text
            paragraph
            know more
        }
        
    }
}

next feature section(bg-color,):
div(max-width 1080px box){
    1.Content box():
        heading
        div
        div{
            left section
            right section
        }

    2.cards(grid){

    }
    3.demo box(flex){
        text span
        button
    }
}

card section(bg-white) :
    2 images
    6 element in Grid:
    1st element is not card
        each element:
            background image
            icon 
            heading
            paragraph 
            button
    
    
core-feature-section{
    heading
    div
    paragraph
    grid section:
    card{
        image
        heading 
        paragraph
    }
}

section{
    div{
        left-section{
            heading
            div
            paragraph
        }
        right-section{
            top-gradient
            photos section animation
            bottom-gradient
        }
    }
}


expericence person:
div{
    div{
        heading
        div{

        }
        image
        div{
            div{
                div{
                    icon
                }
            }
            image
            paragraph
            div{
                div{
                    icon
                }
            }
        }
        div{
            6 divs
        }
    }
}

footer{
    div{
        div{
            image
            p
            p
            p
            paragraph
            heading
            form{
                textarea and button
            }
            div{
                image
                image
            }
        }
        div{
            list {
                heading
                items
            }
            list {
                heading
                items
            }
            list {
                heading
                items
            }
            list {
                heading
                items
            }
            list {
                heading
                items
            }
        }
        div{
            list {
                heading
                items
            }
            list {
                heading
                items
            }
            list {
                heading
                items
            }
            list {
                heading
                items
            }
            list {
                heading
                items
            }
        }
        div{
            list
            
        }
    }
}
