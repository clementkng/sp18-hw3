## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
Nil in Ruby represents that there is not a value present for the field it 
set to, so this represents that if no value shows up, then 186 (the 
placeholder value) is assumed to the value. It is not rendered, but it
shows up as a default grayed out value in the text field.  

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
Because there is no route set up that matches a get request for teachers.

3. What type of request did your browser just perform?
A get request.

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
http://localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?
Because this is a post request, which is set up in the routes file to render
the HTML view. 